# Nodus Fall (源初之结) Technical Reference, Hero Archetypes & Build Calculation Matrix

Public engineering companion, stat-formula reference, and co-op team synergy documentation for **Nodus Fall (源初之结)** — maintained alongside the live bilingual community platform at [NodusFallDB Wiki & Build Database](https://nodusfalldb.com/).

Effective team composition and DPS/survivability optimization in four-player Nodus Fall expeditions require auditing multiplicative passive buckets, elemental resonance windows, weapon base scaling curves, and stamina economy thresholds rather than relying on naive sheet-damage numbers.

### 1. Four Core Hero Archetypes & Expedition Combat Roles

Squad balance across high-corruption endgame nodes hinges on combining complementary defensive anchors, stagger breakers, and burst windows across the four primary hero archetypes cataloged in the [Nodus Fall Characters & Classes Guide](https://nodusfalldb.com/characters) (and mirrored in Simplified Chinese via the [《源初之结》全角色实机图鉴](https://nodusfalldb.com/zh-CN/characters)):

| Archetype Role | Primary Resource Mechanic | Co-Op Squad Synergy Contribution | Recommended Stat Priority | Scaling Focus |
| :--- | :--- | :--- | :--- | :--- |
| Vanguard Anchor | Guard Gauge & Parry Counter | Generates teamwide damage-reduction aura & interrupts boss channeled ultimates | Armor, Block Efficiency, Threat Gen | Frontline mitigation + stagger uptime |
| Resonance Striker | Combo Chain & Elemental Stacks | Converts elemental primes into 2.4x multiplicative detonation bursts | Crit Rate, Elemental Mastery, Attack Speed | Single-target boss phase burn |
| Kinetic Weaver | Cooldown Echo & Zone Fields | Applies crowd-control slow fields, projectile deflection, and vulnerability debuffs | Cooldown Haste, Aura Radius, Energy Regen | AoE wave clear + debuff amplification |
| Field Tactician | Triage Charges & Link Tether | Distributes continuous HoT ticks, cleanses corruption stacks, and shares weapon buffs | Healing Power, Max HP, Revival Speed | Sustainment in extended raid phases |

### 2. Multiplicative Damage Buckets & Stagger Break Windows

Understanding additive versus multiplicative stat stacking prevents wasted weapon affix slots when optimizing loadout builds in the [Nodus Fall Build Calculator](https://nodusfalldb.com/builds/builder):

- **Bucket A — Base Weapon Power & Flat Hero Attack**: Scales linearly with weapon upgrade tier (+1 to +15). Diminishing marginal value occurs quickly once flat attack exceeds 2,400 without percentage multipliers.
- **Bucket B — Skill Multiplier & Archetype Stance Modifiers**: Core ability coefficients range from `180%` rapid combo finishers to `620%` charged execution strikes.
- **Bucket C — Elemental Weakness & Corruption Armor Shred**: Breaking an elite enemy's posture bar opens a `4.5s` exposed vulnerability window that applies a separate `1.50x` multiplier alongside armor-penetration passives.
- **Bucket D — Critical Hit Variance**: Optimal efficiency favors maintaining an approximate `1 : 2` ratio between Critical Hit Probability (`45%–65%`) and Critical Damage Bonus (`+90% to +130%`) before investing in conditional on-kill triggers.

### 3. Weapon Passives, Affix Ceilings & Synergy Pairing

Not all legendary weapons pair cleanly with fast-hitting multi-strike heroes. High-cooldown weapons reward front-loaded charged attacks and parry triggers, whereas low-base-attack fast weapons maximize proc-per-second status stacks. Complete frame data, base curves, and passive trigger cooldowns are indexed inside the [Nodus Fall Weapons Database](https://nodusfalldb.com/database/weapons).

| Weapon Weight Class | Attack Cadence | Stagger Output per Hit | Ideal Passive Trigger Archetype | Common Build Trap to Avoid |
| :--- | :--- | :--- | :--- | :--- |
| Heavy Greatsword / Hammer | Slow (1.45s–1.80s cycle) | High (32–44 posture dmg) | Charged finisher & perfect-parry counters | Stacking on-hit procs with internal ICDs |
| Dual Blades / Twin Edge | Fast (0.42s–0.55s cycle) | Low (8–12 posture dmg) | Multi-hit elemental stack & crit-bleed triggers | Over-investing in charged-attack-only runes |
| Medium Polearm / Halberd | Balanced (0.85s–1.05s) | Moderate-High (18–25) | Sweep range amplifiers & cooldown resets | Neglecting stamina regeneration thresholds |
| Focus Catalyst / Staff | Cast-channel variable | Utility / Zone stagger | Field duration extension & vulnerability aura | Zero defensive HP margin on high-tier raids |

### 4. Bilingual Database Routing (English & Simplified Chinese)

NodusFallDB maintains synchronized bilingual patch notes, weapon stat diffs, and theorycrafted co-op squad compositions across dedicated localized routes without cross-language mixing:

- [Nodus Fall Wiki, Database & Builds Home](https://nodusfalldb.com/) — Global English hub for tier lists, patch tracking, and squad tools.
- [Nodus Fall Characters & Classes Matrix](https://nodusfalldb.com/characters) — Full kit breakdowns for all 4 hero archetypes.
- [Co-Op Team & Loadout Build Calculator](https://nodusfalldb.com/builds/builder) — Interactive stat simulator testing weapon passives and squad resonance.
- [Nodus Fall Weapons Database](https://nodusfalldb.com/database/weapons) — Complete weapon base scaling stats, passives, and upgrade paths.
- [《源初之结》中文 Wiki 与配装攻略首页](https://nodusfalldb.com/zh-CN) — Official Simplified Chinese knowledge base and combat guides.
- [《源初之结》全角色与4大职业实机图鉴](https://nodusfalldb.com/zh-CN/characters) — Detailed Simplified Chinese skill ratios and role breakdowns.