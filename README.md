# Thrive 🌿
### A community resilience game for the polycrisis era

---

## The Idea

A free, open source, idle RPG that teaches real-world preparedness and community resilience — disguised as a cosy game. Inspired by Animal Crossing, Stardew Valley, and Pokémon GO.

The core insight: **resilience is a network effect.** One prepared household is fragile. A thousand connected prepared households in a region is genuinely robust. The game makes building that network feel like tending a garden, not preparing for apocalypse.

Most preparedness tools are either boring checklists or fear-based. Thrive is neither. It's warm, communal, and empowering — and it creates real behaviour change as a side effect of being fun.

---

## Why It Matters

We're in a polycrisis — overlapping climate events, power grid vulnerabilities, supply chain fragility. Governments aren't moving fast enough. The window to build community resilience *before* a crisis is now.

Thrive is **civic infrastructure disguised as a game**:
- People don't engage with "civil defence preparedness campaigns"
- People *do* engage with games, streaks, community events, finding neighbours
- The actual behaviour change happens as a side effect of fun

Open source + global means:
- Any community anywhere can localise and run it
- It survives because communities fork and maintain it
- No commercial pressure, no data harvesting, no shutting down if unprofitable
- Can integrate with actual emergency management systems over time

---

## Core Design Pillars

1. **Fun first** — works as a standalone idle/RPG game even if you never think about preparedness
2. **Real-world parallel** — every in-game action maps to something you can actually do
3. **Community multiplier** — the game gets more valuable the more people around you play
4. **Zero fear** — framing is always empowerment, warmth, community-building. Never doomsday.
5. **Works offline / low-tech** — single HTML file, no backend required, runs anywhere
6. **Meets you where you are** — your household, your budget, your constraints, your region

---

## Aesthetic & Feel

- Animal Crossing meets Stardew Valley
- Warm parchment tones, rounded bubble panels, soft greens and teals
- Cosy, friendly, approachable — feels like a small-town general store
- Name: **Thrive** — not just surviving, but building something that flourishes

---

## Household Settings (New)

Before playing, or at any time, players configure their actual household situation. This personalises quests, scenarios, and advice to be genuinely useful rather than generic.

### Household Composition
- Number of household members + ages (infant, child, adult, senior)
- Any members with disabilities or access/functional needs (mobility, vision, hearing, cognitive, medical equipment)
- Pets and animals (species, count)
- Caregiving responsibilities (caring for someone outside the household)

### Location & Environment
- Region / climate zone (affects seasonal quests and relevant scenarios)
- Housing type (apartment, house, rural, mobile home, boat)
- Renter vs. owner (affects what modifications are possible)

### Financial Reality
- Current savings / liquid resources (ranges, not exact: <$500 / $500–2k / $2k–10k / $10k+)
- Monthly income (range)
- Job loss toggle — are you currently employed or recently lost work?
- Benefits / assistance received (affects recommendations, never judgemental)

These settings change *what the game recommends*, not whether you can play. Someone with $300 savings and three kids gets different quests than someone with $10k and a paid-off house — both are valid and both can build resilience.

---

## Scenarios System (New)

Scenarios are the heart of Thrive's depth. They let players prepare for *specific, realistic events* — not abstract "emergencies."

### What a Scenario Is
A scenario is a structured situation with:
- **Context** — what's happening, the backstory, the stakes
- **Constraints** — what you don't have (power, water, income, mobility, time)
- **Phases** — Before / During / After, each with specific quests
- **Household modifier** — how the scenario intersects with your settings (a heat wave hits differently if you have an infant or no AC)
- **Community angle** — how neighbours and networks factor in

### Scenario Library

**Curated Real-World Events**
These are based on documented historical events — players can learn what actually happened, what worked, what didn't.

- 🌊 **New Orleans — Hurricane Katrina (2005)** — levee failure, evacuation failure, shelter-in-place decision tree, neighbour-dependent survival
- 🧊 **Austin — Winter Storm Uri (2021)** — grid failure in unexpected cold, burst pipes, multi-day heat loss, car as only warm space
- 💸 **Argentina — Economic Collapse (2001)** — currency devaluation, bank freezes, hyperinflation, barter economy emergence
- 🔥 **California Wildfires — Camp Fire (2018)** — rapid evacuation, go-bag reality check, air quality, communication failure
- 🌊 **Japan — Tōhoku (2011)** — earthquake + tsunami + nuclear, multi-hazard, community mutual aid, long-duration displacement

**Regional Scenario Templates**
Plausible near-future events by region, grounded in climate and infrastructure data:

- 🌡️ **Texas — El Niño Heat Wave + Grid Failure** — prolonged 105°F+ heat, rolling ERCOT outages, cooling centres, medication storage, car and community cooling
- 🌧️ **Houston-Style Flash Flooding** — rapid inundation, car escape, vertical evacuation, flood insurance reality
- 🌀 **Gulf Coast Hurricane Season** — Category 3–4 landfall, 72hr pre-storm window, shelter-in-place vs. evacuation
- 🌫️ **Western Smoke Season** — weeks of hazardous air quality, indoor filtration, vulnerable household protection
- ❄️ **Northern Winter Grid Failure** — cold snap + power loss, insulation, heating alternatives, pipe protection
- 🏙️ **Urban Supply Chain Disruption** — multi-week shortage, no panic buying, community resource sharing
- 📉 **Personal Economic Crisis** — job loss, medical debt spike, food insecurity — resilience from the inside

