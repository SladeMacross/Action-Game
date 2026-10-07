# Megametroidvania: Brainstorm History

Summary of the original brainstorm chat (before 10/07/2026). `Design Doc.md` is the main reference; this file records how the ideas got there, including the ones that were cut, changed or moved to other games.

---

## 1. How the idea developed

| # | Idea | Outcome |
|---|---|---|
| 1 | Mega Man combined with a metroidvania, a "megametroidvania" | **Kept** as the core |
| 2 | Helldivers 2 enemy classes (light, medium, heavy, tank, air), merged into three groups | Changed several times (see below) |
| 3 | Primary, secondary and tertiary weapon slots, plus armor with stats you allocate | **Cut** as too complex |
| 4 | Dash as an attack | **Kept**: the dash does damage |
| 5 | Flipped proposal: dash and melee for infantry, buster for armored, an alternate buster mode for air | Changed again |
| 6 | Infantry and air merged, since the buster already hits fliers | Led to the armor tier system |
| 7 | **Three armor tiers:** weak (anything works), medium (buster or charge), heavy (charge only) | **Kept** |
| 8 | Wall jump | **Kept** |
| 9 | Skill trees for everything, with enemies that scale so late weak enemies match early heavy ones | **Kept** |
| 10 | Upgrades that break armor tiers are what drives progression | **Kept** |
| 11 | Identity: Mega Man plus beat-'em-up (dash and melee) plus metroidvania complexity and secrets | **Kept** |
| 12 | Bosses **don't** give powers; they drop items that NPCs trade for skill points (the "mage" example) | **Kept** |
| 13 | Contra influence: platform shooting, intensity, varied level types | **Kept** (but no one-hit deaths) |
| 14 | Cyberpunk setting, replacing the mage example | Working direction, **now undecided** |
| 15 | Vehicle levels like Contra's perspective changes, as horizontal or vertical shmups, Blade Runner style | **Kept**, to be used sparingly |
| 16 | Ideas from the *[2030] Army of One* story: "one alone, many tools," jammer zones, PMC contracts | Explored, then **separated** |
| 17 | The "eras" concept: falcon, dog and horse, then drones and a car, then cyberpunk versions | **Parked** as its own idea |
| 18 | Realization that too many ideas belonged to different games | Led to the split |
| 19 | `agent.txt` (2017): a high-tech world and the Agent's gear, trimmed to remove the experiment story and mutations | Became the **Agent game** |
| 20 | Tension between stealth and scanning on one side and Mega Man-style power growth on the other | Led to the final split |

---

## 2. The final split

### Game 1: the Action Game (this folder)
See `Design Doc.md`.

### Game 2: the Agent game (`Projects\Agent Game`)
- Based on the 2017 notes: a high-tech near-future world, the Agent's badge, weapon, vehicle and drone
- Shared modules (AI, communicator, scanner, beam, shield, self-destruct, stealth) as the upgrade system
- Stealth and tactics: scan, plan, execute; lethal combat
- Has its own design doc

### Parked
- **The eras game:** a bloodline across ninja, modern and cyberpunk eras, with companions that evolve from animals to machines
- ***Army of One*:** stays a story or movie. Still separating my own ideas from the AI-generated parts.

---

## 3. Status at the end of the brainstorm
- `Design Doc.md` created as the main reference.
- Nothing built yet. No code or prototype.
- Planned next step: a **browser prototype** of the test room (all moves, one enemy per armor tier including a flier, debug toggle for armor-breaking upgrades), or work through the open decisions starting with the setting.
