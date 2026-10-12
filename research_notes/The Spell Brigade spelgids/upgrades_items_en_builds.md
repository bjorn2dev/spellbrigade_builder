# The Spell Brigade: in-run upgrades, items, stats and build systems (state as of 2026-10-12)

> **How these notes were made.** The sandbox egress policy blocked every game-specific host for direct fetching: thespellbrigade.wiki.gg, thespellbrigade.wiki, steamcommunity.com, store.steampowered.com, whisperofthehouse.com, gamegrin.com, reddit, steamdb, youtube, 2upskill and pixelnitro all returned proxy 403 or DNS failure. Everything below comes from WebSearch result extracts, which quote or summarise those pages. All numbers are therefore second-hand quotes of the cited pages. They need an in-game or direct-page check before they go into the build-planner as hard data. When a page's age showed up in the snippet, I've noted it: the wiki.gg Upgrades page was about 134 days old (roughly June 2026, post-1.0) and the Enchantments page about 288 days old (roughly Dec 2025/Jan 2026, late Early Access).
>
> **Version timeline used throughout:**
> - Early Access launch: 18 Sep 2024 ([MassivelyOP](https://massivelyop.com/2024/09/18/bullet-heaven-co-op-game-the-spell-brigade-is-now-available-in-early-access/))
> - EA Update 0.7.2: 29 Jan 2025 ([SteamDB](https://steamdb.info/patchnotes/17171436/))
> - EA "Update 8" (0.8.0.2869): 5 Mar 2025 ([SteamDB](https://steamdb.info/patchnotes/17603290/))
> - EA Update 9 "Dark Devotion" (0.9.0.3352): 16 Apr 2025 ([Steam announcement](https://steamcommunity.com/games/2904000/announcements/detail/528717787215955183))
> - EA Update 13: the final EA update ([Rogueliker](https://rogueliker.com/the-spell-brigade-update-13/))
> - 1.0 full release: 29 Apr 2026 ([Gematsu](https://www.gematsu.com/2026/03/co-op-bullet-heaven-roguelite-game-the-spell-brigade-launches-april-29-for-ps5-pc))
> - 1.0 Patch 9: 1 Jul 2026 ([thespellbrigade.wiki changelog](https://thespellbrigade.wiki/changelog/))
> - 1.1 "Realm Sweep": ~early Sep 2026, with patch 1.1.4.19571 dated 17 Sep ([Steam news](https://store.steampowered.com/news/app/2904000/view/715662120170030645))
> - 1.2: the official X account header reads "PS5 & Steam 1.2 OUT NOW". Patch 1.2.0.20127 is dated 06-10-26 ([X](https://x.com/thespellbrigade), [Steam community hub](https://steamcommunity.com/app/2904000)).
>
> **Current version = 1.2.x (Oct 2026).** I found no 1.2 balance notes that change upgrades or scrolls.

## 1. What kinds of in-run upgrades exist, and what are the exact system names?

### Takeaway
The game uses its own vocabulary. "Rings", "tomes", "curses", "blessings" and "relics" don't exist as current systems. In a run you get:
- **Improvements** (the in-game word for level-up choices; the wiki calls them "Upgrades"), split into **Character Upgrades** and **Spell Upgrades**
- **Spell Levels**, which unlock **Infusions** (elements) at spell level 7 and 14
- **Augments**/augmentations: spell-specific modifiers from Objectives and chests
- **Scrolls**: temporary boons from Scroll Chests. They were called **Relics** in Early Access.
- Pickups: Mana orbs (XP), Health Potions, Mana Magnet, Revive Cores

Outside the run, these shape the build:
- **Enchantments**, bought with gold, each with a **Mastery**
- **Covenants** and **Trial Covenants** (difficulty modifiers that give "Devotion")
- **Ascension** (character prestige)
- Each wizard's **Traits**

### Cited Findings
- **Improvements** is the in-game term for level-up offers. Banish, Lock and the Denial covenant are all worded around "Improvements", e.g. "You get offered one Improvement less" — [wiki.gg Covenants](https://thespellbrigade.wiki.gg/wiki/Covenants); "You can Lock specific Improvements, so they will stay in place until the next Level Up" — [wiki.gg Enchantments](https://thespellbrigade.wiki.gg/wiki/Enchantments)
- The wiki's **Upgrades** page defines upgrades as per-run stat increases obtained on level up, in two families:
  - **Character Upgrades**: "stats increases that will boost character stats or spell stats for all spells, except Colossal Grace". All of them can appear regardless of chosen spells, except Colossal Grace.
  - **Spell Upgrades**: "each spell can receive specific upgrades that will increase its stats".
  - Source: [wiki.gg Upgrades](https://thespellbrigade.wiki.gg/wiki/Upgrades)
- Level-up options include spell upgrades (Damage, Range, Size, Cooldown for a specific spell) — [thespellbrigade.wiki Beginner's Guide](https://thespellbrigade.wiki/guides/beginners-guide/)
- **Infusions**: a spell can get its first infusion at spell level 7 (level 6 for Moon Mage) and a second at level 14. The two infusions combine into an advanced infusion — [wiki.gg Infusions](https://thespellbrigade.wiki.gg/wiki/Infusions); [Steam guide "The Spell Brigade [1.0]"](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916)
- **Augments**: spell-specific upgrades earned from objectives and chests. "Each successfully completed objective gives you a spell augmentation", and chests hidden on the map also give them. Example: the Reginald achievement "Augmentor" asks you to augment Astral Orbs 4 times in one mission — [Steam guide [1.0]](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916); [thespellbrigade.wiki achievements](https://thespellbrigade.wiki/achievements/)
- Example augment set, Magic Missile: Explosive Missile (detonates at end of life), Missile Split (splits at end of life, capped at 6 upgrades), Seeking Missile (targets the highest-HP enemy, +20% lifetime) — [wiki.gg Magic Missile](https://thespellbrigade.wiki.gg/wiki/Magic_Missile) (page about 689 days old, i.e. EA)
- "Extra Projectile — Adds +1 projectile per cast" is described as an augmentation in one guide — [thespellbrigade.wiki Beginner's Guide](https://thespellbrigade.wiki/guides/beginners-guide/) (secondary fan site)
- **Objectives** reward unique spell upgrades: "after completing an objective the Wizard(s) are rewarded with unique spell upgrades" — [wiki.gg Objectives](https://thespellbrigade.wiki.gg/wiki/Objectives)
- **Scrolls**: "Scrolls, previously known as Relics in the early access version, are temporary boons the player can obtain during missions."
  - Up to three Scroll Chests can appear in a mission. Opening one lets you choose 1 of 3 boons.
  - Source: [wiki.gg Scrolls](https://thespellbrigade.wiki.gg/wiki/Scrolls)
- Pickups in a run:
  - Health Potions drop randomly from monsters — [Whisper of the House achievements guide](https://www.whisperofthehouse.com/the-spell-brigade/achievements-guide)
  - Mana Orbs are XP, and a Mana Magnet pulls them in. The achievement "Unholy Attraction" asks for >666 Mana Orbs collected with a single Mana Magnet — [Steam guide [1.0]](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916)
  - **Revive Cores** are used to "blast yourself and your teammates back into action" — [Steam store page](https://store.steampowered.com/app/2904000/The_Spell_Brigade/)
- **Enchantments**: permanent upgrades bought with gold in the lobby. Each has 5 levels plus a **Mastery** bonus. Gold spent on Enchantments can be fully refunded at any time — [wiki.gg Enchantments](https://thespellbrigade.wiki.gg/wiki/Enchantments); [Steam guide "All Enchantments / Masteries"](https://steamcommunity.com/sharedfiles/filedetails/?id=3726023191)
- **Covenants**: per-run or per-player modifiers enabled in the lobby. **Trial Covenants** make the game harder and reward extra wizard XP and gold. Stacked trial covenants give **Devotion** — [wiki.gg Covenants](https://thespellbrigade.wiki.gg/wiki/Covenants)
- **Ascension**: a wizard reaching level 10 can be ascended, which resets them to level 1. The first two ascensions give a reward — [wiki.gg Ascension](https://thespellbrigade.wiki.gg/wiki/Ascension). The 1.0 launch coverage names a "new Ascension system" — [Gematsu](https://www.gematsu.com/2026/03/co-op-bullet-heaven-roguelite-game-the-spell-brigade-launches-april-29-for-ps5-pc)
- **Wizard Traits**: EA Update 8 reworked each wizard's stats and effects and added new Wizard Traits. Examples: Reginald's luck/drop-chance bonuses; Sun Mage dodge plus a smaller hitbox; Hatti damage bonus with a max-HP penalty; Ludwig +12 Armor, bigger hitbox, lower move speed. Each wizard also got unique Starter Spell buffs — [SteamDB Update 8](https://steamdb.info/patchnotes/17603290/); [sihmar copy of 0.8.0.2869 notes](https://sihmar.com/the-spell-brigade-update-0-8-0-2869-patch-notes-march-5-2025/)
- **Spell level beyond 20**: a PS5 trophy asks you to "upgrade one Spell to Level 21", so levels past 20 exist — [GameFAQs PS5 achievements](https://gamefaqs.gamespot.com/ps5/638324-the-spell-brigade/achievements). A guide says maxing a spell's level "unlocks a new mastery tree" — [TPose Gaming Ascension guide](https://tposegaming.com/spell-brigade-ascension/) (low confidence, unverified elsewhere)

### Inferences
- For the planner's data model, the in-run layers are:
  1. Character Upgrades (global stats, rarity-tiered)
  2. Spell Upgrades (per-spell stats, rarity-tiered)
  3. Spell Level (count of upgrades taken for a spell), which gates the Infusion slots at levels 7 and 14
  4. Augments (per-spell, from objectives/chests, capped per spell)
  5. Scrolls (from chests, 1-of-3 choice)
- Meta layers that set the baseline: Enchantments+Masteries, Covenants/Trial Covenants, Wizard Traits and Ascension.
- There's no "curse" item system. The negative modifiers are Trial Covenants, chosen before the run.

### Gaps
- I couldn't get an exact per-spell list of which Spell Upgrade types (Damage, Cooldown, Range, Size, Duration, Projectiles) each spell can roll; the wiki tables were cut off. The spells researcher may have this.
- I found no augment caps per spell besides Missile Split's 6. A player said "there is a limited amount of augments for each spell" ([Steam guide [1.0]](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916)).
- What "mastering" a spell at level 20 gives is unconfirmed. The "mastery tree" claim comes from one low-authority guide.

## 2. Full list of each upgrade/item, with exact names, numbers, rarity, stacks and unlocks

### Takeaway
I identified 13 named Character Upgrades with per-rarity values; tables below. Per-spell upgrades follow standard tiers such as 10/15/25/35% for damage. There are 20 basic+advanced Infusions, about 21 named current Scrolls (and 3 removed in 1.0 Patch 9), and roughly 19 Enchantments with Masteries. Values for the newest scrolls come from 1.0 Patch 9 (Jul 2026). Most upgrade values are from wiki pages dated before or around 1.0.

### Cited Findings

#### 2a. Character Upgrades (level-up Improvements). Source: [wiki.gg Upgrades](https://thespellbrigade.wiki.gg/wiki/Upgrades), page about 134 days old (~post-1.0)

| Exact name | Stat | Common | Rare | Epic | Legendary | Notes |
|---|---|---|---|---|---|---|
| Vitality Forge | Max Health | +100 | +200 | +300 | +400 | |
| Titan's Fury | Base Damage | 5% | 10% | 15% | 20% | Same values on the [Magic Missile page](https://thespellbrigade.wiki.gg/wiki/Magic_Missile) |
| Caster Precision | Critical Chance | 4% | 6% | 9% | 12% | Soft cap 80% |
| Wizard's Edge | Base Critical Damage | 10% | ? | ? | 50% | Conflict: [GameGrin](https://www.gamegrin.com/articles/useful-upgrades-to-survive-longer-in-the-spell-brigade/) says it raises base damage by 20%. The wiki says crit damage. Middle tiers not captured. |
| Colossal Grace | Spell Size | — (no Common) | 12% | 15% | 18% | Only offered if you hold a spell that can take Spell Size upgrades |
| Quickstep Surge | Base Move Speed | 8% | 12% | 18% | — (no Legendary) | |
| Veil of Haste | Base Cast Speed | 6% | 9% | 12% | 18% | |
| Wisdom's Embrace | Mana Gain (XP gain) | 7% | 12% | 17% | 21% | Soft cap 200%, max 241% |
| Rejuvenating Echo | Health Regeneration | 1 | 2 | 3 | 4 | No cap listed |
| Swift Overlay | Dodge | 4% | 6% | 9% | 12% | Soft cap 75%, max 98% |
| Fortune's Favor | Luck | 2 | 4 | 6 | 8 | Soft cap 25 (players report 24), max 50 |
| Mind's Reach | Mana Pull (pickup radius) | 8% | 12% | 18% | 24% | |
| Mystic Barrier | Armor | 16 | 26 | 36 | 50 | |

- Spell Size also lengthens Rocky Road but doesn't widen it — [wiki.gg Upgrades](https://thespellbrigade.wiki.gg/wiki/Upgrades)
- GameGrin (about 155 days old) describes Quickstep Surge as "increases your character's base move speed", and Titan's Fury as +5% base damage at the low tier — [GameGrin](https://www.gamegrin.com/articles/useful-upgrades-to-survive-longer-in-the-spell-brigade/)

#### 2b. Spell Upgrades (per-spell Improvements)
- Spell Damage: +10% / +15% / +25% / +35% (Common/Rare/Epic/Legendary) — [wiki.gg Upgrades](https://thespellbrigade.wiki.gg/wiki/Upgrades); [wiki.gg Magic Missile](https://thespellbrigade.wiki.gg/wiki/Magic_Missile)
- Magic Missile's own upgrades — [wiki.gg Magic Missile](https://thespellbrigade.wiki.gg/wiki/Magic_Missile) (EA-era page)
  - Cooldown reduction 10/15/25/35%
  - Range 0/16/27/38%. The rarity mapping is uncertain; the 0% probably means no Common tier.
  - Magic Missile can take range upgrades but not size or duration upgrades
- Example base stats (Magic Missile, the Wizard King's starter spell): Base Spell Damage 140, Base Cast Speed 0.44/s, Base Spell Size 0.98, Base Spell Range 9 — [wiki.gg Magic Missile](https://thespellbrigade.wiki.gg/wiki/Magic_Missile)
- Upgrade types named by guides: Damage, Range, Size, Cooldown; Duration exists for some spells — [thespellbrigade.wiki Beginner's Guide](https://thespellbrigade.wiki/guides/beginners-guide/); [wiki.gg Magic Missile](https://thespellbrigade.wiki.gg/wiki/Magic_Missile)

#### 2c. Infusions (elements applied at spell level 7 and 14)

Basic elements — [Steam guide "Infusion Elements and their Effects"](https://steamcommunity.com/sharedfiles/filedetails/?id=3729529643), [wiki.gg Infusions](https://thespellbrigade.wiki.gg/wiki/Infusions):

| Element | Status effect | Effect (fan-reported numbers) |
|---|---|---|
| Fire | Afterburn | Deals ⅓ of the hit damage (including crit) every 0.5 s, 3 times over 1.5 s. Doesn't stack. |
| Lightning | Sparks | Extra 50% of hit damage (including crit) to 2 nearby enemies |
| Acid | Corrosion | Enemy takes +10% damage from all sources for 3 s. Doesn't affect the initial hit; more hits extend the duration. |
| Ice | Slow | Slows by 10% of damage dealt (25% with Frost). Stacks additively, capped at 72%. A fan site says 1.0 changed Ice to a full freeze ([thespellbrigade.wiki elements](https://thespellbrigade.wiki/spells/elements/)). This conflicts. |
| Dark | Corruption | Added in EA Update 9. Old wiki text, marked outdated: corruption builds at 2× damage taken, the enemy turns on its allies once corruption ≥ its max HP, and this lasts 20 s or 4 attacks. Overhauled in Update 13 and "refined" in 1.0 ([wiki.gg Infusions](https://thespellbrigade.wiki.gg/wiki/Infusions); [AmeriMe Media on Update 13](https://www.amerimemedia.com/post/the-spell-brigade-ushers-in-spooky-season-with-update-13-new-spells-pumpkin-fits-and-frightening)) |

- At the start only the Fire infusion is offered. Lightning, Acid, Ice and Dark unlock as you infuse more spells — [Fantasy Warden beginner guide](https://fantasywarden.com/games/spell-brigade-beginners-guide) (attribution from search extract)
- Holding Ctrl on an infusion choice shows its effect in game — [Steam infusion guide](https://steamcommunity.com/sharedfiles/filedetails/?id=3729529643)
- The Steam guide lists 20 infusions: 5 basic plus 15 two-element combinations — [Steam guide [1.0]](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916)

Advanced infusions (second infusion at level 14). Names conflict between sources:

| Combo | Name(s) reported | Effect notes | Sources |
|---|---|---|---|
| Fire + Fire | Wildfire | Afterburn can crit; 1.0 rework: "Critical Damage crits" | [wiki.gg](https://thespellbrigade.wiki.gg/wiki/Infusions), [thespellbrigade.wiki](https://thespellbrigade.wiki/spells/elements/) |
| Lightning + Lightning | Thunder | Impact/burst damage ("Thunder burst" in 1.0) | [Whisper](https://www.whisperofthehouse.com/the-spell-brigade/best-spells-elements), [thespellbrigade.wiki](https://thespellbrigade.wiki/spells/elements/) |
| Acid + Acid | Corrosion (wiki) / Venom (other sources) | Acid + Weakness | [wiki.gg](https://thespellbrigade.wiki.gg/wiki/Infusions); [shapes.inc](https://shapes.inc/fandom/the-spell-brigade/spells-and-elements); [Steam thread](https://steamcommunity.com/app/2904000/discussions/0/597399204164281582/) |
| Ice + Ice | Frost | Slow (25%) plus a small chance to freeze | [wiki.gg](https://thespellbrigade.wiki.gg/wiki/Infusions) |
| Dark + Dark | Void | One fan guide says Void needs all team members on Dark (unverified) | [Steam guide](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916), [thespellbrigade.wiki](https://thespellbrigade.wiki/spells/elements/) |
| Fire + Lightning | Plasma | Burst damage | [Whisper](https://www.whisperofthehouse.com/the-spell-brigade/best-spells-elements) |
| Fire + Acid | Brimstone / Corrosion (conflict) | | search extract citing [shapes.inc](https://shapes.inc/fandom/the-spell-brigade/spells-and-elements) |
| Fire + Ice | Cold Fire / "Coldfire" | | [Steam guide](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916), [PixelNitro](https://pixelnitro.com/?p=4815) |
| Fire + Dark | Hellfire | | [wiki.gg](https://thespellbrigade.wiki.gg/wiki/Infusions) |
| Lightning + Dark | Shadowbolt / Blackbolt (conflict) | | [wiki.gg](https://thespellbrigade.wiki.gg/wiki/Infusions), [shapes.inc](https://shapes.inc/fandom/the-spell-brigade/spells-and-elements) |
| Ice + Dark | Wither (wiki) / Soulfrost | | [wiki.gg](https://thespellbrigade.wiki.gg/wiki/Infusions), [Guidexon](https://guidexon.com/the-spell-brigade-tier-list/) |
| Acid + Dark | Blight | | [Steam guide](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916) |
| Lightning + Ice | "White Lightning" (one extract; not on the Steam guide list) | | unverified |

- A Steam guide notes that "some infusion names changed in a patch". That explains the naming conflicts — [Steam guide [1.0]](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916)

#### 2d. Scrolls (formerly Relics)

Pool facts:
- Before Patch 9 there were 20 Scrolls: 13 locked behind Quests, 5 unlocked by default, and 5 exclusive to co-op — [wiki.gg Scrolls](https://thespellbrigade.wiki.gg/wiki/Scrolls)
- 1.0 Patch 9 (1 Jul 2026) added 7, removed 3, reworked Fist of Support and Power of Friendship, and added a Scroll HUD showing cooldowns and stacks. It also added 4 new Quests to unlock the new scrolls — [thespellbrigade.wiki changelog](https://thespellbrigade.wiki/changelog/); [thespellbrigade.wiki scrolls](https://thespellbrigade.wiki/scrolls/)
- Scroll quests unlock extra Scroll Chests: "Collect 3 scrolls" unlocks a second chest and "Collect 8 scrolls" a third — [wiki.gg Quests](https://thespellbrigade.wiki.gg/wiki/Quests)
- Rerolls also work on Scroll choices — [wiki.gg Enchantments](https://thespellbrigade.wiki.gg/wiki/Enchantments)

| Scroll | Effect | Unlock | Version / notes | Source |
|---|---|---|---|---|
| Blood Speed | More Move Speed the lower your Health, up to 21% | Default | Reworked in EA U9 | [wiki.gg Scrolls](https://thespellbrigade.wiki.gg/wiki/Scrolls); [EA U9](https://steamcommunity.com/games/2904000/announcements/detail/528717787215955183) |
| Humble Refinement | +1% Critical Damage every time you *encounter* a Common Improvement | Defeat a boss without choosing any Luck improvements | Possibly the renamed EA-U9 relic "Humble Ascension" (inference) | [wiki.gg Scrolls](https://thespellbrigade.wiki.gg/wiki/Scrolls); [Steam guide](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916) |
| Offensive Defense | +1% Damage per point of Armor; −0.25% Move Speed per point of Armor | Complete a mission with ≥80 Armor | | [wiki.gg Scrolls](https://thespellbrigade.wiki.gg/wiki/Scrolls); [Steam thread](https://steamcommunity.com/app/2904000/discussions/0/597398761189164696/) |
| Delayed Fate | +1 Luck each time you skip spending a reroll (max 10 stacks). Only offered if you have rerolls left or the Reroll Mastery. | Conflicting: save rerolls when offered only Commons 5× ([Quests](https://thespellbrigade.wiki.gg/wiki/Quests)) vs level up 20× in a row without taking damage | Condition added in Patch 9 | [wiki.gg Scrolls](https://thespellbrigade.wiki.gg/wiki/Scrolls); [Steam announcements](https://steamcommunity.com/app/2904000/announcements/) |
| Evasion Mend | Dodging restores 20% of the dodged damage | Dodge a hit that would have killed you | Reworked in EA U9 | [wiki.gg Scrolls](https://thespellbrigade.wiki.gg/wiki/Scrolls); [wiki.gg Quests](https://thespellbrigade.wiki.gg/wiki/Quests) |
| Fist of Support | Current (Patch 9 rework): each teammate revive gives +10% Damage and +30% Critical Damage, stacking. EA U9 version: +10% Damage per teammate revived. | Kill 50 enemies while reviving a fellow wizard | Co-op oriented | [thespellbrigade.wiki scrolls](https://thespellbrigade.wiki/scrolls/); [sihmar U9 notes](https://sihmar.com/the-spell-brigade-version-0-9-0-3352-patch-notes-april-16-2025/) |
| Power of Friendship | More Armor the closer teammates are (max 20 per teammate) | ? | Patch 9: changed from Damage to Armor, max easier to reach. A guide says stay within ~15 units. | [wiki.gg Scrolls](https://thespellbrigade.wiki.gg/wiki/Scrolls); [thespellbrigade.wiki scrolls](https://thespellbrigade.wiki/scrolls/) |
| Attunement | +20% Cast Speed while standing still | Stand still for 900 s total | Added EA U9 | [wiki.gg Relics/Scrolls](https://thespellbrigade.wiki.gg/wiki/Relics) |
| Vital Strike | Heal for 0.3% of critical damage dealt (an older version said 0.5%) | Return to full HP after dropping below 10% | Added EA U9; numbers from forum | [Steam scroll discussion](https://steamcommunity.com/app/2904000/discussions/0/838375062933484060/) |
| Elixir Permanence | +40 Max Health each time you grab a Health Potion | ? | Added EA U9 | [wiki.gg Relics/Scrolls](https://thespellbrigade.wiki.gg/wiki/Relics) |
| Mana Siphon | Each Mana orb picked up has a 15% chance to trigger … (wiki text truncated) | Level up three times within 2 s | Added EA U9 | [wiki.gg Relics/Scrolls](https://thespellbrigade.wiki.gg/wiki/Relics) |
| Hard Lessons | Mana Gain rises as Health falls (max 40%), per the wiki. The EA U9 notes said XP Gain, max 30%. | ? | Reworked EA U9 | [wiki.gg Relics/Scrolls](https://thespellbrigade.wiki.gg/wiki/Relics); [sihmar U9](https://sihmar.com/the-spell-brigade-version-0-9-0-3352-patch-notes-april-16-2025/) |
| Go-Getter's Grace | Wiki: +30% healing per completed Objective (a forum quote says 25%). EA U9 notes: +50% Revive Speed per Objective completed. | ? | Reworked EA U9; current effect unclear | [wiki.gg Relics/Scrolls](https://thespellbrigade.wiki.gg/wiki/Relics); [sihmar U9](https://sihmar.com/the-spell-brigade-version-0-9-0-3352-patch-notes-april-16-2025/) |
| Bountiful Quests | Name only, effect not captured | ? | EA-era relic | [Steam thread "New Relics, What They Do"](https://steamcommunity.com/app/2904000/discussions/0/4842023128332339717/) |
| Second Breath | +1 stack per second standing still, −1 per second moving, max 5; +6% Move Speed per stack | Quest | New in 1.0 Patch 9 | [thespellbrigade.wiki scrolls](https://thespellbrigade.wiki/scrolls/) |
| Lucky Scroll | Grants a random scroll and adds an extra Scroll Chest to the map | Quest; hard to find solo, Endless suggested | New in Patch 9 | [Steam announcements](https://steamcommunity.com/app/2904000/announcements/); [Steam thread](https://steamcommunity.com/app/2904000/discussions/0/565913205989390394/) |
| Magician Collision | **Co-op only.** Colliding with a teammate gives both wizards +25% Move Speed for 5 s (10 s cooldown). | ? | New in Patch 9; fan tier B | [wiki.gg Scrolls](https://thespellbrigade.wiki.gg/wiki/Scrolls); [thespellbrigade.wiki scrolls](https://thespellbrigade.wiki/scrolls/) |
| Passive Income | Luck capped at 0, but every 5th Level Up contains a guaranteed Legendary | ? | New in Patch 9; fan tier A | [thespellbrigade.wiki scrolls](https://thespellbrigade.wiki/scrolls/) |
| Fight or Flight | Taking damage gives +30% Move Speed for 2 s (7 s cooldown) | ? | New in Patch 9; fan tier B | [thespellbrigade.wiki scrolls](https://thespellbrigade.wiki/scrolls/) |
| Thick Skin | Armor scales inversely with Health, max 90 | ? | New in Patch 9 | [wiki.gg Scrolls](https://thespellbrigade.wiki.gg/wiki/Scrolls) |
| Drinking Buddies | **Co-op.** When you drink a Health Potion, teammates get 50% of the healing, and vice versa. | ? | New in Patch 9 | [wiki.gg Scrolls](https://thespellbrigade.wiki.gg/wiki/Scrolls); [thespellbrigade.wiki scrolls](https://thespellbrigade.wiki/scrolls/) |
| ~~Savior Focus~~ | +25% Critical Damage per teammate revived | Complete a mission with ≥201% Crit Damage | **Removed in 1.0 Patch 9** | [Steam announcements](https://steamcommunity.com/app/2904000/announcements/); [thespellbrigade.wiki changelog](https://thespellbrigade.wiki/changelog/) |
| ~~Steady Hand~~ | +100% Critical Damage while standing still | Kill 433 enemies while standing still | **Removed in 1.0 Patch 9** | [wiki.gg Quests](https://thespellbrigade.wiki.gg/wiki/Quests); [Steam scroll discussion](https://steamcommunity.com/app/2904000/discussions/0/838375062933484060/) |
| ~~Resilient Revival~~ | Revive-based bonus; exact numbers not isolated | Revive 10 fellow wizards | **Removed in 1.0 Patch 9** | [wiki.gg Quests](https://thespellbrigade.wiki.gg/wiki/Quests) |

- The official reason for the Patch 9 removals: Savior Focus, Steady Hand and Resilient Revival "were removed as they could not reach parity with other scrolls" — [Steam announcements](https://steamcommunity.com/app/2904000/announcements/) via search extract
- EA Update 9 added five relics: Attunement, Vital Strike, Elixir Permanence, Mana Siphon and Humble Ascension. It reworked Blood Speed, Hard Lessons, Go-Getter's Grace, Evasion Mend, Fist of Support, Savior Focus and others — [Steam EA Update 9](https://steamcommunity.com/games/2904000/announcements/detail/528717787215955183); [sihmar](https://sihmar.com/the-spell-brigade-version-0-9-0-3352-patch-notes-april-16-2025/)
- Achievements tied to scrolls: "Scroll Enthusiast" (collect 3 scrolls) and "Scroll Hunter" (collect 12 different scrolls) — [GameFAQs PS5 achievements](https://gamefaqs.gamespot.com/ps5/638324-the-spell-brigade/achievements)

#### 2e. Enchantments + Masteries (meta, bought with gold; they set in-run baselines)
Sources: [wiki.gg Enchantments](https://thespellbrigade.wiki.gg/wiki/Enchantments) (about 288 days old); [Steam guide "All Enchantments / Masteries"](https://steamcommunity.com/sharedfiles/filedetails/?id=3726023191) (about 150 days old, ~1.0)

| Enchantment | Levels 1→5 | Mastery effect | Notes |
|---|---|---|---|
| Damage | +7% … +25% spell damage | +10% damage vs enemies above 70% Health | Base price 100 |
| Regeneration | +3/6/9/12/15 | Regain some Health on Level Up | |
| Revive | +10/10/20/30/30% healing on revive; +0/1/1/1/2 Revive Cores | More Health the sooner you revive a teammate | |
| Spell Size | +4/8/12/16/20% | 10% chance to cast your spell at 160% size | |
| Luck | +4/6/8/10/12 | First Level Up offers only Improvements of increased Rarity | |
| Dodge | +4/8/12/16/20% | Dodged damage is reflected to its source | |
| Armor | +20/40/60/80/100 | Invulnerable for 4 s after taking damage | |
| Mana Gain | +3% … +15% | Gain mana when you revive a teammate | |
| Mana Pull | ? | Take less damage while using a Mana Magnet | |
| Reroll | +1/2/3/4/5 rerolls | Spend Health to reroll when out of rerolls | Base price shown as 250 (garbled table) |
| Banish | +1 … +5 | Banishing an Improvement immediately offers a new one | |
| Lock | +1/2/3/4/5 locks | A locked Improvement gains Rarity at the next Level Up | Price 300 shown |
| Revive Speed | ? | Revive Cores recharge faster when you take damage | |
| Max Health | ? | Gain empty max Health each time you revive a teammate | |
| Critical Damage | ? | Crit damage rises slightly with each attack and resets on a crit | |
| Critical Chance | ? | Attacks instantly kill non-boss monsters below 10% Health | |
| Revive Circle | ? | Standing in a Revive Circle slowly heals you | |
| Move Speed | ? | Your Resurrection Beam moves faster | |
| Spell Cooldown ("Haste") | ? | ? | Named only in [2UpSkill tier list](https://2upskill.com/the-spell-brigade-enchantment-tier-list-2026-best-permanent-upgrades-guide/) |

- Unlocking every enchantment including its mastery costs 124,287 gold in total — [wiki.gg Enchantments](https://thespellbrigade.wiki.gg/wiki/Enchantments)

#### 2f. Covenants / Trial Covenants (pre-run modifiers that change in-run offers)
- Covenants — [wiki.gg Covenants](https://thespellbrigade.wiki.gg/wiki/Covenants)
  - **Harmony**: friendly fire off
  - **Eternity**: endless mission
  - **Abstinence** (formerly "Solitary Focus"): "You can use one Spell less", more per stack
- Trial Covenants (v1.0) — [wiki.gg Covenants](https://thespellbrigade.wiki.gg/wiki/Covenants); [NineWiki](https://ninewiki.com/guide/the-spell-brigade-how-to-get-trial-covenants/); [Whisper of the House](https://www.whisperofthehouse.com/the-spell-brigade/trial-covenants-masteries-prestige); [Steam guide (marked Outdated)](https://steamcommunity.com/sharedfiles/filedetails/?id=3719250290)
  - **Denial**: one Improvement less per stack, up to 2 stacks. Unlock: ascend Wizard King and Star Mage twice.
  - **Discipline**: take damage on every level up, about 20 HP. Unlock: ascend Kavin and Campanelli twice, and beat Astral Rifts on hardcore at ≥9 Devotion.
  - **Onslaught**: 1/2/4 Devotion by stack
  - **Mana Drought**: enemies drop less mana. Unlock: ascend Ludwig and Balthazar twice, and beat Verdant Meadows on hardcore at ≥3 Devotion.
  - **Purity**: activated enchantments are disabled. Unlock: beat Pyrestorm Pit on hardcore at ≥7 Devotion.
  - **Mortality**: monsters kill you in one hit (environmental damage excluded). Unlock: ascend Moon Mage twice.
  - **Torment**: you heal less. Unlock: ascend Aldric and Bryony twice, and beat Frozen Ancients on hardcore at ≥5 Devotion.
- As of patch 1.0.5.17363 you no longer have to ascend specific wizards. Ascending any wizard unlocks trial covenants in order — [Steam guide](https://steamcommunity.com/sharedfiles/filedetails/?id=3719250290)
- Each Devotion level gives +10% wizard XP (player claim) — [Steam thread "What is Devotion?"](https://steamcommunity.com/app/2904000/discussions/0/561406856399993277/)

### Inferences
- Scroll count now ≈ 20 − 3 + 7 = 24. I captured 21 current names. About 3 current scrolls, probably default or co-op ones, are still unnamed.
- "Humble Ascension" (EA U9) and "Humble Refinement" (current) are probably the same scroll renamed. Both are crit-damage scalers: a YouTube title credits Humble Ascension with 554% crit damage. This is unconfirmed.
- Enchantment Mastery effects show up as in-run mechanics (Lock rarity bump, Banish refresh, Reroll for Health, 160%-size casts, 10% execute). The planner should model them as toggles on top of the in-run upgrades.

### Gaps
- The Wizard's Edge middle tiers, and the Damage, Mana Gain and Spell Cooldown enchantment values per level, weren't fully captured.
- The rarity-tier mapping of the Range spell upgrade (0/16/27/38) is unclear.
- Missing: unlock conditions for Power of Friendship, Elixir Permanence, Hard Lessons, Go-Getter's Grace and the 7 Patch-9 scrolls; Bountiful Quests' effect; the end of Mana Siphon's effect; the 5 default and 5 co-op-exclusive scroll names after Patch 9.
- I found no 1.1/1.2 notes changing Character Upgrade, Scroll or Enchantment numbers. Possible silent changes can't be ruled out.

## 3. All stats and how they are calculated

### Takeaway
The stats visible in upgrades are:
- Max Health, Armor, Dodge, Health Regeneration, Move Speed
- Base Damage and Spell Damage, Critical Chance, Critical Damage
- Cast Speed and Cooldown, Spell Size, Spell Range, Duration
- Mana Gain (XP gain), Mana Pull (pickup radius), Luck
- Revive stats: Revive Speed, Revive Cores, revive healing

Four stats have soft caps, after which their upgrades stop appearing: Luck, Dodge, Critical Chance and Mana Gain. Locking can push past them to hard maximums. Size scales by surface area. Additive vs multiplicative stacking isn't officially documented.

### Cited Findings
- The wiki states "there are currently 4 stats with soft caps after which related upgrades will not appear" — [wiki.gg Upgrades](https://thespellbrigade.wiki.gg/wiki/Upgrades)

| Stat | Soft cap (wiki) | Highest possible (wiki) | Player-reported |
|---|---|---|---|
| Luck | 25 | 50 | Soft 24, max 42 without tricks; 50 by taking the luck scroll after reaching 40 ([Steam caps thread](https://steamcommunity.com/app/2904000/discussions/0/573792389465141072/)) |
| Dodge | 75% | 98% | One thread: 87% max; another: "painful to reach 105% dodge" ([caps thread](https://steamcommunity.com/app/2904000/discussions/0/573792389465141072/)) |
| Critical Chance | 80% | 103% | One thread: 92% max ([caps thread](https://steamcommunity.com/app/2904000/discussions/0/573792389465141072/)) |
| Mana Gain | 200% | 241% | Hard caps "with maxed Lock enchantment are: Luck 50 Dodge 98% Crit 103% Mana Gain 241%" ([caps thread](https://steamcommunity.com/app/2904000/discussions/0/573792389465141072/)) |

- How to get past the soft caps: reach 24 Luck, then lock in an Epic or Legendary after completing an objective. "This method doesn't just work with Mana Gain and Luck but also Critical Chance and Dodge" — [wiki.gg Upgrades](https://thespellbrigade.wiki.gg/wiki/Upgrades); [Steam caps thread](https://steamcommunity.com/app/2904000/discussions/0/573792389465141072/)
- A developer said the soft cap reduces "the chance of receiving a dodge upgrade" once you pass a certain percentage, i.e. a weighting change rather than a hard block — [Steam caps thread](https://steamcommunity.com/app/2904000/discussions/0/573792389465141072/); [Steam "Dodge cap?"](https://steamcommunity.com/app/2904000/discussions/0/4697908845438737713/)
- **Spell Size** upgrades are "based on the surface area of the spell, instead of diameter or length" (developer, late 2024). Players reported the effect as small or confusing — [Steam discussion](https://steamcommunity.com/app/2904000/discussions/0/4633734370401767717)
- **Armor**:
  - One search extract says Update 8 (Mar 2025) made armor "a percentual damage reduction instead of a flat value" and removed the soft cap. A second extract of the same notes found only Ludwig's +12 Armor. Unresolved — [SteamDB Update 8](https://steamdb.info/patchnotes/17603290/)
  - Pre-2025 players described armor as flat "direct mitigation, no formula" — [Steam "Armour?"](https://steamcommunity.com/app/2904000/discussions/0/686368182958705278/); [Steam "random thoughts"](https://steamcommunity.com/app/2904000/discussions/0/595143167557295002/)
  - Thick Skin (max 90 Armor) and Offensive Defense (+1% damage per Armor) both treat Armor as an open-ended number — [wiki.gg Scrolls](https://thespellbrigade.wiki.gg/wiki/Scrolls)
- **Damage stacking**:
  - A player says damage, rate of fire and crit "add multiplicatively with each other": +100% in each gives about +700% DPS — [Steam "Game balance"](https://steamcommunity.com/app/2904000/discussions/0/838375696283811039/)
  - Base Damage (Titan's Fury) "applies to your character so it applies to all your spells". Whether it adds to or multiplies Spell Damage is untested — [Steam "Base Damage?"](https://steamcommunity.com/app/2904000/discussions/0/655981814410734550/)
- **Crit**: Afterburn and Sparks scale off hit damage including crit, so crit stats feed elemental damage — [Steam infusion guide](https://steamcommunity.com/sharedfiles/filedetails/?id=3729529643)
- **Slow** stacks additively and caps at 72% — [Steam infusion guide](https://steamcommunity.com/sharedfiles/filedetails/?id=3729529643)
- **Mana Gain** in co-op scales the XP value of orbs *you* pick up for the shared bar. At 200% an orb gives 20; at 100% it gives 10 — [Steam "XP Increase in multiplayer"](https://steamcommunity.com/app/2904000/discussions/0/4629231591254675054/)
- Example base spell stats are listed in 2b (Damage 140, Cast Speed 0.44/s, Size 0.98, Range 9) — [wiki.gg Magic Missile](https://thespellbrigade.wiki.gg/wiki/Magic_Missile)
- The upgrade wording uses both "Base Damage" (Titan's Fury) and "Spell Damage" (per-spell upgrades, Damage enchantment), and both "Base Cast Speed" (Veil of Haste) and "Cooldown" (per-spell upgrades). These are separate stat channels — [wiki.gg Upgrades](https://thespellbrigade.wiki.gg/wiki/Upgrades)

### Inferences
- Practical planner model: global "Base" multipliers (Titan's Fury, Veil of Haste, Colossal Grace) × per-spell multipliers (Spell Damage, Cooldown, Size), with crit layered on top. This matches the player's multiplicative claim, but treat it as a hypothesis.
- Luck, Dodge, Crit Chance and Mana Gain need cap logic: upgrades stop being offered at the soft cap, and Locks allow overshoot up to the hard maximum.

### Gaps
- No official armor formula. Whether armor is a % reduction now is unconfirmed.
- No confirmed additive/multiplicative rules, and no caps on move speed, cast speed or cooldown.
- No stat screen list from an official source.

## 4. Rarity tiers, how offers are generated, and rerolls, banishes, locks, skips and luck

### Takeaway
There are four rarities: Common, Rare, Epic, Legendary. Base offer odds are 71/25/4/0%. Each Luck point shifts about 1.2 points from Common towards higher tiers. Three tools change offers:
- **Reroll**: also works on Scrolls and Objectives
- **Banish**: removes an Improvement for the rest of the mission
- **Lock**: keeps an Improvement for the next level up and raises its rarity

Earlier picks reportedly weight later offers.

### Cited Findings
- Base odds: 71% Common, 25% Rare, 4% Epic, 0% Legendary. Per +1 Luck: −1.2% Common, +0.5% Rare, +0.4% Epic, +0.3% Legendary. At 42 Luck: 20.6% / 46.0% / 20.8% / 12.6% — [wiki.gg Enchantments](https://thespellbrigade.wiki.gg/wiki/Enchantments)
- Every Character Upgrade has a value per tier (Common/Rare/Epic/Legendary). Some lack a tier: Colossal Grace has no Common, Quickstep Surge no Legendary — [wiki.gg Upgrades](https://thespellbrigade.wiki.gg/wiki/Upgrades)
- **Reroll**: Reroll enchantment +1…+5. Rerolls also apply to Scrolls and Objectives. The Reroll Mastery lets you pay Health for more rerolls — [wiki.gg Enchantments](https://thespellbrigade.wiki.gg/wiki/Enchantments)
- **Banish**: "specific Improvements will not be offered anymore for the remainder of the Mission". +1…+5 via the enchantment. The Mastery immediately offers a replacement — [wiki.gg Enchantments](https://thespellbrigade.wiki.gg/wiki/Enchantments); [Steam Masteries guide](https://steamcommunity.com/sharedfiles/filedetails/?id=3726023191)
- **Lock**: "Lock specific Improvements, so they will stay in place until the next Level Up". With the Mastery, "Locking an Improvement will increase its Rarity the next Level Up". +1…+5 locks — [wiki.gg Enchantments](https://thespellbrigade.wiki.gg/wiki/Enchantments)
- Players use spare Locks around objective rewards to get a second Legendary and break the soft caps — [Steam caps thread](https://steamcommunity.com/app/2904000/discussions/0/573792389465141072/)
- **Pool weighting**: "The upgrades you choose will influence the upgrades you are offered in the future". Example: taking a Moonerang upgrade makes more Moonerang buffs likelier — search extract of [Steam discussion](https://steamcommunity.com/app/2904000/discussions/0/4633734370401767717) / [Whisper of the House](https://www.whisperofthehouse.com/the-spell-brigade/trial-covenants-masteries-prestige) (exact attribution uncertain)
- **Denial** cuts the number of offered Improvements by one per stack — [wiki.gg Covenants](https://thespellbrigade.wiki.gg/wiki/Covenants)
- **Passive Income** sets Luck to 0 but guarantees a Legendary every 5th level up — [thespellbrigade.wiki scrolls](https://thespellbrigade.wiki/scrolls/)
- **Delayed Fate** rewards *not* rerolling with +1 Luck (max 10) — [wiki.gg Scrolls](https://thespellbrigade.wiki.gg/wiki/Scrolls)
- **Humble Refinement** gives +1% crit damage for every Common Improvement *encountered*, so being offered Commons is rewarded — [wiki.gg Scrolls](https://thespellbrigade.wiki.gg/wiki/Scrolls)
- With the Luck Mastery, the first Level Up offers only higher-rarity Improvements — [Steam Masteries guide](https://steamcommunity.com/sharedfiles/filedetails/?id=3726023191)
- A player argues rarity matters more than upgrade type. An Epic Size or Damage pick can beat a Legendary XP pick — [Steam "Experience Power Ups in multiplayer?"](https://steamcommunity.com/app/2904000/discussions/0/595134572710111089/)
- Luck "significantly improves upgrade quality early in the run". Banish needs to be unlocked first (via the enchantment) — [Whisper of the House](https://www.whisperofthehouse.com/the-spell-brigade/trial-covenants-masteries-prestige)
- A Steam tech-support thread reports a banishing bug, details not captured — [Steam "Banishing Bug"](https://steamcommunity.com/app/2904000/discussions/2/834999160768884158/)
- 1.2.0.20127 fixed "killing the boss too fast in Endless Mode could break Level Ups" — [Steam community hub](https://steamcommunity.com/app/2904000)
- Mana (XP) orbs are rarity-coloured. One wiki extract gives "Tiny 'common': 7, (0.3)" up to a big legendary orb worth 21; the meaning of the numbers is unclear — [wiki.gg Objectives](https://thespellbrigade.wiki.gg/wiki/Objectives) (low confidence)

### Inferences
- Odds formula for the planner: P(tier) = base + Luck × delta, using base (71, 25, 4, 0) and delta (−1.2, +0.5, +0.4, +0.3) per Luck point. This is valid up to at least 42 Luck. Behaviour from 43 to 50 Luck is unknown (Common would go negative past ~59).
- No "skip" button was found. Delayed Fate's "skip spending a reroll" suggests declining a reroll is tracked, but there's no evidence of skipping a level-up outright.

### Gaps
- Base number of rerolls, banishes and locks with zero enchantments.
- Number of choices per level up (probably 3, minus Denial stacks), and whether objective rewards use a different rarity table.
- The exact weighting algorithm for "previous picks influence offers".

## 5. Shop, merchant or gold economy inside a run

### Takeaway
I found no in-run shop or merchant. Gold is paid out at the end of a mission, based mostly on level and completed objectives, and spent in the lobby on Enchantments, which are refundable. The in-run "economy" is mana orbs (XP), Health Potions, Mana Magnets, Revive Cores, Scroll Chests and augment chests. 1.0 added thief enemies that steal resources.

### Cited Findings
- One guide says no gold is earned during a run at all: no drops, no pickups. Another lists the payout sources as objectives, enemy kills, run completion, Bounty, contracts, and small extras like Greed and breakables — [TheGamer gold guide](https://www.thegamer.com/the-spell-brigade-how-to-farm-gold-fast/); [Whisper of the House gold farm](https://www.whisperofthehouse.com/the-spell-brigade/gold-farm)
- A player's formula (unofficial): Gold = (9 × Level) + (23 × Completed Objectives) — [Steam "how does the gold reward work"](https://steamcommunity.com/app/2904000/discussions/0/725769023703235370/)
- **Bounty** doubles objective gold. A normal clear gives about 500–550 gold; a Bounty-focused run about 800–850 — [Whisper of the House gold farm](https://www.whisperofthehouse.com/the-spell-brigade/gold-farm)
- Conflict: a 2026 guide says destructibles now drop noticeable gold — [2UpSkill gold guide](https://2upskill.com/the-spell-brigade-gold-farming-guide-2026-best-spots-and-fast-money-methods/)
- Trial Covenants raise gold and wizard XP gain — [wiki.gg Covenants](https://thespellbrigade.wiki.gg/wiki/Covenants)
- Enchantments are bought for gold in the lobby. The full set costs 124,287 gold and refunds are free — [wiki.gg Enchantments](https://thespellbrigade.wiki.gg/wiki/Enchantments)
- 1.0 added "resource-stealing thieves" and elite variants that act as mini-bosses — [Gematsu](https://www.gematsu.com/2026/03/co-op-bullet-heaven-roguelite-game-the-spell-brigade-launches-april-29-for-ps5-pc)
- Objectives, per the Steam guide [1.0]: Bewitching Fungi, Crush the Statues (8 statues per wizard), Hunt Down the Golden Crab, Sacrifice (kill enemies inside a circle), Seal the Rift (stand in it; it degrades when empty), Soul Sludge, Unstable Spell Cores — [Steam guide [1.0]](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916); [wiki.gg Objectives](https://thespellbrigade.wiki.gg/wiki/Objectives)
- Objective unlock milestones: 5 objectives completed unlocks Sacrifice; 12 unlocks Spell Core; 25 unlocks Brazier — [Steam guide [1.0]](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916)
- 1.1 objective variants: Rifts can split into several smaller ones; Sacrifice can be a damaging Death Shrine; there are new Golden Crab and Statue variants — [Steam 1.1 news](https://store.steampowered.com/news/app/2904000/view/715662120170030645); [Rogueliker 1.1](https://rogueliker.com/the-spell-brigade-realm-sweep/)
- Reginald has increased Health Potion drops — [Whisper of the House achievements](https://www.whisperofthehouse.com/the-spell-brigade/achievements-guide)

### Inferences
- The planner doesn't need an in-run shop model. It needs an "objective reward → augment/Improvement" event and "scroll chest (1-of-3)" events, with up to 3 chests per mission depending on quest unlocks.

### Gaps
- What thieves steal (mana orbs? potions?) and how it affects builds.
- Whether breakables drop gold in the current version.
- The official gold formula.

## 6. Team/co-op shared upgrades and upgrades that buff allies

### Takeaway
Co-op uses one shared XP/level bar; each collector's Mana Gain scales their pickups. Revive tools are central:
- Revive Cores, Revive Circle, Resurrection Beam, and a ghost state that can still collect XP
- A cluster of co-op-only or revive-scaling scrolls and masteries: Fist of Support, Power of Friendship, Magician Collision, Drinking Buddies, plus the Revive, Max Health and Mana Gain masteries

Builds can be coordinated across players, e.g. an all-Dark team.

### Cited Findings
- **Shared XP pool**: orbs go to a shared team XP bar, but their value depends on the collector's XP gain — [Console Creatures review](https://www.consolecreatures.com/the-spell-brigade-review/); [Steam "XP Increase in multiplayer"](https://steamcommunity.com/app/2904000/discussions/0/4629231591254675054/)
- **Ghost state** (1.0-era rework): dead players become ghosts who wander and still collect XP orbs — search extract citing 1.0 patch notes; [Steam store](https://store.steampowered.com/app/2904000/The_Spell_Brigade/)
- **Revive Cores** in co-op: one player's Core can pull back a downed teammate, at the cost of the Core. A guide advises having one player hold spare Cores — [GameBrief tips](https://www.gamebrief.net/blog/the-spell-brigade-tips-guide-2026)
- The Revive enchantment adds Revive Cores (+0/1/1/1/2) and revive healing — [Steam Masteries guide](https://steamcommunity.com/sharedfiles/filedetails/?id=3726023191)
- Revive-themed Masteries — [Steam Masteries guide](https://steamcommunity.com/sharedfiles/filedetails/?id=3726023191):
  - Max Health: gain empty max HP per teammate revive
  - Mana Gain: gain mana per revive
  - Revive Circle: standing in it heals you
  - Move Speed: faster Resurrection Beam
  - Revive Speed: Cores recharge when you take damage
- **Co-op scrolls**:
  - Magician Collision: both wizards get +25% Move Speed for 5 s on collision — [wiki.gg Scrolls](https://thespellbrigade.wiki.gg/wiki/Scrolls)
  - Drinking Buddies: 50% potion healing shared both ways — [wiki.gg Scrolls](https://thespellbrigade.wiki.gg/wiki/Scrolls)
  - Power of Friendship: Armor by proximity, max 20 per teammate — [thespellbrigade.wiki scrolls](https://thespellbrigade.wiki/scrolls/)
  - Fist of Support: +10% Damage and +30% Crit Damage per revive — [thespellbrigade.wiki scrolls](https://thespellbrigade.wiki/scrolls/)
  - Before Patch 9, 5 of the 20 scrolls were "exclusive to co-op mode" — [wiki.gg Scrolls](https://thespellbrigade.wiki.gg/wiki/Scrolls)
- **Friendly fire and negative effects**:
  - The Harmony covenant turns friendly fire off — [wiki.gg Covenants](https://thespellbrigade.wiki.gg/wiki/Covenants)
  - 1.1 "Reworked Ice and Dark Healing Spells so their negative effects no longer apply to teammates" — [Steam 1.1 news](https://store.steampowered.com/news/app/2904000/view/715662120170030645)
- Objective scaling: Crush the Statues requires 8 statues *per wizard* — [Steam guide [1.0]](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916)
- Team builds — [thespellbrigade.wiki builds](https://thespellbrigade.wiki/builds/); [thespellbrigade.wiki elements](https://thespellbrigade.wiki/spells/elements/):
  - "Full Dark Corruption", S-tier, 4-player co-op only: all four players infuse Dark
  - Void (Dark+Dark) reportedly needs the whole team on Dark (unverified)
  - "Moonerang Acid" (Campanelli) is described as the co-op anchor
- Campanelli is described as having the best revive speed — [thespellbrigade.wiki achievements](https://thespellbrigade.wiki/achievements/)

### Inferences
- The planner should support a "team" view: element mix (Dark stacking; Acid's +10% damage taken helps everyone hitting the target), revive-scroll value that scales with expected revives, and a toggle for co-op-only scrolls in the pool.

### Gaps
- Whether Character Upgrades are chosen per player (individual offers on a shared level) or shared.
- Names of all current co-op-exclusive scrolls.
- How Acid/Corrosion debuffs interact with allies' damage numbers.

## 7. Community builds, tier lists, meta strategies, and broken or nerfed combos

### Takeaway
The 1.0-era community consensus:
- The **Star Mage "Falling Stars + Lightning"** one-spell build to spell level 20 has the highest ceiling. Priority: Luck → Cooldown Reduction → Damage/Crit.
- The **Sun Mage "Solar Pulse Aura"** is the easiest and safest.
- **Reginald Acid Astral Orbs** is the boss killer.
- An all-Dark team ("Full Dark Corruption") is the 4-player S-tier pick.
- Lightning is the top general element; Acid and Wildfire come next.
- Luck, Armor, Mana Gain and Cooldown are the most valued stats.
- Offensive Defense and Humble Refinement are considered the strongest scrolls.

The main recorded "removals" were three underperforming revive/crit scrolls in 1.0 Patch 9. I found no explicit combo nerfs in the official notes.

### Cited Findings

#### Builds
- **Falling Stars Lightning (Star Mage)**: the community's consensus best build. Stack Falling Stars to Spell Level 20 with the Lightning infusion around level 7. Stat priority: Luck → Cooldown Reduction → Damage — [thespellbrigade.wiki builds](https://thespellbrigade.wiki/builds/); [thespellbrigade.wiki Star Mage](https://thespellbrigade.wiki/wizards/star-mage/). An alternative order: Luck → Cooldown Reduction → Spell Level → Critical Damage — [Whisper of the House best builds](https://www.whisperofthehouse.com/the-spell-brigade/best-builds)
- Plasma on Falling Stars makes "one of the strongest boss-killing spells" — search extract via [thespellbrigade.wiki Star Mage](https://thespellbrigade.wiki/wizards/star-mage/)
- **Acid Astral Orbs (Reginald)**: the boss killer. Luck upgrades first, Acid at level 7 — [thespellbrigade.wiki builds](https://thespellbrigade.wiki/builds/)
- **Moonerang Acid (Campanelli)**: co-op anchor, Acid at level 7 — [thespellbrigade.wiki builds](https://thespellbrigade.wiki/builds/)
- **Full Dark Corruption**: S-tier, 4-player co-op only — [thespellbrigade.wiki builds](https://thespellbrigade.wiki/builds/)
- **Solar Pulse Aura (Sun Mage)**: easiest to reproduce and the safest solo, farming and long-loop route. One-spell routing with spell size, cast speed, Lightning / Plasma / Wildfire, crit sustain and movement. Sun Mage's dodge and smaller hitbox make close-range aura play safer — [Whisper of the House best builds](https://www.whisperofthehouse.com/the-spell-brigade/best-builds); [Whisper solo guide](https://www.whisperofthehouse.com/the-spell-brigade/solo-guide)
- Other Whisper builds: **Acid Multi-Hit** for boss and elite shred, **Scepter Mesh Plasma** for co-op space control — [Whisper of the House best builds](https://www.whisperofthehouse.com/the-spell-brigade/best-builds)
- **High-frequency spells** (Rune Burst, Aether Beam): take Veil of Haste at Rare or higher, then stack cooldown reduction, spell damage and crit on one focused spell route — [Whisper of the House best builds](https://www.whisperofthehouse.com/the-spell-brigade/best-builds)
- **Ludwig**: one guide makes him a defensive Ice + Lightning pick, another a ghost-revive/lifesteal character. The sources conflict — search extract of [thespellbrigade.wiki](https://thespellbrigade.wiki/) / [Whisper wizard unlocks](https://www.whisperofthehouse.com/the-spell-brigade/wizard-unlocks)
- **One-spell focus**: the Abstinence covenant rewards specialisation, but per one source it limits flexibility — [PixelNitro covenants](https://pixelnitro.com/the-spell-brigade-covenants-explained-2026-guide-to-pacts-and-power-synergies/). A Steam thread discusses "How to use/upgrade only one spell" — [Steam](https://steamcommunity.com/app/2904000/discussions/0/659341126368916150/). A player says extra upgrades on an already-maxed spell are still worth taking — [Steam](https://steamcommunity.com/app/2904000/discussions/0/599640708794613803/)
- PixelNitro synergy claims, low confidence: Acid + Fire reduces enemy armor; Gravitational Well + Coldfire infusion for area damage — [PixelNitro](https://pixelnitro.com/?p=4815)

#### Tier lists
- Elements (thespellbrigade.wiki, 1.0): Lightning S ("best general element in 1.0"); Acid A; Wildfire A; Plasma B ("niche for Hatti"). Star Mage and Reginald are the S-tier wizards — [thespellbrigade.wiki tier list](https://thespellbrigade.wiki/builds/tier-list/); [thespellbrigade.wiki elements](https://thespellbrigade.wiki/spells/elements/)
- Elements (Steam guide): Plasma, Wildfire and Blackbolt are S. This conflicts with the above — [Steam guide "Spell"](https://steamcommunity.com/sharedfiles/filedetails/?id=3514756770)
- Elements (Whisper of the House): Lightning and Acid S. Plasma is strong "but not automatically better than Acid, Flux, or Corrosion" — [Whisper spells & elements](https://www.whisperofthehouse.com/the-spell-brigade/best-spells-elements)
- Guidexon: Aurora Wings and Falling Stars are S-tier spells. Plasma is the strongest all-round advanced element, but Acid often wins long boss fights — [Guidexon](https://guidexon.com/the-spell-brigade-tier-list/)
- Enchantment tiers (2UpSkill 2026): S = Luck, Armor, Mana Gain; A = Crit Chance, Crit Damage, Cooldown, Max Health; C = Health Regen, Dodge — [2UpSkill enchantment tier list](https://2upskill.com/the-spell-brigade-enchantment-tier-list-2026-best-permanent-upgrades-guide/). The same site calls Cooldown Reduction the strongest stat across builds — [2UpSkill character guide](https://2upskill.com/character-unlock-guide-for-the-spell-brigade-2026-edition/)
- Scroll tiers (post-Patch 9, fan site): Passive Income A; Magician Collision B; Fight or Flight B — [thespellbrigade.wiki scrolls](https://thespellbrigade.wiki/scrolls/)
- Scroll opinions:
  - "Humble Refinement" is called one of the best damage-scaling options, alongside "Offensive Defense" — [Steam scroll discussion](https://steamcommunity.com/app/2904000/discussions/0/838375062933484060/)
  - "Offensive Defense relic is basically must-get"; others warn its move-speed penalty "will get you killed" without compensation — [Steam thread](https://steamcommunity.com/app/2904000/discussions/0/597398761189164696/)
  - Players complain that the new Patch-9 scrolls "pollute the pool" — [Steam thread](https://steamcommunity.com/app/2904000/discussions/0/565913463540746289/)

#### Broken, nerfed and changed combos (with patch references)
- **EA era**: "Vital Strike and Humble Ascension relic is broken. Huge Crit damage 554% and life steals" (YouTube title, unverified) — [YouTube](https://www.youtube.com/watch?v=eVEM-5ww0gs)
- **1.0 Patch 9 (1 Jul 2026)**:
  - Removed Savior Focus (+25% crit damage per revive), Steady Hand (+100% crit damage while standing still) and Resilient Revival, because they "could not reach parity with other scrolls"
  - Reworked Fist of Support (now +10% Damage and +30% Crit Damage per revive)
  - Power of Friendship changed from Damage to Armor
  - Delayed Fate now only appears with rerolls available
  - Fixed split-augmentation damage on Talon Slash, Phantom Blades and Spear Barrage
  - Sources: [thespellbrigade.wiki changelog](https://thespellbrigade.wiki/changelog/); [Steam announcements](https://steamcommunity.com/app/2904000/announcements/)
- **1.0 Patch 7**: buffs to Talon Slash +20%, Spear Barrage +30%, Phantom Blades +10%, Impish Havoc +20% — [thespellbrigade.wiki changelog](https://thespellbrigade.wiki/changelog/)
- **Falling Stars**: called "currently overpowered" in an early-EA thread, but EA patch 0.10.3.4046 (June 2025) *increased* its damage — search extract via [thespellbrigade.wiki changelog](https://thespellbrigade.wiki/changelog/)
- **1.0 reworks**: Lightning (Thunder burst), Wildfire (Critical Damage crits) and Ice (full freeze instead of slow) — [thespellbrigade.wiki elements](https://thespellbrigade.wiki/spells/elements/) (fan site, not confirmed by official notes)
- **Update 13**: Dark/corruption overhaul; bosses (Sol'phish, Krog'wa) can be corrupted — [AmeriMe Media](https://www.amerimemedia.com/post/the-spell-brigade-ushers-in-spooky-season-with-update-13-new-spells-pumpkin-fits-and-frightening); [Rogueliker U13](https://rogueliker.com/the-spell-brigade-update-13/)
- **1.1 Realm Sweep**: new wizard Eugenie (Rogueliker says "Eugene") with the Seismic Slam spell; Boss, Ice and Dark reworks; Ice/Dark healing spells no longer debuff teammates — [Steam 1.1 news](https://store.steampowered.com/news/app/2904000/view/715662120170030645); [Rogueliker](https://rogueliker.com/the-spell-brigade-realm-sweep/)
- **1.2 (Oct 2026)**: only bug fixes found. A "bigger update" is planned for the end of the year — [Steam community hub](https://steamcommunity.com/app/2904000)
- **Endless mode**: players complain that "Balance, Progression, and boss Hp tweaks have ruined Endless mode" — [Steam thread](https://steamcommunity.com/app/2904000/discussions/0/597398453436331359/)
- **Unreliable sources**: XModHub build and tier pages name spells and characters that aren't in this game ("Arcane Rift", "Frost Nova", "Archmage"). Excluded — [XModHub](https://www.xmodhub.com/info/?p=27817)

### Inferences
- Recurring build template across sources:
  1. Pick one carry spell and push it to level 20+
  2. Infuse at 7 (Lightning for clearing, Acid for bosses), then pick a second infusion at 14 for the combo
  3. Take Luck early (better rarity), then Cooldown/Cast Speed, then Damage/Crit
  4. Use Lock/Reroll to raise rarity and break the caps
  5. Pick scrolls that match your defence stat (Armor → Offensive Defense/Thick Skin; Dodge → Evasion Mend) or co-op revives
- Luck is valued highly because of the rarity math (≈+0.3% Legendary per point). Passive Income is the counter-strategy.

### Gaps
- No full current (1.1/1.2) tier list. Most tier lists are 1.0-era (May–Jul 2026), and 1.1's Ice/Dark/Boss reworks may have shifted the meta.
- I couldn't fetch YouTube or Reddit build guides directly.
- No official nerf numbers for any combo after 1.0, beyond the scroll removals and reworks.
