# The Spell Brigade: spells, elements (infusions) and combination mechanics

Research date: 2026-10-12. Game: *The Spell Brigade* (Bolt Blaster Games; Steam app 2904000; PC + PS5), a 1-4 player online co-op wizard survivors-like. Current version is **1.2** (build 1.2.0.20127, early October 2026).

**Method caveat for the report writer.** Page fetching was blocked in this environment (DNS/egress policy denied wiki.gg, steamcommunity.com, store.steampowered.com and all guide sites). Every fact below comes from search-engine result summaries and snippets of the cited pages, not from reading the full pages. Treat exact numbers as "reported by source X". The best primary sources are the fan wiki at **thespellbrigade.wiki.gg**, Steam guides and Steam announcements. The cached wiki.gg snapshots are old: the Infusions/Elements pages were about 689 days old (late Early Access) and the Spells page snapshot (oldid=2027) about 542 days old. **thespellbrigade.wiki** (no ".gg") is a different, third-party site labelled "1.0". It looks SEO-driven and sometimes disagrees with the other sources. **xmodhub.com** and **hyper3d.ai** list spells that do not exist in this game ("Arcane Rift", "Frost Nova", "Fireball", "Lightning Bolt", class "Archmage"). Exclude them.

### Version timeline relevant to spells (for the "added in" column)