**User-Created Scenarios**
Players (and community contributors) can build their own scenarios using a structured template:
- Name, region, type (weather / economic / infrastructure / health / multi-hazard)
- Phase structure (Before / During / After)
- Up to 10 quests per phase
- Household modifiers (how does this scenario change with kids? elderly? no car? no savings?)
- Can be exported as JSON and shared

---

## Game Mechanics (Current + Planned)

### ✅ Built (v0.1)
- Character creation (name, avatar, role)
- 9 roles with stat bonuses (Farmer, Medic, Engineer, Builder, Scholar, Counselor, Animal Keeper, Leader, Warrior)
- 10 real-world quests with step-by-step instructions and XP rewards
- Inventory / supply tracker with expiry warnings
- Household + neighbour management
- Community share board (I have / I need)
- Resilience score across 8 categories
- XP + levelling system
- Day streak tracker
- LocalStorage save state

### 🔜 Next (v0.2)
- **Household settings** — full configuration of members, finances, location, needs
- **Scenario system** — curated library + user-created scenarios
- **Scenario quests** — phase-based Before/During/After quest chains for each scenario
- **Household modifiers** — scenarios adapt to your actual situation
- **Idle mechanics** — resources tick over time, offline progress
- **Seasonal quests** — real calendar tied to seasons
- **Village code** — shareable JSON so real-world neighbours can link their games

### 🌍 Future (v1.0+)
- **Real-world event triggers** — weather events or power outages in your region unlock special quests
- **Community events (like GO raids)**
  - "Find a Medic" — locate someone with first aid skills nearby
  - "Village Market" — post/match resources with neighbours
  - "Neighbourhood Audit" — suburb earns a collective resilience score
  - Seasonal challenges tied to real scenarios
- **Historical event replays** — step through Katrina or Uri day by day, make decisions, see outcomes
- **Global resilience map** — see community resilience scores by region
- **Event API** — hooks for emergency management agencies to trigger in-game events
- **Localisation** — community-translated versions for any language/region

---

## Technical Approach

- **v0.1–v0.2:** Single HTML file (HTML + Tailwind CDN + vanilla JS), LocalStorage save state. Zero dependencies. Someone in a village with intermittent internet can use it.
- **v0.3+:** Optional lightweight backend for community features (village codes, shared boards, scenario sharing). Still works offline without it.
- **Open source from day one** — GitHub, clear README, MIT or similar licence

The single-file approach is a feature, not a limitation. It's the most resilient possible distribution format — ironic and intentional.

Scenarios are stored as JSON objects inside the HTML file — they're data, not code, so community contributors can add scenarios without touching the game engine.

---

## Distribution Philosophy

Start with yourself. Build what's useful to you. Put it on GitHub with a clear README explaining the vision. The right contributors will find it — people who get *why* it exists, not just developers looking for a project.

The scenarios system is a contribution engine: anyone can write a scenario for their region, their event, their community. The game becomes more valuable with every new scenario added.

---

## The Name

**Thrive**

Not surviving. Not just getting through. *Thriving* — building something that grows, connects, and sustains. The name signals the game's orientation: forward, warm, generative. Not bunkers. Not fear. Roots and networks and people helping people flourish.

---

## Prompt for Future AI Sessions

Use this to pick up where you left off:

```
I'm building an open source community resilience game called "Thrive" 
— a cosy idle RPG inspired by Animal Crossing, Stardew Valley, and Pokémon GO.

The core idea: resilience is a network effect. The game teaches real-world 
preparedness through bite-sized quests, idle mechanics, scenario simulations, 
and community events — but it works as a fun standalone game even if you 
never think about preparedness.

Aesthetic: Animal Crossing — warm parchment tones, rounded bubble panels, 
Nunito font, soft greens and teals. Cosy and empowering, never fear-based.

Tech: Single HTML file (HTML + vanilla JS + Tailwind CDN), LocalStorage save,
no backend required. Open source. Works offline.

Current features built (v0.1):
- Character creation with 9 roles (Farmer, Medic, Engineer, Builder, Scholar, 
  Counselor, Animal Keeper, Leader, Warrior), each with stat bonuses
- 10 real-world quests with step-by-step instructions and XP
- Inventory/supply tracker with expiry warnings (90-day alert)
- Household + neighbour management
- Community share board (I have / I need)
- 8-category resilience score (Water, Food, Medical, Tools, Power, 
  Garden, Skills, Community)
- XP + levelling system, day streak tracker, activity log

Next priorities:
1. Household settings — members, location, finances ($), job status, disabilities/needs
2. Scenarios system — curated library (Texas heat wave, Hurricane Katrina, 
   Austin freeze, Argentina economic collapse) + user-created scenarios
3. Idle mechanics — passive resource generation, offline progress
4. Seasonal quests tied to real calendar
5. Village code — shareable JSON to link neighbours' games locally

Scenario structure: each scenario has a Context, Constraints, Before/During/After 
phases with quests, and Household Modifiers (how the scenario changes based on 
your household settings — kids, disabilities, finances, etc.).

Longer term: historical event replays, real-world event triggers, 
community raid-style events (Find a Medic, Village Market), global 
resilience map, emergency management API hooks.

The single HTML file is intentional — most resilient possible format, 
works anywhere, shareable as one file. Scenarios are JSON data objects 
inside the file so contributors can add scenarios without touching game logic.

[Attach the current thrive.html file to continue building]
```

---

*Started: June 2026*
*Status: v0.1 playable prototype (was Spark & Co.)*
*Renamed: Thrive*
*Licence: TBD (MIT or similar)*
