# The Spell Brigade: Playable Wizards and Meta-Progression (state as of 2026-10-12, game version 1.2)

**Method and reliability note (read first).** Direct page fetching did not work in this session. WebFetch failed on DNS and direct HTTPS requests were refused by the egress proxy (403) for wiki.gg, steamcommunity.com, store.steampowered.com, steamdb.info and others. So **every finding below comes from search-engine result summaries/snippets of the cited pages, not from reading the full pages**. Exact numbers (quest thresholds, % bonuses, gold costs) should be re-checked against the live pages before they go into the build-planner as hard data.

Source tiers used below:
- **Primary/official:** Steam announcements and patch notes, SteamDB patch mirrors, the publisher press site (Pirate PR).
- **Good fan source:** the fan wiki at thespellbrigade.wiki.gg. Its per-wizard pages include 1.1 content (Eugenie), so they have been edited recently. Its Quests overview page is older, around 1.5 years per the search tool.
- **Lower reliability:** thespellbrigade.wiki (no ".gg"), an unofficial SEO-style "wiki" whose dates contradict official patch notes. Also generic guide sites (tposegaming, whisperofthehouse, 2upskill, guidexon) and sihmar.com patch-note mirrors.

**Version timeline (context for the "update added" column):**
- Early Access launch: 16 Sep 2024 ([Steam store](https://store.steampowered.com/app/2904000/The_Spell_Brigade/); [Pirate PR launch release](https://press.piratepr.com/gather-your-squad-and-join-the-fray-the-spell-brigade-is-out-today)).
- EA Updates 8–13: Mar–Oct 2025.
- 1.0 full release on Steam + PS5: 29 Apr 2026.
- Post-1.0 Patches 1–10: May–Jul 2026.
- 1.1 "Realm Sweep": about 2–3 Sep 2026.
- 1.2: 2–6 Oct 2026, the current version.

---

## 1. Complete list of playable wizards (name, theme, starting spell, passive, stats, role, unlock, update added)

### Takeaway
As of 1.2 there are **16 playable wizards**. That is the 15 present at 1.0 (Knelly was the 15th, added at 1.0) plus **Eugenie**, added in 1.1 "Realm Sweep" (Sep 2026). No wizard was added in 1.2. Each wizard has three things: a **signature (starting) spell** with built-in signature bonuses, a **Wizard Trait** (passive stat package, introduced in EA Update 8), and an **unlock quest**. Reginald is unlocked from the start.

### Master catalogue table

Notes on columns:
- "Signature spell bonus" means the bonus attached to the wizard's signature/starting spell, per the wiki.gg wizard pages.
- "Trait" means the Wizard Trait passive.
- "Unlock quest (wiki.gg)" comes from the wiki.gg per-wizard pages and the Quests page.
- "Alt. unlock (tposegaming)" is a conflicting list from a post-1.0 guide (see the conflicts below).
- "Gold price" is from the period when wizards could be bought with gold. This was **removed in Patch 7 (Jun 2026)** and the gold was refunded.

| # | Wizard | Added in | Signature (starting) spell + signature bonus | Wizard Trait (passive) | Unlock quest (wiki.gg) | Alt. unlock (tposegaming, post-1.0 guide) | Gold price (old gold era) |
|---|---|---|---|---|---|---|---|
| 1 | **Reginald** | EA launch (Sep 2024) | Astral Orbs: +25% Spell Size, −12% Cooldown | +2 Luck; 10% higher chance to find Health Potions & Magnets | Unlocked by default | Unlocked by default | free |
| 2 | **Sun Mage** | EA, before Update 8 (launch roster per a low-reliability source) | Solar Pulse: +33% Spell Size | +7% Dodge; +7% Move Speed on roads & environmental hazards; −25% Hitbox Size | Dodge 5 attacks | Survive a total of 30 min | n/a |
| 3 | **Moon Mage** | EA, before Update 8 | Moonerang: +25% Spell Size, +12% Range | Gets new Spells & Infusions 1 level faster; +3% XP Gain | Level up 90 times | 180 level-ups | n/a |
| 4 | **Ludwig** | EA, before Update 8 | Arcane Broadsword: +25% Spell Size, −8% Cooldown | Immune to elemental effects; larger hitbox; +12 Armor; slower movement (−10% Move Speed) | Take 18,000 damage | Equip a new spell 36 times | 850 gold |
| 5 | **Aldric** | EA, before Update 8 | Aether Beam: +8% Damage, −4% Cooldown | +60% Revive Speed; +1 Health Regeneration; +25% Heal Efficiency | Heal a total of 10,000 HP | 360 level-ups | 950 gold |
| 6 | **Wizard King** | EA, before Update 8 | Magic Missile: +20% Duration, −8% Cooldown, +8% Spell Size | +10% Critical Chance | Land 6,000 Critical hits (listed as "original outfit" quest) | 1,111 level-ups | n/a |
| 7 | **Kavin** | EA (launch roster per a low-reliability source) | Rocky Road: +33% Spell Size, +8% Damage | Gains XP when taking damage (wiki: "+0.025% XP … based on damage taken") | Deal 7,000 damage to yourself | Survive a total of 240 min | n/a |
| 8 | **Hatti** | EA, before Update 8 | Rune Burst: +20% Spell Size, +12% Duration, −8% Cooldown | +6% Damage; −300 Max Health; 15% more vulnerable to Elemental Damage ("glass cannon") | Kill 40,000 monsters while at half HP or less | 600 level-ups | n/a |
| 9 | **Campanelli** | EA (launch roster per a low-reliability source) | Phantom Blades: +25% Spell Size, −12% Cooldown | More powerful Resurrection Beam (larger size, damage, duration); +10% Move Speed | Cast 100,000 spells | Equip a new spell 86 times | n/a |
| 10 | **Star Mage** | EA, between launch and Update 8 (exact update not found) | Falling Stars: −12% Cooldown | +15% Elemental Damage | Upgrade Solar Pulse or Moonerang 300 times | Survive a total of 273 min | n/a |
| 11 | **Maggie** | **EA Update 8** (v0.8.0.2869, 5 Mar 2025), the "eleventh wizard" | Aurora Wings: −12% Cooldown | Reveals Objectives faster, plus locations of Health Potions, Magnets and Relics | Complete 20 Objectives with ≥50 s left | Equip a new spell 50 times | 1,250 gold |
| 12 | **Bryony** | **EA Update 9 "Dark Devotion"** (v0.9.0.3352, 16 Apr 2025) | Vengeful Sprout: +25% Spell Size, +12% Damage, + damage-rate bonus | +20% potion healing; magnets work better; +12% pickup distance | Collect 80,000 Mana Orbs | Survive a total of 343 min | n/a |
| 13 | **Balthazar** | **EA Update 10 "From the Dead"** (21 May 2025) | Talon Slash: +35% Spell Size, +12% Damage | Signature spell imbued with Lifesteal; can revive teammates while downed (ghost form) | Die 99 times | Equip a new spell 75 times | 1,450 gold |
| 14 | **Pipwick** | **EA Update 11 "The Bloated One"** (v0.11.0.4763, 2 Jul 2025) | Impish Havoc: +12% Spell Duration (summons autonomous imps) | Slight chance to infuse spells with a random element; +5% Crit Damage; −3% Crit Chance (wiki.gg). The patch-notes mirror says "increased Crit Chance and Damage" (conflict) | Deal 1,235,813 critical damage | Equip a new spell 75 times | 1,700 gold |
| 15 | **Knelly** | **1.0** (29 Apr 2026), the 15th wizard | Bell March: +12% Cast Speed | Deals damage back to attacker when hit; explodes on death | Make 35 spells explosive | 180 level-ups | n/a |
| 16 | **Eugenie** | **1.1 "Realm Sweep"** (v1.1.0.19533, ~2 Sep 2026) | Seismic Slam: +25% Spell Size, +10% Damage | Not confirmed (illusion-projection themed; see gaps) | Complete 8 objectives without taking damage | n/a (guide predates 1.1) | n/a |

### Ascension outfits (first ascension replaces the starting spell)

| Wizard | Ascension outfit (1st ascension) | Starting spell with that outfit |
|---|---|---|
| Reginald | Knelly's Pupil Reginald | Bell March |
| Sun Mage | Chthonic Sun Mage | Chthonic Charge |
| Moon Mage | Scepter Mage | Scepter Mesh |
| Ludwig | Crimson Count Ludwig | Talon Slash |
| Aldric | Suncrest Aldric | Solar Pulse |
| Wizard King | Wizard Prince | Spear Barrage |
| Kavin | Whirlbound Kavin | Necro Whirl |
| Hatti | Swirl Hatti | Swirl Sickle |
| Campanelli | Bomb-Tastic Campanelli | Hex Bomb |
| Star Mage | Runic Star Mage | Cardinal Runes |
| Maggie | Sproutling Maggie | Vengeful Sprout |
| Bryony | Ironclad Bryony | Arcane Broadsword |
| Balthazar | Daywalker Balthazar | Aether Beam |
| Pipwick | Songbird Pipwick | Aurora Wings |
| Knelly | Quarry Knelly | Rocky Road |
| Eugenie | (ascension outfit exists; name/spell not found) | unknown |

### Cited Findings
**Roster size and newest wizards**
- The wiki.gg Wizards page lists a 15-wizard roster: Reginald, Sun Mage, Moon Mage, Ludwig, Aldric, Wizard King, Kavin, Maggie, Hatti, Balthazar, Star Mage, Bryony, Campanelli, Pipwick, Knelly. — [The Spell Brigade Wiki: Wizards](https://thespellbrigade.wiki.gg/wiki/Wizards)
- The 1.0 release (29 Apr 2026) added "a 15th playable wizard", Knelly, with signature spell "Bell March". It also added new enemies, elite mini-boss variants, a new boss, an Ascension system and an Austin Wintory soundtrack. — [Pirate PR 1.0 press release](https://press.piratepr.com/co-op-wizard-survivors-like-the-spell-brigade-marches-onto-playstation-5-and-10-release-on-steam-on-29-april); [GAMESTIC](https://www.gamestic.nl/2026/03/31/the-spell-brigade-reaches-1-0-on-april-29-launches-on-ps5-and-pc/); [indiegame.com](https://indiegame.com/en/archives/26648)
- 1.1 "Realm Sweep" (Steam patch 1.1.0.19533, dated "02-09-26") added "New Wizard: Eugenie, including 3 new Outfits" and the new spell Seismic Slam. It also added 5 more outfits for Moon Mage, Kavin, Pipwick, Maggie and Sun Mage, rift variants, and the ability to rotate the character in the wizard/outfit menus. — [Steam announcements](https://steamcommunity.com/app/2904000/announcements/)
- Rogueliker dated its 1.1 article 3 Sep 2026 and spells the name "Eugene". It also mentions Golden Crabs, Statues and Mana Beasts. — [Rogueliker: Realm Sweep](https://rogueliker.com/the-spell-brigade-realm-sweep/)
- The developer's X account posted "PS5 & Steam 1.2 OUT NOW" (about 2 Oct). Steam lists patch 1.2.0.20127 dated "06-10-26", and the visible notes are bug fixes (Frozen Ancients geysers doing 1 damage, Broodmaw eggs, SFX slider, a Lucky Scroll ban bug). No new wizard was seen. — [X @thespellbrigade](https://x.com/thespellbrigade); [Steam announcements](https://steamcommunity.com/app/2904000/announcements/)

**When each wizard was added**
- EA Update 8 (5 Mar 2025, v0.8.0.2869) added Maggie as the eleventh wizard. Its Aurora Wings spell came in the same update, which also gave every wizard unique Wizard Traits plus starter-spell buffs. The notes give exact traits: Reginald +2 Luck & 10% higher chance of Health Potions/Magnets; Sun Mage +7% Dodge, +7% Move Speed on roads/hazards, −25% Hitbox; Moon Mage new Spells/Infusions 1 level faster, +3% XP; Kavin gains XP when taking damage; Star Mage +15% Elemental Damage; Wizard King +10% Crit Chance; Hatti +6% Damage, −300 Max HP, 15% more vulnerable to Elemental Damage. — [SteamDB Update 8 patch notes](https://steamdb.info/patchnotes/17603290/); [Steam Update 8 event](https://steamcommunity.com/app/2904000/eventcomments/595142635297997301/?l=english&ctp=7)
- A Mar 7, 2025 hotfix fixed Moon Mage's trait so it works for non-host players, not only the Team Leader (host). — [Sihmar patch notes Mar 7 2025](https://sihmar.com/the-spell-brigade-update-patch-notes-march-7-2025/)
- On Steam, players noted that Hatti was the only wizard with negative traits. The developers replied that the values came from many balancing iterations "though they're not final". — [Steam Update 8 event comments](https://steamcommunity.com/app/2904000/eventcomments/595142635297997301/?l=english&ctp=7)
- EA Update 9 "Dark Devotion" (16 Apr 2025, v0.9.0.3352) added Bryony, "potion specialist/herb enthusiast… also half plant", with signature spell Vengeful Sprout. — [Steam: EA Update 9](https://steamcommunity.com/games/2904000/announcements/detail/528717787215955183); [Sihmar 0.9.0.3352](https://sihmar.com/the-spell-brigade-version-0-9-0-3352-patch-notes-april-16-2025/)
- EA Update 10 "From the Dead" (21 May 2025) added Balthazar. He is a melee undead mage with Talon Slash who specialises in Lifesteal and can revive teammates "from beyond the grave". The update also added the outfits Nightshift Balthazar and Emperor Balthazar, plus a new revive system with Ghost Wizards. His lore says he "supposedly died over 200 years ago". — [Steam full patch notes feed](https://store.steampowered.com/news/posts/?feed=steam_community_announcements&enddate=1747835965); [wiki.gg Balthazar](https://thespellbrigade.wiki.gg/wiki/Balthazar)
- EA Update 11 "The Bloated One" (v0.11.0.4763, 2 Jul 2025) added boss Krog'wa the Bloated One and wizard Pipwick. Pipwick uses "flute magic" and a mask, and summons imps that attack on their own. The update also added the spell Impish Havoc and the outfits Dragon Tamer Pipwick and Pipwick the Tune Tinkerer. — [Steam EA Update 11 event](https://steamcommunity.com/app/2904000/eventcomments/597405077977827896/); [Sihmar 0.11.0.4763](https://sihmar.com/the-spell-brigade-update-0-11-0-4763-patch-notes-july-2-2025/)
- EA Update 12 "The Astral Riftlands" (v0.12.0.5763, 24 Sep 2025) added a realm, enemies, an objective and 4 quests, with **no new wizard**. Rogueliker counted 13 wizards at that point. That conflicts with my count of 14: 10 before Update 8, plus Maggie, Bryony, Balthazar and Pipwick. — [Steam: EA Update 12](https://store.steampowered.com/news/app/2904000/view/520850995978174568); [Rogueliker Update 12](https://rogueliker.com/the-spell-brigade-update-12/)
- EA Update 13 (Oct 2025, the "final Early Access update", spooky season) added spells and seasonal outfits, not wizards. — [Rogueliker Update 13](https://rogueliker.com/the-spell-brigade-update-13/); [Pirate PR spooky update](https://press.piratepr.com/spooky-update-hits-the-spell-brigade-co-op-wizard-survivors-like-with-10-release-on-the-horizon)
- One summary claimed the EA launch roster was only 4 wizards (Reginald, Campanelli, Sun Mage, Kavin), with Star Mage added later. The underlying source was not identifiable and is probably the low-reliability thespellbrigade.wiki changelog, so this is **unverified**. — [thespellbrigade.wiki changelog](https://thespellbrigade.wiki/changelog/)

**Signature spells, traits and unlock quests**
- Sources for the signature-spell bonuses, traits and unlock quests in the catalogue table: [Reginald](https://thespellbrigade.wiki.gg/wiki/Reginald), [Sun Mage](https://thespellbrigade.wiki.gg/wiki/Sun_Mage), [Moon Mage](https://thespellbrigade.wiki.gg/wiki/Moon_Mage), [Ludwig](https://thespellbrigade.wiki.gg/wiki/Ludwig), [Aldric](https://thespellbrigade.wiki.gg/wiki/Aldric), [Wizard King](https://thespellbrigade.wiki.gg/wiki/Wizard_King), [Kavin](https://thespellbrigade.wiki.gg/wiki/Kavin), [Maggie](https://thespellbrigade.wiki.gg/wiki/Maggie), [Hatti](https://thespellbrigade.wiki.gg/wiki/Hatti), [Balthazar](https://thespellbrigade.wiki.gg/wiki/Balthazar), [Star Mage](https://thespellbrigade.wiki.gg/wiki/Star_Mage), [Bryony](https://thespellbrigade.wiki.gg/wiki/Bryony), [Campanelli](https://thespellbrigade.wiki.gg/wiki/Campanelli), [Pipwick](https://thespellbrigade.wiki.gg/wiki/Pipwick), [Knelly](https://thespellbrigade.wiki.gg/wiki/Knelly), [Eugenie](https://thespellbrigade.wiki.gg/wiki/Eugenie), [Quests](https://thespellbrigade.wiki.gg/wiki/Quests)
- The Eugenie wiki page labels the signature spell "Bell March Seismic Slam", which looks like a wiki template error. Official 1.1 notes and Rogueliker tie Eugenie to **Seismic Slam**. Eugenie's outfits are Original (complete 8 objectives without taking damage), Dark Phase (have an Illusion attract ≥29 enemies over its lifetime), Genuine Djinn (project 333 Illusions), and an ascension outfit (ascend once). — [wiki.gg Eugenie](https://thespellbrigade.wiki.gg/wiki/Eugenie); [Rogueliker](https://rogueliker.com/the-spell-brigade-realm-sweep/)
- A Steam player described Eugenie's illusion as spawning inside the player and bumping/turning the character, and called Seismic Slam weaker than other spells and awkward on keyboard (single opinion). — [Steam discussion: Eugenie's spell](https://steamcommunity.com/app/2904000/discussions/0/588436698284762850/)
- Pipwick's outfit quests: "As Pipwick, have 8 active Imps at the same time" and "have minions of 3 different infusions at the same time". — [Sihmar 0.11.0.4763](https://sihmar.com/the-spell-brigade-update-0-11-0-4763-patch-notes-july-2-2025/); [wiki.gg Pipwick](https://thespellbrigade.wiki.gg/wiki/Pipwick)
- Ascension outfit / starting-spell pairs (table above): wiki.gg Ascension page, cross-confirmed by a Steam thread for Wizard King, Star Mage, Aldric, Maggie, Bryony, Balthazar, Pipwick and Knelly. The Bell March, Cardinal Runes and Solar Pulse spell pages list these wizards as starting-spell users "only with Ascension Outfit equipped". — [wiki.gg Ascension](https://thespellbrigade.wiki.gg/wiki/Ascension); [Steam: Ascension skin spells](https://steamcommunity.com/app/2904000/discussions/0/838375062933398814/); [Bell March](https://thespellbrigade.wiki.gg/wiki/Bell_March); [Cardinal Runes](https://thespellbrigade.wiki.gg/wiki/Cardinal_Runes); [Solar Pulse](https://thespellbrigade.wiki.gg/wiki/Solar_Pulse)
- Unofficial nicknames from a low-reliability fan site: Reginald "The Lucky Mage", Knelly "The Bell Mage", Pipwick "The Summoner", Balthazar "The Revenant". — [thespellbrigade.wiki wizards](https://thespellbrigade.wiki/wizards/); [changelog](https://thespellbrigade.wiki/changelog/)

**Conflicts on unlock requirements and costs**
- **Unlock-quest conflict.** tposegaming's post-1.0 guide groups original-outfit (= wizard) unlocks into survival time, "equip a new spell N times" and level-up counts. The numbers are in the table's "Alt. unlock" column. They differ from wiki.gg for almost every wizard; for example, Ludwig is "take 18,000 damage" on wiki.gg vs "equip a new spell 36 times" in the guide. — [tposegaming wizards guide](https://tposegaming.com/the-spell-brigade-wizards/) vs [wiki.gg Quests](https://thespellbrigade.wiki.gg/wiki/Quests)
- **Gold prices.** A Steam guide titled "[1.0]" says "Wizards are now unlockable with gold": Ludwig 850, Aldric 950, Maggie 1,250, Balthazar 1,450, Pipwick 1,700. — [Steam Guide: The Spell Brigade [1.0]](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916)
- **Patch 7** (fan changelog dates it 11 Jun 2026) "reworked the Wizard & Trial unlocking, improved our Devotion system, and also introduced Tiny Mode". The fan changelog says wizards "reverted to Quest-based unlocking (Gold spent refunded)". — [Steam announcements](https://steamcommunity.com/app/2904000/announcements/); [thespellbrigade.wiki changelog](https://thespellbrigade.wiki/changelog/)
- One player called the switch from gold to quests "discouraging"/more grindy. — [Steam: Wizard unlocking](https://steamcommunity.com/app/2904000/discussions/0/573792728906928554/)

**Base stats**
- No absolute base stats (base HP, move speed, damage) were found. Known modifiers are relative: Hatti −300 Max HP; Campanelli +10% Move Speed; Ludwig −10% Move Speed / +12 Armor. The in-run upgrade Vitality Forge gives +100/200/300/400 Max HP by rarity, but no base value is stated. — [wiki.gg Upgrades](https://thespellbrigade.wiki.gg/wiki/Upgrades); [SteamDB Update 8](https://steamdb.info/patchnotes/17603290/)

### Inferences
**Version currency of each source**
- The wiki.gg per-wizard pages are probably closer to the current (post-Patch 7, post-1.1) quests than the tposegaming list. The wiki pages include Eugenie (1.1), and Patch 7 "reworked" wizard unlocking after the tposegaming guide (≈ May 2026) was written. The tposegaming numbers may reflect the 1.0 launch state. For the app, use wiki.gg values as "current" and keep tposegaming values as "possibly outdated".
- The wiki.gg Quests page lists "14 Wizard Quests". That matches the 14 non-default wizards before 1.1 (all except Reginald). Eugenie adds a 15th wizard quest in 1.1.

**Theme and role per wizard**
- Wizards do not appear to have a fixed element. Elements come in-run through Infusions. Theme/role can be derived from traits:

| Role | Wizards | Basis |
|---|---|---|
| Support / reviver | Aldric, Campanelli, Balthazar | revive and heal traits |
| Tank / bruiser | Ludwig | Armor, elemental immunity |
| Glass cannon / DPS | Hatti, Star Mage, Wizard King, Pipwick | damage and crit traits |
| Economy / utility | Reginald, Maggie, Bryony | Luck, pickups, objective info |
| XP / scaling | Moon Mage, Kavin | XP traits |
| Mobility / evasion | Sun Mage | Dodge, smaller hitbox |
| Retaliation | Knelly | thorns-style damage, death explosion |
| Illusion / control | Eugenie | Illusions |

- The roster count should read 16 for version 1.1+/1.2. Many guides still say "15" because they predate 1.1.

### Gaps
**Wizard data**
- Absolute base stats (HP, move speed, base damage, pickup radius, armor) per wizard were not found. Wizards may share a common base with only trait modifiers on top, but this is unconfirmed.
- Eugenie's Wizard Trait text was not found. The "+25% Spell Size, +10% Damage" on the wiki is the signature-spell bonus, not a confirmed trait. His ascension outfit name and spell are also missing, and the pronoun varies between sources.
- The exact EA update that added Star Mage, and the full EA launch roster, could not be confirmed from primary sources.
- Pipwick's trait conflicts between sources: "+5% Crit Damage, −3% Crit Chance" on wiki.gg vs "increased Crit Chance and Damage" in a patch mirror. Later balance patches may explain the difference.

**Unlock requirements and costs**
- Gold prices for the remaining wizards in the gold era were not found. They are moot after Patch 7 anyway.
- Which unlock-quest list is current in 1.2 (wiki.gg vs tposegaming) could not be verified directly.

---

## 2. Wizard-level systems (skill trees, talents, levels, loadouts) and how wizard choice interacts with spell choice

### Takeaway
Wizards have **no per-wizard skill or talent trees**. Each wizard has a **rank/level (1 → 10)** earned through wizard XP, plus a **badge**. At max rank the wizard can **Ascend** (prestige): rank resets to 1, the badge upgrades, and the first two ascensions give rewards: (1) an Ascension outfit that **changes the starting spell**, and (2) a Trial Covenant.

Wizard choice affects spells in three ways:
- It sets the **starting/signature spell**, which gets signature bonuses.
- It applies a **trait** that may interact with spells (Moon Mage gets spells/infusions earlier, Star Mage boosts elemental damage, Pipwick randomly infuses spells, Ludwig is immune to elemental effects).
- The **outfit choice** can swap the starting spell.

No sources mention spell restrictions per wizard.

### Cited Findings
**Rank, badge and Ascension**
- "After leveling up a wizard to level 10, you can ascend them. This resets their level to 1 and unlocks a reward the first two times they are ascended. On the first ascension, they will gain a new outfit that starts with a different spell, and on the second one they will unlock a covenant." — [wiki.gg Ascension](https://thespellbrigade.wiki.gg/wiki/Ascension)
- The 1.0 press release says the Ascension system lets players reset their wizard rank for upgraded badges. It also mentions secret outfits that change each wizard's starting spell. — [Pirate PR 1.0 press release](https://press.piratepr.com/co-op-wizard-survivors-like-the-spell-brigade-marches-onto-playstation-5-and-10-release-on-steam-on-29-april); [Games Press](https://www.gamespress.com/Gather-Your-Squad-and-Join-the-Fray-The-Spell-Brigade-is-Out-Today)
- A player reports that you click the badge of a max-rank (rank 10) wizard in character select to open the ascension option. Another post says wizards that were at max rank before an update "will now be at the end of Rank 9", so the max-rank threshold (9 vs 10) is in conflict. — [Steam: Ascending your wizard?](https://steamcommunity.com/app/2904000/discussions/0/838375062933398815/)
- tposegaming says a character can ascend "two ascensions maximum". It also says ascension resets rank in exchange for alternate skins, different starting spells and Trial Covenants. — [tposegaming Ascension guide](https://tposegaming.com/spell-brigade-ascension/)

**Signature spells and spell pools**
- Spell Quests (21 of them) "unlock signature spells so that they can be selected when adding a new spell during a mission". Examples: hit N targets with one Moonerang to unlock Moonerang; cast 4 Falling Stars at the same time to unlock Falling Stars. — [wiki.gg Quests](https://thespellbrigade.wiki.gg/wiki/Quests)
- Update 8 introduced "unique Wizard Traits" and starter-spell buffs for each wizard. — [SteamDB Update 8](https://steamdb.info/patchnotes/17603290/)
- Ascension-outfit starting spells apply "only with Ascension Outfit equipped". For example, Reginald starts with Bell March in the Knelly's Pupil outfit. — [wiki.gg Bell March](https://thespellbrigade.wiki.gg/wiki/Bell_March)

**Spell mastery**
- tposegaming says maxing a spell's level unlocks a mastery tree with perks. Context suggests this is an in-run spell system, not a wizard tree. — [tposegaming Ascension guide](https://tposegaming.com/spell-brigade-ascension/)
- Post-1.0 Patch 10 (8 Jul 2026) notes "Size Mastery now affects Spear Barrage and Impish Havoc", which shows that spell masteries exist. — [Steam announcements](https://steamcommunity.com/app/2904000/announcements/)

### Inferences
**Data model**
- For the build-planner, model a wizard as: base (shared, unknown) + Trait modifiers + signature spell (with signature bonus) + outfit, where the outfit determines the starting spell. Treat the ascension outfit as a "starting-spell variant" of the wizard.
- Every spell seems to be available to every wizard once it is unlocked via Spell Quests. Signature spells first have to be unlocked for the general pool. No per-wizard spell ban was found in any source.

**Trait-to-spell synergies**

| Wizard | Trait | Synergy |
|---|---|---|
| Star Mage | +15% Elemental Damage | Infusions |
| Pipwick | random-element infusion | Elemental builds |
| Wizard King | +10% Crit | Crit builds |
| Hatti | +6% Damage | All damage |
| Moon Mage | earlier spells/infusions | Builds that need more spells early |

### Gaps
- Whether the signature-spell bonus (e.g. Reginald's +25% Spell Size/−12% Cooldown on Astral Orbs) applies only to the wizard's own signature spell, or also when another wizard picks that spell, is not stated in the snippets.
- Whether the signature bonus carries over to the ascension outfit's alternative starting spell is unknown.
- The wizard XP formula (XP per run, XP per rank) was not found. One player guessed "Prestige XP = run duration × Devotion modifier", which is unverified. — [Steam: Devotion/Prestige XP](https://steamcommunity.com/app/2904000/discussions/0/838375444718849387/)
- Whether badge tiers continue beyond the 2nd ascension is unclear (cosmetic badge only?). No loadout slots beyond outfit selection were found.

---

## 3. Meta-progression: currencies, permanent upgrades, quests, hub, unlock trees

### Takeaway
There is no account level. Out-of-run progression runs on three things:
1. **Gold**, earned per run and spent on **Enchantments** (permanent stat upgrades bought in the lobby, fully refundable) and **Ascensions**. It was also used to buy wizards until Patch 7.
2. **Wizard rank / Ascension / Devotion**, the prestige layer, fed by **Trial Covenants**.
3. A large **Quest** system (149 quests on the older wiki count) that unlocks wizards, signature spells, outfits, scrolls, realms (maps), covenants and Enchantment tiers.

The hub is a **lobby** where Enchantments are bought and wizards/outfits are selected.

### Cited Findings
**Gold**
- Enchantments are permanent upgrades bought for gold in the lobby. Players can get a full refund of all gold spent on Enchantments at any time, with no penalty. — [wiki.gg Enchantments](https://thespellbrigade.wiki.gg/wiki/Enchantments)
- Gold income per run is roughly 500–550 gold for a normal run and about 800–850 for an optimised Bounty run (fan guide). — [whisperofthehouse gold farm](https://www.whisperofthehouse.com/the-spell-brigade/gold-farm)
- tposegaming advises farming gold on Easy, since higher difficulty gives no extra ascension progress or gold (guide claim). — [tposegaming Ascension guide](https://tposegaming.com/spell-brigade-ascension/)
- Post-1.0 Patch 5 overhauled the gold economy, and Patch 7 added an individual enchantment refund system (fan changelog). — [thespellbrigade.wiki changelog](https://thespellbrigade.wiki/changelog/)

**Enchantments**
- Base prices (level 1), as listed on wiki.gg:

| Base price | Enchantments |
|---|---|
| 100 | Damage, Mana Pull, Revive Speed, Max Health |
| 150 | Critical Damage, Mana Gain, Revive Circle, Armor |
| 200 | Cast Speed, Bounty, Revive, Regeneration |
| 250 | Spell Size, Reroll, Luck, Move Speed |
| 300 | Critical Chance, Banish, Lock, Dodge |

- Each enchantment has 5 levels plus a Mastery effect. Examples: Damage reaches +25% at level 5, and Max Health reaches +750. Damage mastery gives extra damage against enemies above 70% HP, Armor mastery gives temporary invulnerability after taking damage, and Bounty at max doubles gold from objectives. Unlocking everything including masteries costs **124,287 gold** in total. — [wiki.gg Enchantments](https://thespellbrigade.wiki.gg/wiki/Enchantments)
  - The search summary said "17 lobby upgrades", but the price list above names 20. Count conflict: verify.
- Enchantment tiers are quest-gated: Tier 1 by quest; Tier 2 "Perform 7 Enchantments"; Tier 3 requires 5 masteries activated; Tier 4 requires 8 masteries. — [wiki.gg Enchantments](https://thespellbrigade.wiki.gg/wiki/Enchantments); [wiki.gg Quests](https://thespellbrigade.wiki.gg/wiki/Quests)
- A Steam thread titled "enchantments reset" exists, suggesting a post-1.0 reset event (details not seen). — [Steam: enchantments reset](https://steamcommunity.com/app/2904000/discussions/0/838375062933396559/)

**Ascension cost**
- The two sources disagree:

| Source | Ascension cost |
|---|---|
| [tposegaming Ascension guide](https://tposegaming.com/spell-brigade-ascension/) | 4,000 gold per ascension, roughly 3–4 h of farming |
| [wiki.gg Ascension](https://thespellbrigade.wiki.gg/wiki/Ascension) | Table starts at 3,300 gold for "Ascension 0" and rises per ascension (table layout ambiguous in the snippet) |

**Devotion and Trial Covenants**
- Trial Covenants are a subgroup of Covenants that unlock with each new ascension. They make the game harder in exchange for extra wizard XP and gold. — [wiki.gg Covenants](https://thespellbrigade.wiki.gg/wiki/Covenants)
- Each covenant has a Devotion value:

| Covenant | Devotion |
|---|---|
| Onslaught | 1 / 2 / 4 by stack |
| Diminution | 2 (new trial in Patch 7) |
| Purity | 4 |
| Mortality | 5 |

  Source: [wiki.gg Covenants](https://thespellbrigade.wiki.gg/wiki/Covenants).
- Covenants are also unlocked via quests: "Attempt a Severe Mission" unlocks the **Eternity** covenant. — [wiki.gg Quests](https://thespellbrigade.wiki.gg/wiki/Quests)
- Devotion is the multiplier for ascension progress and is earned through Trial Covenants. It "spikes the difficulty hard". — [tposegaming Ascension guide](https://tposegaming.com/spell-brigade-ascension/)
- EA Update 9 was named "Dark Devotion", and Patch 7 (2026) "improved our Devotion system". — [Steam: EA Update 9](https://steamcommunity.com/games/2904000/announcements/detail/528717787215955183); [Steam announcements](https://steamcommunity.com/app/2904000/announcements/)
- A hotfix after Patch 7 fixed outfit and covenant progression bugs, including Trial covenants not unlocking retroactively (fan changelog). — [thespellbrigade.wiki changelog](https://thespellbrigade.wiki/changelog/)

**Quests and unlock chains**
- The older wiki counts **149 Quests** in categories Missions, Wizards (14), Spells (21), Outfits (39), Scrolls, Ascension (34) and Misc. The page's own wording is inconsistent ("seven categories" but describes five). — [wiki.gg Quests](https://thespellbrigade.wiki.gg/wiki/Quests)
- Realm (map) unlock chain via Mission quests:
  1. Complete a mission in Verdant Meadow → unlocks Frozen Ancients. A separate page says "survive 12 minutes in Verdant Meadows".
  2. Complete one in Frozen Ancients → unlocks Pyrestorm Pit.
  3. Complete one in Pyrestorm Pit → unlocks Astral Riftlands (added in EA Update 12).

  Sources: [wiki.gg Quests](https://thespellbrigade.wiki.gg/wiki/Quests); [wiki.gg Frozen Ancients](https://thespellbrigade.wiki.gg/wiki/Frozen_Ancients)
- 1.1 added "10 new Quests" and "7 new Scrolls, each unlockable through their own Quest". The search summary attributed this to the post that also contains Patch 7, so the exact patch is unclear. The low-reliability fan changelog places 7 new Scrolls in Patch 9 (1 Jul 2026). — [Steam announcements](https://steamcommunity.com/app/2904000/announcements/); [thespellbrigade.wiki changelog](https://thespellbrigade.wiki/changelog/)
- Boss kills can unlock titles; for example, defeating Krog'wa unlocks the title "Toad Trampler". — [Sihmar 0.11.0.4763](https://sihmar.com/the-spell-brigade-update-0-11-0-4763-patch-notes-july-2-2025/)

**Modes and third-party save editors**
- Other modes/modifiers: Endless and No Friendly Fire modifiers (Dec 2024 update), and Tiny Mode (Patch 7). — [X @thespellbrigade status](https://x.com/thespellbrigade/status/1864982605247996333); [Steam announcements](https://steamcommunity.com/app/2904000/announcements/)
- A third-party save editor advertises unlocking "all covenants, prestige characters, max upgrades, achievements, outfits, and gold". It is not official, but its list confirms the categories of persistent progress. — [GitHub oAntz/SpellBrigadeUnlocker](https://github.com/oAntz/SpellBrigadeUnlocker)

### Inferences
- Progression layers for the planner:

| Layer | What it holds |
|---|---|
| Account-wide | Enchantments (with 4 quest-gated tiers), unlocked spells, scrolls, realms, covenants, outfits |
| Per wizard | Rank 1–10, ascension count (0–2+), badge |
| Per run | Covenants/Devotion selection |

- Because Enchantments are fully refundable, the build-planner can treat the Enchantment loadout as a freely re-assignable "gold budget" rather than a permanent choice.
- The repeated "Patch N" numbering after 1.0 (Patches 1–10, May–Jul 2026) is separate from EA "Update N" numbering (Updates 8–13, 2025). Keep both labels distinct in the app's version metadata.

### Gaps
- No account level or player profile level was found. It may not exist.
- The exact number of Enchantments in 1.2 (17 vs 20) and their per-level values beyond the examples given are not in hand.
- The current ascension cost (4,000 flat vs a rising table starting at 3,300) and the exact Devotion → XP formula are unresolved.
- The Patch 7 Devotion rework details and Tiny Mode rules were not found.
- The current quest count after the 1.0, Patch 7 and 1.1 additions is unknown. 149 is an older figure.

---

## 4. Unlockables and achievements (what unlocks what)

### Takeaway
Nearly everything is quest-gated:
- **Wizards:** 14 wizard quests plus Eugenie's.
- **Signature spells:** 21 spell quests.
- **Outfits:** 39 outfit quests, plus ascension outfits.
- **Scrolls, realms, covenants and Enchantment tiers.**

Steam has **113–114 achievements** (1.0 era, sources differ). Only a few are explicit wizard-unlock achievements ("Unlock Sun Mage", "Unlock Moon Mage"); many others are wizard-specific feats.

### Cited Findings
**What unlocks what**

| Unlockable | How it unlocks | Count/notes |
|---|---|---|
| Wizards | Wizard Quests (catalogue table, section 1) | 14 + Eugenie |
| Signature spells (into the general spell pool) | Spell Quests | 21 |
| Outfits | Outfit Quests and ascensions | 39 outfit quests |
| Realms | Mission quests | chain in section 3 |
| Covenants | Quests/ascensions | e.g. Eternity: attempt a Severe Mission |
| Enchantment tiers | Quests | 4 tiers |
| Scrolls | Scroll quests | — |

  Sources: [wiki.gg Quests](https://thespellbrigade.wiki.gg/wiki/Quests); [wiki.gg Ascension](https://thespellbrigade.wiki.gg/wiki/Ascension); [wiki.gg Enchantments](https://thespellbrigade.wiki.gg/wiki/Enchantments)

**Achievements**
- Steam Hunters lists 113 base-game achievements. A fan guide says the 1.0 list has 114 Steam achievements. — [Steam Hunters](https://steamhunters.com/apps/2904000/achievements); [whisperofthehouse achievements guide](https://www.whisperofthehouse.com/the-spell-brigade/achievements-guide)
- Explicit unlock achievements found: "Unlock Sun Mage" and "Unlock Moon Mage". Wizard-specific achievements also exist for Star Mage, Hatti, Knelly, Ludwig and others. — [Steam Hunters](https://steamhunters.com/apps/2904000/achievements)
- The guide names these as the hardest-to-plan achievements: Heckin' Hardcore, π, Starry Rain, Hells Bells, Out with a Bang, A Worthy Sacrifice, The Fungi Amongi. — [whisperofthehouse achievements guide](https://www.whisperofthehouse.com/the-spell-brigade/achievements-guide)
- Its suggested order: normal clears → wizard unlocks → spell/element achievements → objectives → wizard-specific → restriction routes → long cumulative grinds. For achievement hunting it suggests unlocking Star Mage, Hatti, Bryony, Campanelli, Knelly. — [whisperofthehouse achievements guide](https://www.whisperofthehouse.com/the-spell-brigade/achievements-guide); [whisperofthehouse wizard unlocks](https://www.whisperofthehouse.com/the-spell-brigade/wizard-unlocks)
- The fan changelog mentions a post-1.0 fix for a "Knelly explosion achievement not triggering on boss kills". — [thespellbrigade.wiki changelog](https://thespellbrigade.wiki/changelog/)
- Other achievement and trophy lists: [GameFAQs PC achievements](https://gamefaqs.gamespot.com/pc/462264-the-spell-brigade/achievements); [GameFAQs PS5](https://gamefaqs.gamespot.com/ps5/638324-the-spell-brigade/achievements); [PSNProfiles trophies](https://psnprofiles.com/trophies/41118-the-spell-brigade)

### Inferences
- "Starry Rain" (Star Mage/Falling Stars), "Hells Bells" and "Out with a Bang" (Knelly/Bell March/explosions) appear to be wizard-themed achievements, judging by the names. This is inferred only from the names.
- Quests (in-game unlocks) and Steam achievements are separate systems. Unlock logic in the planner should follow quests, not achievements.

### Gaps
- No full achievement list with descriptions could be retrieved (page fetch blocked). Whether 1.1/1.2 added achievements (e.g. for Eugenie) is unknown.
- Full lists of the 21 spell quests, 39 outfit quests and 34 ascension quests are not in hand (only examples).

---

## 5. Cosmetics (outfits, skins, hats, titles, badges)

### Takeaway
Cosmetics are **outfits** (full-wizard skins), **titles** and **rank badges**. No separate hat or robe slot was found.

| Outfit source | Notes |
|---|---|
| Quest outfits | Original outfit = the wizard unlock; plus 2–3 alternate outfits per wizard |
| Ascension outfits | **Change the starting spell**, the only cosmetic with a gameplay effect |
| Paid Supporter Pack | Golden and Sketchy skins per wizard, purely aesthetic |
| Early Access exclusive | One skin per wizard for players who played during Early Access |
| Seasonal | Spooky outfits from Update 13 |

### Cited Findings
**Supporter Pack (paid DLC)**
- The Supporter Pack DLC (Steam app 3194200, released 16 Sep 2024 alongside EA) adds Golden and Sketchy (black-and-white concept) skins. Listings disagree on counts: most say 15 Golden + 15 Sketchy; older listings say 8 or 11 of each, presumably because the pack grew with the roster.
- The skins are described as "purely aesthetic and do not impact gameplay, power levels, or game progression".
- Sources: [gg.deals Supporter Pack](https://gg.deals/dlc/the-spell-brigade-supporter-pack/); [isteam.net](https://isteam.net/app/3194200); [Steam Supporter Edition bundle](https://store.steampowered.com/bundle/44452/The_Spell_Brigade__Supporter_Edition/)
- A Steam announcement, "More Skins for the Supporter Pack!", gave each wizard an additional Golden Outfit. — [Steam announcement](https://steamcommunity.com/app/2904000/eventcomments/595143167557278920?snr=2_groupannouncements_detail_)
- tposegaming lists Golden/Sketchy variants (e.g. Golden Reginald, Sketchy Kavin) as obtainable only by buying the Supporter Pack. — [tposegaming wizards guide](https://tposegaming.com/the-spell-brigade-wizards/)

**Other outfit sources**
- The 1.0 launch added "an extra skin for each Wizard that will be exclusive to anyone that has played the full game during Early Access". — [Pirate PR 1.0 press release](https://press.piratepr.com/co-op-wizard-survivors-like-the-spell-brigade-marches-onto-playstation-5-and-10-release-on-steam-on-29-april)
- Quest-unlocked outfit examples:

| Outfit | Unlock quest |
|---|---|
| Dragon Tamer Pipwick / Pipwick the Tune Tinkerer | Imp-count and infusion quests |
| Nightshift / Emperor Balthazar | (added in EA Update 10) |
| Dark Phase / Genuine Djinn Eugenie | Illusion quests |
| Hattree (Hatti) | Kill 300 enemies stuck in bushes (Quests page); the Hatti page differs ("Frost Branch") |

  Sources: [Sihmar 0.11.0.4763](https://sihmar.com/the-spell-brigade-update-0-11-0-4763-patch-notes-july-2-2025/); [Steam patch notes feed](https://store.steampowered.com/news/posts/?feed=steam_community_announcements&enddate=1747835965); [wiki.gg Eugenie](https://thespellbrigade.wiki.gg/wiki/Eugenie); [wiki.gg Quests](https://thespellbrigade.wiki.gg/wiki/Quests); [wiki.gg Hatti](https://thespellbrigade.wiki.gg/wiki/Hatti)
- Update 13 (Oct 2025) added seasonal (spooky) outfits. — [Rogueliker Update 13](https://rogueliker.com/the-spell-brigade-update-13/)
- 1.1 added 8 outfits: 3 for Eugenie, plus 1 each for Moon Mage, Kavin, Pipwick, Maggie and Sun Mage. It also added character rotation in the outfit menu. — [Steam announcements](https://steamcommunity.com/app/2904000/announcements/)

**Ascension outfits, titles and badges**
- Ascension outfits swap the starting spell: "starts with a different spell" (table in section 1). — [wiki.gg Ascension](https://thespellbrigade.wiki.gg/wiki/Ascension)
- Titles are cosmetic rewards, e.g. "Toad Trampler" for defeating Krog'wa. Rank badges upgrade with each Ascension. — [Sihmar 0.11.0.4763](https://sihmar.com/the-spell-brigade-update-0-11-0-4763-patch-notes-july-2-2025/); [Pirate PR 1.0 press release](https://press.piratepr.com/co-op-wizard-survivors-like-the-spell-brigade-marches-onto-playstation-5-and-10-release-on-steam-on-29-april)

### Inferences
- For the planner, outfits can be ignored as stat sources. The exception is ascension outfits, which should be modelled as "alternative starting spell" options per wizard.

### Gaps
- No evidence was found of separate hat/robe slots, a cosmetic shop, or a cosmetic currency.
- A complete per-wizard outfit list with each unlock quest (39 outfit quests) was not retrievable.
- The name of the Early Access–exclusive outfits was not found.

---

## 6. Tier lists and community consensus on strongest/weakest wizards

### Takeaway
There is no authoritative community tier list. Rankings come from fan wikis and guide sites, and they disagree.

| Category | Wizards | Notes |
|---|---|---|
| Most often top-rated | Star Mage, Reginald, Sun Mage, Campanelli | Star Mage for DPS ceiling; Reginald for Luck; Sun Mage for solo safety; Campanelli for co-op revives and double-hit |
| Most often rated weaker | Aldric, Pipwick | Aldric is weak solo; Pipwick is complex and weak early |
| Polarising | Ludwig | Depends on skill level |

No Reddit threads were found by the search tool.

### Cited Findings
**Low-reliability fan site (thespellbrigade.wiki)**
- Its rankings:

| Tier | Wizards | Site's reasoning |
|---|---|---|
| S | Star Mage | "highest DPS ceiling in game with Falling Stars" |
| S | Reginald | best starter thanks to +2 Luck improving upgrade quality |
| A | Campanelli | "double-hit DPS + best revive support" |
| C | Aldric | "weak solo; essential in Hardcore co-op only" |
| C | Pipwick | "unique but complex; weak early" |
| C (beginners) / S (expert hands) | Ludwig | depends on skill |

- It also calls Star Mage + Falling Stars + Lightning the "community consensus best build".
- Sources: [thespellbrigade.wiki tier list](https://thespellbrigade.wiki/builds/tier-list/); [thespellbrigade.wiki wizards](https://thespellbrigade.wiki/wizards/)

**Other guide sites**
- One guide calls Sun Mage the best early unlock, mainly for solo play. Another ranks him S-tier as the "safest carry". Another rates Campanelli S for co-op, and one places Ludwig in S-tier. The search summary did not say which of these three sites said what. — [whisperofthehouse wizard unlocks](https://www.whisperofthehouse.com/the-spell-brigade/wizard-unlocks); [2upskill 1.0 guide](https://2upskill.com/the-spell-brigade-1-0-guide-best-builds-meta-spells-and-wizard-tier-list-2026-update/); [guidexon tier list](https://guidexon.com/the-spell-brigade-tier-list/)
- Related spell consensus: guide sites agree Falling Stars and Aurora Wings (Star Mage and Maggie signature spells) are top-tier. Solar Pulse (Sun Mage) is the most cited weak spell but "excellent with the right infusion". — [guidexon](https://guidexon.com/the-spell-brigade-tier-list/); [whisperofthehouse spells tier list](https://www.whisperofthehouse.com/the-spell-brigade/best-spells-elements)

**Player comments**
- Hatti's negative traits were contested by players at Update 8. The devs defended them as intentional glass-cannon trade-offs. — [Steam Update 8 event comments](https://steamcommunity.com/app/2904000/eventcomments/595142635297997301/?l=english&ctp=7)
- A Steam thread "What are your favorite wizards and spells??" exists, but its content was not retrievable. — [Steam discussion](https://steamcommunity.com/app/2904000/discussions/0/580550507183179156/)
- A Steam player found Eugenie's Seismic Slam weaker than other spells. — [Steam: Eugenie's spell](https://steamcommunity.com/app/2904000/discussions/0/588436698284762850/)

### Inferences
- The traits explain the rankings:
  - Star Mage's +15% Elemental Damage scales with infusions.
  - Reginald's +2 Luck improves every level-up choice.
  - Sun Mage's Dodge plus a −25% hitbox makes him safe solo.
  - Aldric's and Campanelli's traits are revive/heal oriented, which are worth little solo and a lot in co-op.

  A build-planner could tag wizards "solo" vs "co-op" accordingly.
- Most tier lists date from the 1.0 period (spring 2026). They predate Patches 5–10 (gold economy, spell buffs like Talon Slash +20% and its no-longer-split damage, Impish Havoc damage multiplier 1 → 1.5) and 1.1/1.2, so Balthazar and Pipwick may be stronger now than those lists suggest. — balance changes from [thespellbrigade.wiki changelog](https://thespellbrigade.wiki/changelog/) and [Steam announcements](https://steamcommunity.com/app/2904000/announcements/)

### Gaps
- No Reddit, YouTube-description or Steam-guide tier list could be read in full. The "community consensus" here rests on SEO guide sites of uncertain authorship.
- No tier placement exists for Eugenie (1.1) or any post-1.1 re-evaluation.
- No win-rate or usage statistics exist from any source.