| Version / update | Date | Spell-relevant content | Source |
|---|---|---|---|
| EA 0.7.2 | 29 Jan 2025 | Spell Slots UI enlarged (Steam Deck readability) | [SteamDB 0.7.2](https://steamdb.info/patchnotes/17171436/) |
| EA Update 8 | 5 Mar 2025 | (content not retrieved) | [SteamDB Update 8](https://steamdb.info/patchnotes/17603290/) |
| EA 0.11.0.4763 | 2 Jul 2025 | "Updated the UI for the Spell Slots and their Infusions" | [sihmar.com 0.11 notes](https://sihmar.com/the-spell-brigade-update-0-11-0-4763-patch-notes-july-2-2025/) |
| EA Update 13 "Pumpkin Panic" (final EA content drop) | 22 Oct 2025 | New spells **Swirl Sickle** and **Spear Barrage** | [Rogueliker Update 13](https://rogueliker.com/the-spell-brigade-update-13/); [thespellbrigade.wiki changelog](https://thespellbrigade.wiki/changelog/) |
| **1.0** full release (build 1.0.0.16435) | 29 Apr 2026 | New wizard Star Mage with **Falling Stars** ("4-instance cap"); Knelly with **Bell March**; new enchantments/masteries incl. **Ban & Pin**; infusion renames (e.g. Acid+Fire now "Brimstone"); Wildfire can crit | [vpesports 1.0](https://vpesports.com/featured-news/the-spell-brigade-exits-early-access); [GameHypes 1.0](https://gamehypes.com/news/the-spell-brigade-1-0); [Steam guide 1.0](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916) |
| 1.0 Patches 1-9 | 29 Apr - 1 Jul 2026 | Patch 5 (19 May): economy/objectives; Patch 7 (11 Jun): wizard & trial unlocking, Ascensions, Devotion, "Spell Cores"; Patch 9 (1 Jul): new Scrolls and balance | [GameBrief / changelog summary](https://www.gamebrief.net/blog/the-spell-brigade-tips-guide-2026); [Veklar](https://veklar.com/games/the-spell-brigade) |
| **1.1 "Realm Sweep"** | 2 Sep 2026 | New wizard Eugenie (spelled "Eugene" by Rogueliker) with new spell **Seismic Slam**; bigger Spell Cores (an objective variant) | [Steam news 1.1](https://store.steampowered.com/news/app/2904000/view/715662120170030645); [Rogueliker 1.1](https://rogueliker.com/the-spell-brigade-realm-sweep/) |
| 1.1 Patches 1-4 | 2-17 Sep 2026 | (spell details not retrieved) | [Steam announcements](https://steamcommunity.com/app/2904000/announcements/) |
| **1.2** (build 1.2.0.20127) | X post says out 2 Oct 2026; patch notes dated "06-10-26" | New spells **Loaded Dice**, **Tiny Tremors**, **Wicked Buzzsaw** (4 augmentations each, unlocked from the start); **13 new augmentations for older spells** (e.g. Aura Beam, Baby Sprout, Chthonic Pull, Counter Talon); devs say a bigger update is planned for end of 2026 | [Steam announcements](https://steamcommunity.com/app/2904000/announcements/); [Steam all news](https://steamcommunity.com/app/2904000/allnews/); [@thespellbrigade on X](https://x.com/thespellbrigade) |

---

## 1. Complete list of spells (name, type, stats, level-up, unlock)

### Takeaway
I found **26 confirmed spells** as of 1.2: 23 from EA through 1.1, plus 3 added in 1.2. A 27th, "Resurrection Beam", appears on only one low-reliability site. Spells have no fixed element; any spell can take any element through infusions (see section 2). Almost no exact base stats (damage, cooldown) were retrievable. Unlock requirements ("Spell Quests") and mechanic descriptions are partly known.

### Cited Findings

**General**
- The wiki.gg "All Wizard Spells" page lists the spells alphabetically from Arcane Broadsword and Astral Orbs to Vengeful Sprout. Its old snapshot has 22 entries — [wiki.gg Spells](https://thespellbrigade.wiki.gg/wiki/Spells)
- Spells have no fixed element. Elements are added as infusions to any spell at spell levels 7 and 14 — [wiki.gg Infusions](https://thespellbrigade.wiki.gg/wiki/Infusions); [Steam guide 1.0](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916)
- "Spell Quests unlock signature spells so that they can be selected when adding a new spell during a mission." There are **21 Spell Quests** — [wiki.gg Quests](https://thespellbrigade.wiki.gg/wiki/Quests)
- Each wizard has a signature (starting) spell. The first Ascension unlocks an outfit that swaps the starting spell. An ascension costs 4,000 gold, with at most two per character — [wiki.gg Ascension](https://thespellbrigade.wiki.gg/wiki/Ascension); [tposegaming Ascension guide](https://tposegaming.com/spell-brigade-ascension/)
- The three 1.2 spells are "unlocked from the start" — [Steam announcements](https://steamcommunity.com/app/2904000/announcements/)
- A Steam discussion says 1.0 announced a feature to pick your starting spell, which may need unlocking first — [Steam: Starting spells](https://steamcommunity.com/app/2904000/discussions/0/806849231160733975/)

**Spell catalogue**

Legend: "Type" is my classification from the descriptions (marked *inferred* when no source states it). "Sig." is the wizard whose signature spell it is. "Asc." is the wizard whose first-ascension outfit starts with it. Wizard mapping is included only because it decides availability.

| # | Spell (exact name) | Type | What it does (as reported) | Known numbers | Sig. / Asc. | Unlock (Spell Quest) | Added in | Sources |
|---|---|---|---|---|---|---|---|---|
| 1 | **Aether Beam** | Beam (damage or heal) | Dual-purpose beam that damages enemies or heals teammates; called "the only native healing spell in the game" | – | Sig.: Aldric; Asc.: Balthazar | not found | EA | [Steam guide 1.0](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916); [thespellbrigade.wiki spells](https://thespellbrigade.wiki/spells/); [wiki.gg Ascension](https://thespellbrigade.wiki.gg/wiki/Ascension) |
| 2 | **Arcane Broadsword** | Melee/sword (*inferred*) | No mechanic description found; "excellent with Venom DoT" | – | Sig.: Ludwig (the Steam guide spells it "Arcana Broadsword"); Asc.: Bryony | not found | EA | [Steam guide 1.0](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916); [guidexon tier list](https://guidexon.com/the-spell-brigade-tier-list/) |
| 3 | **Astral Orbs** | Orbiting projectiles | Orbs continuously orbit the character and hit enemies repeatedly; "best augment synergy", "best boss killer with Acid" | – | Sig.: Reginald | not found | EA | [Whisper of the House wizards](https://www.whisperofthehouse.com/the-spell-brigade/wizard-unlocks); [guidexon](https://guidexon.com/the-spell-brigade-tier-list/) |
| 4 | **Aurora Wings** | Projectile/summon birds (*inferred*) | Fires birds that can pass through or hit several targets | – | Sig.: Maggie (thespellbrigade.wiki); Asc.: Pipwick | "Hit 5 targets with one Aurora Wings Bird" | EA | [wiki.gg Quests](https://thespellbrigade.wiki.gg/wiki/Quests); [thespellbrigade.wiki wizards](https://thespellbrigade.wiki/wizards/); [wiki.gg Ascension](https://thespellbrigade.wiki.gg/wiki/Ascension) |
| 5 | **Bell March** | Placed/marching explosive (*inferred*) | Bells explode; "Unrung Bells always explode at the end of their lifetime, but the explosion is smaller" | – | Sig.: Knelly; Asc.: Reginald | "Hit 18 enemies with one Bell's explosion" | 1.0 (with Knelly) | [wiki.gg Quests](https://thespellbrigade.wiki.gg/wiki/Quests); [Steam guide 1.0](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916) |
| 6 | **Cardinal Runes** | Rune projectiles/area (*inferred*) | Rune spell; its unique upgrades include **Spell Range** instead of size | Unique upgrades: Spell Damage, Spell Cooldown, Spell Range at 10/15/25/35% | Asc.: Star Mage | "Hit one target with 3 sequential hits of a Rune Burst" | EA | [wiki.gg Quests](https://thespellbrigade.wiki.gg/wiki/Quests); [wiki.gg Cardinal Runes](https://thespellbrigade.wiki.gg/wiki/Cardinal_Runes) |
| 7 | **Chthonic Charge** | Mines/traps | Lays energy mines that detonate after a delay or on contact. Augments can make charges heal allies, come in bursts, or drift toward targets | – | Asc.: Sun Mage | not found | EA | [wiki.gg Chthonic Charge](https://thespellbrigade.wiki.gg/wiki/Chthonic_Charge); [wiki.gg Ascension](https://thespellbrigade.wiki.gg/wiki/Ascension) |
| 8 | **Falling Stars** | Targeted area strike (sky drop) | Calls stars down on enemy positions | Up to **4 instances** active at once ("4-instance cap") | Sig.: Star Mage | not found | 1.0 (with Star Mage) | [vpesports 1.0](https://vpesports.com/featured-news/the-spell-brigade-exits-early-access); [thespellbrigade.wiki tier list](https://thespellbrigade.wiki/builds/tier-list/) |
| 9 | **Hex Bomb** | Explosive burst | Burst-damage explosions with a slow cadence; "cooldown reduction becomes almost mandatory" | – | Asc.: Campanelli | not found | not found | [guidexon](https://guidexon.com/the-spell-brigade-tier-list/); [wiki.gg Ascension](https://thespellbrigade.wiki.gg/wiki/Ascension) |
| 10 | **Impish Havoc** | Summon (minions) | Summons small imps that hunt nearby enemies; damage grows the longer they live; relies on summon upgrades (count, duration) | Unique upgrades: Spell Damage, Spell Cooldown, Spell Lifetime at 10/15/25/35% | Sig.: Pipwick | not found | EA | [wiki.gg Impish Havoc](https://thespellbrigade.wiki.gg/wiki/Impish_Havoc); [guidexon](https://guidexon.com/the-spell-brigade-tier-list/) |
| 11 | **Magic Missile** | Projectile spread (cone) | A spread of projectiles in a cone; good against dense packs, inaccurate against single targets | – | Sig.: Wizard King | not found | EA | [thespellbrigade.wiki spells](https://thespellbrigade.wiki/spells/); [Steam guide 1.0](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916) |
| 12 | **Moonerang** | Returning projectile (boomerang) | Hits going out and again on the return (2 hits per cast); "Moonerangs increase in Size over their lifetime (stacks)"; Spell Range upgrade available | 2 hits/cast | Sig.: Moon Mage (Steam guide, Whisper); thespellbrigade.wiki says Campanelli (**conflict**) | "Hit 12 targets with one Moonerang" | EA | [wiki.gg Quests](https://thespellbrigade.wiki.gg/wiki/Quests); [wiki.gg Upgrades](https://thespellbrigade.wiki.gg/wiki/Upgrades); [Steam guide 1.0](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916) |
| 13 | **Necro Whirl** | Aura / area zone | Conjures energy auras that damage everything in reach. The "Pulling Whirl" version/augment pulls enemies to the center | **Base Lifetime 1.5 s; Base Spell Range 13** | Asc.: Kavin | not found | not found | [wiki.gg Necro Whirl](https://thespellbrigade.wiki.gg/wiki/Necro_Whirl) |
| 14 | **Phantom Blades** | Projectile spread (daggers) | Fires a forward spread of daggers. Augments add blades, a rear volley, blades that heal teammates, or burst fire | "Each upgrade adds 20% spell damage split across all projectiles" | Sig.: Campanelli | "Hit a Golden Crab with one of your Phantom Blades" | EA | [wiki.gg Phantom Blades](https://thespellbrigade.wiki.gg/wiki/Phantom_Blades); [wiki.gg Quests](https://thespellbrigade.wiki.gg/wiki/Quests) |
| 15 | **Rocky Road** | Ground path / line of rocks (*inferred*) | Creates rocks (can crit). Spell Size lengthens the road but not its width | – | Sig.: Kavin; Asc.: Knelly | "Create 850 crit rocks" | EA | [wiki.gg Quests](https://thespellbrigade.wiki.gg/wiki/Quests); [wiki.gg Upgrades](https://thespellbrigade.wiki.gg/wiki/Upgrades) |
| 16 | **Rune Burst** | Projectile(s) | Projectile spell with strong AoE; "can be augmented four times in a single mission — the maximum for any spell"; its extra-projectile augment "casts an additional projectile" | Extra-projectile augment: max **6 upgrades, 10 total projectiles**; unique upgrades: Damage/Cooldown/Range 10/15/25/35% | Sig.: Hatti (thespellbrigade.wiki) | not found | EA | [wiki.gg Rune Burst](https://thespellbrigade.wiki.gg/wiki/Rune_Burst); [thespellbrigade.wiki spells](https://thespellbrigade.wiki/spells/) |
| 17 | **Scepter Mesh** | Placed walls / zone control | Places scepters linked by damaging energy walls that enemies must pass through. Better with infusions and Spell Size. The "Scepter Link" augment connects scepters to the caster as a damaging beam. Weak early, needs several upgrades | – | Asc.: Moon Mage ("Scepter Mage" outfit) | not found | not found | [wiki.gg Ascension](https://thespellbrigade.wiki.gg/wiki/Ascension); [Steam: Ascension skin spells](https://steamcommunity.com/app/2904000/discussions/0/838375062933398814/) |
| 18 | **Seismic Slam** | Ground slam AoE | Slam spell; achievement "Hit 50 Monsters with 1 Slam" | – | Sig.: Eugenie | not found | **1.1 Realm Sweep** | [Steam news 1.1](https://store.steampowered.com/news/app/2904000/view/715662120170030645); [TrueSteamAchievements](https://truesteamachievements.com/a3640600/seismic-slam-achievement) |
| 19 | **Solar Pulse** | Aura / pulse around caster | Pulse that hits many enemies around the player; depends heavily on infusions; can crit through Wildfire since 1.0 | – | Sig.: Sun Mage; Asc.: Aldric | "Use the Solar Pulse to hit 10 targets at once, 99 times" | EA | [wiki.gg Quests](https://thespellbrigade.wiki.gg/wiki/Quests); [guidexon](https://guidexon.com/the-spell-brigade-tier-list/) |
| 20 | **Spear Barrage** | Projectile volley (cone) | Volley of spears in a forward cone; directional | – | Asc.: Wizard King | not found | EA Update 13 (Oct 2025) | [Rogueliker Update 13](https://rogueliker.com/the-spell-brigade-update-13/); [guidexon](https://guidexon.com/the-spell-brigade-tier-list/) |
| 21 | **Swirl Sickle** | Area zones (or melee arc; **conflict**) | One source: whirlwind damage zones at target locations lasting several seconds. BioGamer Girl: a fast, arcing melee spell | – | Asc.: Hatti | not found | EA Update 13 (Oct 2025) | [Rogueliker Update 13](https://rogueliker.com/the-spell-brigade-update-13/); [BioGamer Girl review](http://www.biogamergirl.com/2025/12/the-spell-brigade-cooperative.html) |
| 22 | **Talon Slash** | Melee slash with life steal | Slash attack with life-steal sustain. "Counter Talon" augment: after taking damage, the next cast has 2 extra Talons | – | Sig.: Balthazar (Steam guide); Asc.: Ludwig | "Steal Health from a Scroll Chest" | EA | [wiki.gg Quests](https://thespellbrigade.wiki.gg/wiki/Quests); [thespellbrigade.wiki tier list](https://thespellbrigade.wiki/builds/tier-list/) |
| 23 | **Vengeful Sprout** | Summon/plant (*inferred*) | No mechanic text retrieved. 1.2 added the "Baby Sprout" augment | Unique upgrades: Spell Damage +10/15/25/35%, Spell Cooldown −10/15/25/35% | Sig.: Bryony; Asc.: Maggie | not found | EA | [wiki.gg Vengeful Sprout](https://thespellbrigade.wiki.gg/wiki/Vengeful_Sprout); [wiki.gg Ascension](https://thespellbrigade.wiki.gg/wiki/Ascension) |
| 24 | **Loaded Dice** | Thrown explosive | Giant dice that explode according to the side they land on | 4 augmentations | – (unlocked from start) | none (start) | **1.2** | [Steam announcements](https://steamcommunity.com/app/2904000/announcements/) |
| 25 | **Tiny Tremors** | Ground AoE | Triggers mini earthquakes | 4 augmentations | – (unlocked from start) | none (start) | **1.2** | [Steam announcements](https://steamcommunity.com/app/2904000/announcements/) |
| 26 | **Wicked Buzzsaw** | Seeking projectile | A spinning blade that lunges at targets | 4 augmentations | – (unlocked from start) | none (start) | **1.2** | [Steam announcements](https://steamcommunity.com/app/2904000/announcements/) |
| ? | *Resurrection Beam* | Beam | "Extreme sustained single-target DPS". **Unverified**: only on the third-party thespellbrigade.wiki; may be an error or a misnamed Aether Beam | – | – | – | – | [thespellbrigade.wiki tier list](https://thespellbrigade.wiki/builds/tier-list/) |

**Levelling / per-level upgrades (general rules)**
- Each spell levels up through level-up upgrade choices. Spell-specific "Unique" upgrades use fixed rarity tiers of **10% / 15% / 25% / 35%** (Common / Rare / Epic / Legendary) for stats such as Spell Damage, Spell Cooldown, Spell Lifetime and Spell Range. Which stats exist depends on the spell (e.g. Rune Burst and Cardinal Runes get Range instead of Size) — [wiki.gg Vengeful Sprout](https://thespellbrigade.wiki.gg/wiki/Vengeful_Sprout); [wiki.gg Impish Havoc](https://thespellbrigade.wiki.gg/wiki/Impish_Havoc); [wiki.gg Rune Burst](https://thespellbrigade.wiki.gg/wiki/Rune_Burst)
- The wiki.gg upgrade table marks Spell Range as available for Moonerang but not for Astral Orbs or Falling Stars — [wiki.gg Upgrades](https://thespellbrigade.wiki.gg/wiki/Upgrades)
- Levels go to at least **21**: there is an achievement for upgrading one spell to level 21, and getting any spell to level 21 in a run unlocks the option to cap spell count — [Steam guide 1.0](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916); [Steam: use only one spell](https://steamcommunity.com/app/2904000/discussions/0/659341126368916150/)
- A Steam thread titled "Is it a waste to upgrade beyond the final level?" exists, and a player there says an Epic upgrade on an already-maxed spell is still worth taking. So upgrades keep applying past a nominal "final level" — [Steam discussion](https://steamcommunity.com/app/2904000/discussions/0/599640708794613803/)

### Inferences
- "Element/school" is **not a property of a spell** in this game. A build planner should model element as a per-spell, per-run choice (two infusion slots), not as a fixed spell attribute.
- 21 Spell Quests plus starting/default spells plus the 1.2 start-unlocked spells is roughly consistent with the 26-spell list. Spells with no known quest (Aether Beam, Arcane Broadsword, Astral Orbs, Magic Missile, Moonerang's default availability, etc.) are probably default or signature-unlocked.
- "Chthonic Pull" (listed among the 13 new 1.2 augments) is probably an augment of Chthonic Charge, not a rename. One summary suggested a rename, which is less likely given the augment list. Likewise "Aura Beam" is probably an Aether Beam augment and "Baby Sprout" a Vengeful Sprout augment.

### Gaps
- **No base stats** (damage, cooldown, area, projectile count, duration) could be retrieved for any spell except Necro Whirl (lifetime 1.5 s, range 13), Falling Stars (4 instances), Moonerang (2 hits/cast) and Rune Burst (10-projectile cap). The full wiki.gg spell pages need to be read directly, in a browser or by another agent with access.
- The exact **max level** per spell and the full per-spell list of unique upgrade stats were not found.
- Spell Quest requirements for 14 spells are missing (only 7 of 21 found).
- The 1.0 to 1.2 changes to individual older spells (buffs/nerfs) were not retrieved. Only the additions above are confirmed.
- The early-access launch date and the update that added each EA spell (other than Swirl Sickle and Spear Barrage) are unconfirmed.

---

## 2. Elements and the status effects they apply

### Takeaway
There are **5 base elements**, applied as "Infusions": **Fire, Lightning, Acid, Ice, Dark**. Fire is available from the start and the others unlock later. Each applies one status (Afterburn, Sparks, Acid/Corrosion, Slow, Corruption). The numbers come from community testing and differ between older (EA) and newer (1.0) sources, especially for Acid.

### Cited Findings
- Infusions are "elemental abilities added to spells during a mission". Fire is the only starting option; Lightning, Acid, Ice and Dark unlock later — [wiki.gg Infusions](https://thespellbrigade.wiki.gg/wiki/Infusions)
- A Steam 1.0 guide's "Perfect Synergy" challenge draws from the same five elements (Fire, Lightning, Acid, Ice, Dark) — [Steam guide 1.0](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916)
- The in-game tooltip with exact effect text is shown by holding **Ctrl** while choosing an infusion (forum reply) — [Steam: Infusion Effects?](https://steamcommunity.com/app/2904000/discussions/0/4633734546101166250)

| Element | Status applied | Numbers (as reported) | Sources / conflicts |
|---|---|---|---|
| **Fire** | **Afterburn** (DoT) | ⅓ of the initial hit's damage (including crit) every 0.5 s, 3 ticks over 1.5 s; **does not stack** | [Steam guide: Infusion Elements and their Effects](https://steamcommunity.com/sharedfiles/filedetails/?id=3729529643); [wiki.gg Infusions](https://thespellbrigade.wiki.gg/wiki/Infusions) (same rate) |
| **Lightning** | **Sparks** (chain) | Sparks hit **2 nearby enemies** for an extra **50% of the initial hit's damage** (including crit) | [wiki.gg Infusions](https://thespellbrigade.wiki.gg/wiki/Infusions); [Steam guide 3729529643](https://steamcommunity.com/sharedfiles/filedetails/?id=3729529643) |
| **Acid** | **Acid** debuff (damage-taken amplifier; sometimes called Corrosion) | Old wiki.gg (EA): **+50% damage taken from all sources for 3 s**. Steam guide (around May 2026, 1.0): **+10% damage taken from all sources for 3 s; duration stacks** with repeat hits | **Conflict**: [wiki.gg Elements](https://thespellbrigade.wiki.gg/wiki/Elements) vs [Steam guide 3729529643](https://steamcommunity.com/sharedfiles/filedetails/?id=3729529643). Whisper of the House says Acid "lowers enemy resistance" ([Whisper](https://www.whisperofthehouse.com/the-spell-brigade/best-spells-elements)); thespellbrigade.wiki says Corrosion inflicts "Weakness", reducing the target's damage ([thespellbrigade.wiki elements](https://thespellbrigade.wiki/spells/elements/)) |
| **Ice** | **Slow** (to Freeze with Frost) | Slows enemies by **10% of damage dealt** (25% with Frost); stacks additively up to **72%**. Community: "gradually slows enemies until they freeze" | [Steam guide 3729529643](https://steamcommunity.com/sharedfiles/filedetails/?id=3729529643); [Steam: New elements](https://steamcommunity.com/app/2904000/discussions/0/599641518737780952/) |
| **Dark** | **Corruption** | No verified number. The guide author is "not 100% sure what it does". On *players* (friendly fire), full corruption reverses movement controls | [Steam guide 3729529643](https://steamcommunity.com/sharedfiles/filedetails/?id=3729529643); [Steam guide: Healing & You(r elements)](https://steamcommunity.com/sharedfiles/filedetails/?id=3725498881) |

**Element effects when a spell heals allies** (from Axelone3's Steam guide, tested with Friendly Fire off; healing scales with your damage stat)

| Element on a healing spell | Effect on healed ally |
|---|---|
| Fire | Adds a heal-over-time and a "fire aura" on the target, worth part of the original heal |
| Acid | **+50% all healing received**; green aura on the healed target |
| Lightning | Sparks/chain from hit targets can heal allies ("seems better than a normal spell heal hit") |
| Ice | No effect observed (the author expected move or cast speed) |
| Dark | No effect observed |

— [Steam guide: Healing & You(r elements)](https://steamcommunity.com/sharedfiles/filedetails/?id=3725498881)
- Negative status effects on allies seem to appear only when **Friendly Fire is on**. Ice and Dark negatives still apply even when the spell is set to heal — [Steam guide: Healing & You(r elements)](https://steamcommunity.com/sharedfiles/filedetails/?id=3725498881)

### Inferences
- The +50% to +10% drop for Acid probably reflects a balance change between late EA and 1.0. The planner should use the 1.0 value (10%, duration-stacking) and flag it for in-game verification.
- The thespellbrigade.wiki "All 7 Elements" framing probably counts some advanced infusions (its tier list mixes "Wildfire" and "Plasma" with base elements). No other source supports more than 5 base elements.

### Gaps
- Exact Corruption mechanics against enemies, and the Freeze threshold/duration for Ice, were not found.
- How the non-Fire elements are unlocked (meta-progression condition) was not found.
- Whether status numbers changed in 1.1/1.2 is unknown.

---

## 3. Spell combinations / synergies (incl. co-op)

### Takeaway
Combos happen **inside a single spell**. Each spell has two infusion slots (spell levels 7 and 14), and the pair of elements decides a named "Advanced Infusion" from a symmetric 5×5 table, giving **15 results** (5 same-element plus 10 mixed). Order doesn't matter. I found **no evidence of cross-player elemental reactions**, where one player's fire meets another player's ice to make a new effect. Co-op synergy comes from team-wide debuffs (Acid), healing allies with infused spells, friendly fire, and the "corrupted targets spread effects" infusions.

### Cited Findings
- First infusion when a spell reaches **level 7**, second at **level 14** (Moon Mage: levels **6 and 13**). "The order of which infusion you pick will not change or affect the resulting combo." — [wiki.gg Infusions](https://thespellbrigade.wiki.gg/wiki/Infusions); [Steam guide 1.0](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916)
- The wiki's table has Fire, Lightning, Acid, Ice and Dark as both rows and columns — [wiki.gg Infusions](https://thespellbrigade.wiki.gg/wiki/Infusions)
- The Steam 1.0 guide notes "a lot of the spell infusion names have changed" and lists the ten mixed combos as Plasma, Flux, Shadowbolt, Glint, Brimstone, Hellfire, Frostbite, Miasma, Blight, Wither — [Steam guide 1.0](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916)

**Full infusion combination table (current 1.0+ names)**

| Slot A | Slot B | Result (exact name) | Effect (as reported) | Sources / naming conflicts |
|---|---|---|---|---|
| Fire | Fire | **Wildfire** | Applies Afterburn; Afterburn **can crit** and scales with the player's critical damage (1.0 rework: crit ticks, so Crit Damage enchantments raise its DPS) | [wiki.gg Infusions](https://thespellbrigade.wiki.gg/wiki/Infusions); [thespellbrigade.wiki elements](https://thespellbrigade.wiki/spells/elements/) |
| Fire | Lightning | **Plasma** | Sparks jump between targets; each spark applies Afterburn, on top of the initial target | [wiki.gg Infusions](https://thespellbrigade.wiki.gg/wiki/Infusions) |
| Fire | Acid | **Brimstone** | Applies Afterburn + Acid/Corrosion; also damages nearby enemies for reduced damage | [wiki.gg Infusions](https://thespellbrigade.wiki.gg/wiki/Infusions); [Steam guide 1.0](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916) ("acid + fire … is now called Brimstone"). Older name "Corrosion" per [Shapes.inc](https://shapes.inc/fandom/the-spell-brigade/spells-and-elements) |
| Fire | Ice | **Frostbite** | Applies Afterburn + Slow; pushes targets back slightly | [wiki.gg Infusions](https://thespellbrigade.wiki.gg/wiki/Infusions) |
| Fire | Dark | **Hellfire** | Applies Corruption + Afterburn; targets corrupted by Hellfire **themselves apply Afterburn on hit** | [wiki.gg Infusions](https://thespellbrigade.wiki.gg/wiki/Infusions); [Steam guide 3729529643](https://steamcommunity.com/sharedfiles/filedetails/?id=3729529643) |
| Lightning | Lightning | **Thunder** | Sparks + a big Thunder strike on the initial target for extra damage ("bigger impact damage") | [wiki.gg Infusions](https://thespellbrigade.wiki.gg/wiki/Infusions); [Whisper of the House](https://www.whisperofthehouse.com/the-spell-brigade/best-spells-elements) |
| Lightning | Acid | **Flux** | Sparks + applies Acid | [wiki.gg Infusions](https://thespellbrigade.wiki.gg/wiki/Infusions) |
| Lightning | Ice | **Glint** | Sparks + applies Slow | [wiki.gg Infusions](https://thespellbrigade.wiki.gg/wiki/Infusions) |
| Lightning | Dark | **Shadowbolt** | Sparks; each spark also applies Corruption | [wiki.gg Infusions](https://thespellbrigade.wiki.gg/wiki/Infusions); [Steam guide 1.0](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916). Called "**Blackbolt**" in another guide (probably an older name) |
| Acid | Acid | **Corrosion** | wiki.gg: applies Acid + **Weakness**. Steam guide: +10% damage taken from all sources for 3 s; does not affect the initial hit | [wiki.gg Infusions](https://thespellbrigade.wiki.gg/wiki/Infusions); [Steam guide 3729529643](https://steamcommunity.com/sharedfiles/filedetails/?id=3729529643). Called "**Venom**" by [Shapes.inc](https://shapes.inc/fandom/the-spell-brigade/spells-and-elements) and [PixelNitro](https://pixelnitro.com/?p=4808) (probably old EA name) |
| Acid | Ice | **Miasma** | Applies Acid + Slow; enemies near the target are pushed back | [wiki.gg Infusions](https://thespellbrigade.wiki.gg/wiki/Infusions) |
| Acid | Dark | **Blight** | Applies Corruption + Acid; targets corrupted by Blight **themselves apply Acid on hit** | [wiki.gg Infusions](https://thespellbrigade.wiki.gg/wiki/Infusions) |
| Ice | Ice | **Frost** | Applies Slow with a small chance to **Freeze**; Slow becomes 25% of damage dealt (vs 10%) | [wiki.gg Infusions](https://thespellbrigade.wiki.gg/wiki/Infusions); [Steam guide 3729529643](https://steamcommunity.com/sharedfiles/filedetails/?id=3729529643). "**Deep Freeze**" per [PixelNitro](https://pixelnitro.com/?p=4808) (conflict/older name) |
| Ice | Dark | **Wither** | Applies Corruption + Slow; targets corrupted by Wither **themselves apply Slow on hit** | [wiki.gg Infusions](https://thespellbrigade.wiki.gg/wiki/Infusions) |
| Dark | Dark | **Void** | Applies Corruption; targets corrupted by Void **themselves apply Corruption on hit** | [wiki.gg Infusions](https://thespellbrigade.wiki.gg/wiki/Infusions); [Steam guide 3729529643](https://steamcommunity.com/sharedfiles/filedetails/?id=3729529643). "**Conversion**" per [PixelNitro](https://pixelnitro.com/?p=4808) (conflict/older name) |

- Patch note: "Fixed Flux, Glint and Shadowbolt Infusion's lightning bolt damage not scaling with crits in the initial hit" (exact version not retrieved) — [wiki.gg Infusions / patch quote via search](https://thespellbrigade.wiki.gg/wiki/Infusions); [Steam announcements](https://steamcommunity.com/app/2904000/announcements/)
- The developer's marketing describes figuring out "different spell combinations with your team" — [Gamespress press release](https://gamespress.com/Get-Ready-to-Cast-The-Spell-Brigade-is-to-Conjure-Excitement-at-Steam-)
- A BioGamer Girl review headline describes the game as "Powerful combos, perilous miscasts", which reflects friendly fire risk in co-op — [BioGamer Girl](http://www.biogamergirl.com/2025/12/the-spell-brigade-cooperative.html)
- Certain augmentations turn friendly fire into healing; the best known is **Healing Fire** — [thespellbrigade.wiki beginner's guide](https://thespellbrigade.wiki/guides/beginners-guide/)

### Inferences
- For a planner: model combos as `result = table[{slotA, slotB}]` (unordered), one per spell. Up to 4 spells times 1 result each gives 4 advanced infusions per player.
- Co-op "combos" in practice: (a) one player's Acid/Corrosion raises damage taken from **all sources**, so it amplifies teammates' damage; (b) Slow/Freeze and knockback infusions (Frostbite, Miasma) give team control; (c) healing-capable spells (Aether Beam, healing augments on Chthonic Charge and Phantom Blades, Healing Fire) gain element effects on allies (Acid +50% healing, Fire HoT, Lightning chain heals); (d) the "corrupted targets apply X on hit" infusions (Hellfire, Blight, Wither, Void) may let corrupted enemies spread effects into packs. Whether that triggers on hits from other players was not documented.
- Old EA names in some third-party guides (Venom, Deep Freeze, Conversion, Blackbolt, Corrosion-for-Fire+Acid) should be stored as aliases.

### Gaps
- No official or primary list of cross-player element reactions was found. Absence of evidence suggests they don't exist, but this is not confirmed.
- Exact numbers for advanced infusions (Thunder strike damage, Freeze chance, Weakness amount, Brimstone splash %, knockback strength) were not found.
- Whether 1.1/1.2 renamed or rebalanced any infusion is unknown.

---

## 4. Spell evolutions / fusions / ultimates

### Takeaway
Spells have **no separate "evolved" versions** (no Vampire-Survivors-style weapon evolutions) in any source found. The equivalents are (1) the **Advanced Infusion** created when two infusions occupy one spell (a same-element double "evolves into an Advanced Infusion"), and (2) **Ascension outfits** that swap a wizard's starting spell. No "ultimate" spell mechanic was found.

### Cited Findings
- "When a wizard doubles down on a single element for both Infusion slots, the spell evolves into an Advanced Infusion" — [thespellbrigade.wiki elements](https://thespellbrigade.wiki/spells/elements/)
- The second infusion at level 14 "result[s] in a strong combination of the infusions chosen" — [wiki.gg Infusions](https://thespellbrigade.wiki.gg/wiki/Infusions)
- A Steam discussion argues a dual-infused spell at level 14 is often worth more than pushing another spell further — [Steam discussion](https://steamcommunity.com/app/2904000/discussions/0/501685556737030048)
- First-ascension outfits and their alternate starting spells: Reginald → Bell March; Sun Mage → Chthonic Charge; Moon Mage → Scepter Mesh; Ludwig → Talon Slash; Aldric → Solar Pulse; Wizard King → Spear Barrage; Kavin → Necro Whirl; Maggie → Vengeful Sprout; Hatti → Swirl Sickle; Balthazar → Aether Beam; Star Mage → Cardinal Runes; Bryony → Arcane Broadsword; Campanelli → Hex Bomb; Pipwick → Aurora Wings; Knelly → Rocky Road — [wiki.gg Ascension](https://thespellbrigade.wiki.gg/wiki/Ascension); [tposegaming Ascension guide](https://tposegaming.com/spell-brigade-ascension/)

### Inferences
- A planner's "evolution" node should be the infusion pair, unlocked at spell level 7/14 (6/13 for Moon Mage).

### Gaps
- I found no confirmation either way of hidden fusions between two different spells. No source mentions any.

---

## 5. Spell-attached modifiers / augments

### Takeaway
**Augmentations** are spell-specific modifiers that change behaviour (extra projectiles, healing, pull, linking beams). They are earned from completed **Objectives** and from **chests**, and each spell has a limited set. As of 1.2, every new spell has 4, and 13 more were added for older spells. No complete augment list was retrievable.

### Cited Findings
- "Each successfully completed objective gives you a spell augmentation"; augments also come from chests on the map — [Fantasy Warden beginner's guide](https://fantasywarden.com/games/spell-brigade-beginners-guide); [Steam guide 1.0](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916)
- "There is a limited amount of augments for each spell" — [Steam discussion](https://steamcommunity.com/app/2904000/discussions/0/599640708794613803/)
- Rune Burst "can be augmented four times in a single mission — the maximum for any spell" — [thespellbrigade.wiki spells](https://thespellbrigade.wiki/spells/)
- 1.2: Loaded Dice, Tiny Tremors, Wicked Buzzsaw each "+ 4 Augmentations"; "13 New Augmentations for older Spells" (named examples: Aura Beam, Baby Sprout, Chthonic Pull, Counter Talon) — [Steam announcements](https://steamcommunity.com/app/2904000/announcements/)
- An EA balance pass (0.10.3.4046) included "spell and augmentation tweaks" — [Steam: EA Update 10 Patch 4](https://steamcommunity.com/games/2904000/announcements/detail/498325386812195213)

**Known augment names / effects**

| Spell | Augment (exact name if known) | Effect | Source |
|---|---|---|---|
| Rune Burst | (extra projectile) | Casts one additional projectile; max 6 upgrades, 10 total projectiles | [wiki.gg Rune Burst](https://thespellbrigade.wiki.gg/wiki/Rune_Burst) |
| Talon Slash | **Counter Talon** (added 1.2) | After taking damage, the next cast has 2 additional Talons | [Steam announcements](https://steamcommunity.com/app/2904000/announcements/) |
| Necro Whirl | **Pulling Whirl** | Pulls enemies toward the center | [wiki.gg Necro Whirl](https://thespellbrigade.wiki.gg/wiki/Necro_Whirl) |
| Scepter Mesh | **Scepter Link** | Scepters connect to the caster, forming a damaging beam | [Steam: Ascension skin spells](https://steamcommunity.com/app/2904000/discussions/0/838375062933398814/) |
| Chthonic Charge | (unnamed) ×3; possibly **Chthonic Pull** (1.2) | Charges heal allies / arrive in bursts / drift toward targets | [wiki.gg Chthonic Charge](https://thespellbrigade.wiki.gg/wiki/Chthonic_Charge) |
| Phantom Blades | (unnamed) ×4 | Extra blades / rear volley / blades heal teammates / burst firing | [wiki.gg Phantom Blades](https://thespellbrigade.wiki.gg/wiki/Phantom_Blades) |
| Vengeful Sprout | **Baby Sprout** (1.2) | effect not found | [Steam announcements](https://steamcommunity.com/app/2904000/announcements/) |
| Aether Beam (*inferred*) | **Aura Beam** (1.2) | effect not found | [Steam announcements](https://steamcommunity.com/app/2904000/announcements/) |
| (friendly-fire spells) | **Healing Fire** | Converts friendly fire into healing | [thespellbrigade.wiki beginner's guide](https://thespellbrigade.wiki/guides/beginners-guide/) |
| Astral Orbs / Moonerang | "Extra Projectile" | Extra simultaneous projectile/throw | [Whisper of the House builds](https://www.whisperofthehouse.com/the-spell-brigade/best-builds) |

**Global (non-spell-specific) upgrades that modify spells**, listed briefly for context and covered by other researchers: Titan's Fury (+5/10/15/20% base damage), Colossal Grace (Spell Size, reported as 0/12/15/18% by tier), Veil of Haste (cast speed / cooldown). Global stat upgrades apply to all spells — [wiki.gg Upgrades](https://thespellbrigade.wiki.gg/wiki/Upgrades)

### Gaps
- The full augment list per spell (names, effects, stack limits) was not retrievable. Each wiki.gg spell page appears to list them and should be scraped directly.
- How many augments a spell can hold per mission in general (only Rune Burst's "4, the max" is stated) is not documented.

---

## 6. Spell slots and how spells/upgrades are offered during a run

### Takeaway
A player starts with **1 spell** and can hold up to **4**. The 2nd to 4th spells are offered as a pick of 3 random spells at level milestones. Current patch notes put the **3rd spell at player level 13 and the 4th at level 20**; older guides say levels 5/15/25. Level-up upgrades have 4 rarities (Common/Rare/Epic/Legendary) weighted by Luck. Rerolls use tokens. Banish/Ban & Pin come from Masteries/enchantments (1.0).

### Cited Findings
- You start with one spell. Other spells are offered at certain level-up milestones as "a choice of three random spells"; older guides give levels 5, 15 and 25 — [Fantasy Warden](https://fantasywarden.com/?p=23699)
- Patch notes: "the 3rd Spell at Level 13, and your 4th Spell at Level 20". A new spell can come with an upgrade picked right away, and the 3rd and 4th spells start at spell levels 3 and 4 (exact patch version not retrieved) — [Steam all news](https://steamcommunity.com/app/2904000/allnews/)
- Max 4 spells: a run option limits spells to 1, 2, 3 or 4; it is unlocked by getting any spell to level 21 in one run. The "Solitary Focus" covenant (single spell) is reported to unlock by levelling one spell past 20 in a match, or by ascending three specific characters twice (conflicting reports) — [Steam: use only one spell](https://steamcommunity.com/app/2904000/discussions/0/659341126368916150/); [Steam: activate single spell](https://steamcommunity.com/app/2904000/discussions/0/838375696283763708/)
- Upgrade rarity base odds: **Common 71% / Rare 25% / Epic 4% / Legendary 0%**. At max **Luck 42**: **20.6% / 46.0% / 20.8% / 12.6%**. A player suggests about 24 Luck as a soft cap — [wiki.gg Upgrades](https://thespellbrigade.wiki.gg/wiki/Upgrades); [Steam: Best Element?](https://steamcommunity.com/app/2904000/discussions/0/603032812101078451/)
- **Rerolls**: reroll tokens are earned from Objectives and kills. The usual advice is to reroll only when all three offers are Common — [thespellbrigade.wiki beginner's guide](https://thespellbrigade.wiki/guides/beginners-guide/). A 488-day-old forum post says rerolls unlocked after 50k gold (EA meta-progression; probably outdated) — [Steam: Best Element?](https://steamcommunity.com/app/2904000/discussions/0/603032812101078451/)
- **Banish**: comes mainly through a Mastery ("banishing an upgrade gives you a new one immediately" in one Mastery version). 1.0 added **Ban & Pin** functionality among new enchantments/masteries — [Whisper of the House: Trial Covenants, Masteries & Ascension](https://www.whisperofthehouse.com/the-spell-brigade/trial-covenants-masteries-prestige); [vpesports 1.0](https://vpesports.com/featured-news/the-spell-brigade-exits-early-access); [Steam guide: All Enchantments / Masteries](https://steamcommunity.com/sharedfiles/filedetails/?id=3726023191)
- Spells unlocked through Spell Quests join the pool of spells you can pick when adding a new spell in a mission — [wiki.gg Quests](https://thespellbrigade.wiki.gg/wiki/Quests)
- 1.2 adds spells that are available from the start "giving early players some more options" — [Steam announcements](https://steamcommunity.com/app/2904000/announcements/)

### Inferences
- The level 13/20 thresholds are probably the 1.0-era rule and supersede the 5/15/25 numbers. The level of the 2nd spell under the new rule was not found.
- For a planner: slot 1 is the wizard's signature spell (or the ascension-outfit spell). Slots 2-4 are drawn from the unlocked pool. Each spell has 2 infusion slots, plus augments from objectives and chests.

### Gaps
- The player level at which the 2nd spell is offered (current rule) is unknown.
- How "Pin" works exactly, banish counts, reroll token amounts, and whether spell offers can be rerolled the same way as upgrades.
- Whether infusion offers (which elements are offered at 7/14) are random or freely chosen. Sources imply a choice, but the selection mechanics were not stated.

---

## 7. Community-recommended combinations and strongest spells

### Takeaway
The consensus is that **Lightning** is the safest and strongest element (S tier on several lists), with **Acid** best for bosses/elites and team amplification. **Falling Stars (Star Mage) with Lightning** is called the community's best build. Spell tiers differ widely between sites, and most of these sites are low-reliability SEO guides, so treat rankings as opinion.

### Cited Findings
**Element tiers**
- thespellbrigade.wiki (1.0): Lightning **S**; Acid and Wildfire **A**; Fire, Ice/Frost and Plasma **B**; Dark/Void **C** — [thespellbrigade.wiki elements](https://thespellbrigade.wiki/spells/elements/)
- Whisper of the House (updated 10 May 2026, v1.0): the best element is usually Lightning or Acid. Lightning is the safest first infusion; Acid is for bosses/elites. Advanced picks by problem: Plasma for burst, Flux for Lightning plus Acid utility, Corrosion for full Acid, Wildfire for Fire crit ticks, Thunder for double-Lightning impact, Ice when you need control — [Whisper of the House](https://www.whisperofthehouse.com/the-spell-brigade/best-spells-elements)
- Flux rated **B+**: a strong hybrid, but not the top pick — [guidexon](https://guidexon.com/the-spell-brigade-tier-list/)
- Disagreements: another guide calls Plasma the strongest all-round advanced element, and another says Ice with Lightning dominates — [PixelNitro best spells](https://pixelnitro.com/?p=4815); [insertcoins build guide](https://insertcoins.press/en/articles/the-spell-brigade-build-guide)
- Steam players favour Fire for damage plus healing; Acid/Poison and Flux for endless mode and co-op, plus an Ice or "White Lightning" support spell — [Steam: Best Infusion](https://steamcommunity.com/app/2904000/discussions/0/597399204164281582/); [Steam: What's the best infusion?](https://steamcommunity.com/app/2904000/discussions/0/834998803317739822/)

**Spell tiers (sources disagree)**

| Spell | Ratings seen |
|---|---|
| Falling Stars | S ("highest DPS ceiling; 4 simultaneous instances") — [thespellbrigade.wiki tier list](https://thespellbrigade.wiki/builds/tier-list/) |
| Aurora Wings | S — [ninewiki](https://ninewiki.com/tier-list/the-spell-brigade-tier-list-all-spells-and-elements/) |
| Cardinal Runes | S (both Tier Versus lists) — [Tier Versus](https://tierversus.com/game/the-spell-brigade-spells) |
| Resurrection Beam (unverified spell) | S — [thespellbrigade.wiki tier list](https://thespellbrigade.wiki/builds/tier-list/) |
| Moonerang | A — [thespellbrigade.wiki tier list](https://thespellbrigade.wiki/builds/tier-list/); [guidexon](https://guidexon.com/the-spell-brigade-tier-list/) |
| Talon Slash | A ([ninewiki](https://ninewiki.com/tier-list/the-spell-brigade-tier-list-all-spells-and-elements/), [guidexon](https://guidexon.com/the-spell-brigade-tier-list/)) vs B/C ([thespellbrigade.wiki tier list](https://thespellbrigade.wiki/builds/tier-list/)) |
| Rune Burst | A ([thespellbrigade.wiki](https://thespellbrigade.wiki/spells/)) vs C ([ninewiki](https://ninewiki.com/tier-list/the-spell-brigade-tier-list-all-spells-and-elements/), [guidexon](https://guidexon.com/the-spell-brigade-tier-list/)) |
| Astral Orbs | B ([ninewiki](https://ninewiki.com/tier-list/the-spell-brigade-tier-list-all-spells-and-elements/)) vs top pick with Acid ([guidexon](https://guidexon.com/the-spell-brigade-tier-list/)) |
| Arcane Broadsword | B — [ninewiki](https://ninewiki.com/tier-list/the-spell-brigade-tier-list-all-spells-and-elements/) |
| Chthonic Charge | B/C — [ninewiki](https://ninewiki.com/tier-list/the-spell-brigade-tier-list-all-spells-and-elements/); [Tier Versus](https://tierversus.com/game/the-spell-brigade-spells) |
| Solar Pulse | C, but "crits with Wildfire in 1.0"; also called "one of the most misleading spells", reliant on infusions — [ninewiki](https://ninewiki.com/tier-list/the-spell-brigade-tier-list-all-spells-and-elements/); [guidexon](https://guidexon.com/the-spell-brigade-tier-list/) |
| Phantom Blades | C — [ninewiki](https://ninewiki.com/tier-list/the-spell-brigade-tier-list-all-spells-and-elements/) |
| Vengeful Sprout | C — [ninewiki](https://ninewiki.com/tier-list/the-spell-brigade-tier-list-all-spells-and-elements/) |

**Recommended combinations**
- **Star Mage + Falling Stars + Lightning**: "the community's consensus best build" — [Whisper of the House builds](https://www.whisperofthehouse.com/the-spell-brigade/best-builds); [thespellbrigade.wiki builds](https://thespellbrigade.wiki/builds/)
- **Scepter Mesh + Lightning or Plasma** for co-op; Scepter Mesh and Solar Pulse pair with Spell Size mastery — [Whisper of the House builds](https://www.whisperofthehouse.com/the-spell-brigade/best-builds); [wiki.gg Ascension](https://thespellbrigade.wiki.gg/wiki/Ascension)
- **Moonerang + Acid at level 7**: two hits per cast apply Acid twice; pair with an Extra Projectile augment and Astral Orbs — [Whisper of the House builds](https://www.whisperofthehouse.com/the-spell-brigade/best-builds)
- **Solar Pulse aura** is the easiest build to reproduce — [Whisper of the House builds](https://www.whisperofthehouse.com/the-spell-brigade/best-builds)
- **Acid on repeat-hit spells** (Astral Orbs, Moonerang), or Flux/Corrosion, against bosses — [Whisper of the House](https://www.whisperofthehouse.com/the-spell-brigade/best-spells-elements); [guidexon](https://guidexon.com/the-spell-brigade-tier-list/)
- Arcane Broadsword is "excellent with Venom [= Corrosion] DoT" — [guidexon](https://guidexon.com/the-spell-brigade-tier-list/)

### Inferences
- Multi-hit spells (Astral Orbs, Moonerang, Rune Burst/Cardinal Runes, Falling Stars) benefit most from on-hit infusions such as Lightning Sparks and Acid. Afterburn doesn't stack, so it gains less from very high hit rates. That matches the Lightning/Acid preference.
- In co-op, one Acid/Corrosion user boosts the whole team's damage (the debuff applies to "all sources"), which makes it a natural support role.

### Gaps
- No tier list explicitly covers the 1.1/1.2 spells (Seismic Slam, Loaded Dice, Tiny Tremors, Wicked Buzzsaw).
- The tier-list sites (ninewiki, guidexon, tierversus, thespellbrigade.wiki, 2upskill, pixelnitro) are aggregator or SEO sites of uncertain authority. I found no developer-endorsed or data-driven ranking (e.g. pick-rate data).
