# The Spell Brigade: core gameplay, run structure, modes, maps, enemies and bosses

> **Research method and caveats (read first).** Research date: 2026-10-12. The egress proxy blocked direct page fetches for every relevant host (store.steampowered.com, steamcommunity.com, thespellbrigade.wiki.gg, thespellbrigade.wiki, metacritic, review sites all returned 403/ENOTFOUND). All findings below come from search-engine extractions of those pages, not from full reads. The search tool sometimes merged snippets from several results in one answer, so where a claim could come from more than one page I cite the most likely page and say so. Treat exact numbers (timers, HP, gold costs) as "reported by source X". Source quality varies a lot:
> - **More reliable:** Steam store page and official Steam announcements, SteamDB patch-note mirrors, the wiki.gg wiki (but many of its pages are 1–2 years old and date from early Early Access), and press reviews/news (Rogueliker, GameSpew, GameGrin, Gamestic, Wayside Shakedown, Games Press releases).
> - **Lower reliability:** thespellbrigade.wiki (not the wiki.gg one), PixelNitro, 2UpSkill, ninewiki, whisperofthehouse, fantasywarden, gamebrief, treyexgaming, tposegaming. Several of these look like SEO or AI-written guide farms. PixelNitro, for example, names a "Void Map" and "Fire Map" that do not exist in the game. I use them only for details nobody else covers, and I flag them when I do.
> - **Version labels:** the game was in Early Access ("EA Update N") from Sept 2024 to April 2026, then had 1.0 (with patches 1.0.x up to "Patch 10"), then 1.1 "Realm Sweep", then 1.2 (current as of Oct 2026).

## 1. Core gameplay loop (genre, perspective, aiming, run length, waves, objectives)

### Takeaway
The Spell Brigade is a top-down, 1–4 player online co-op "survivors-like" (horde survival) from the Belgian studio Bolt Blaster Games. You play wizards whose spells **fire automatically**, so you only steer movement. Friendly fire is on by default. A run takes place on one map ("Realm") at a chosen threat level. Over a timed run you kill hordes, pick up XP, level up and choose upgrades. You also do optional, time-limited map objectives that reward spell Augmentations, collect Relics, and finish by killing a boss, whose death wins the mission.

### Cited Findings
**Identity and release**
- 1–4 player online co-op survivors-like by Bolt Blaster Games, a Belgian studio. You team up as wizards against monster hordes, and "friendly fire is always on" per the store pitch. "Dying isn't a dead end": Revive Cores "(literally) blast yourself and your teammates back into action" — [Steam store page](https://store.steampowered.com/app/2904000/The_Spell_Brigade/); [games.gg](https://games.gg/the-spell-brigade/)
- Store/press tagline: "Survivors-like with ONLINE CO-OP for 1-4 players. Team up with your wizard friends to slay hordes of dark creatures. Complete team..." (truncated) — [channel3.gg listing](https://channel3.gg/the-spell-brigade)
- Early Access began **16 September 2024**. The studio reports **over 1 million copies sold in Early Access**. 1.0 launched **29 April 2026** on Steam and PS5 — [indiegame.com](https://indiegame.com/en/archives/24783); [VGChartz](https://www.vgchartz.com/article/467434/the-spell-brigade-launches-april-29-for-ps5-and-pc/); [Niche Gamer](https://nichegamer.com/the-spell-brigade-leaves-early-access-this-month/)
- 1.0 content: resource-stealing thieves, elite mini-boss variants, a new boss encounter, an **Ascension** system, a 15th playable wizard, and an original soundtrack by Austin Wintory "with tracks for every Realm and Boss Battle" — [Games Press 1.0 release](https://www.gamespress.com/Gather-Your-Squad-and-Join-the-Fray-The-Spell-Brigade-is-Out-Today); [GameGrin launch trailer news](https://www.gamegrin.com/news/watch-the-launch-trailer-for-the-spell-brigade)
- Press calls it "Magicka-inspired" (Magicka is a co-op wizard game known for chaotic friendly fire) — [Rogueliker 1.0 impressions](https://rogueliker.com/the-spell-brigade-review-impressions/)

**Aiming and auto-fire**
- Gamestic (1.0 review): "movement is limited to the analog sticks or directional keys, while your spells fire automatically, leaving you with no direct control over where your attacks land" — [Gamestic review](https://www.gamestic.nl/2026/04/28/review-the-spell-brigade/)
- ComicBuzz wished "there was at least the ability to aim and shoot at enemies rather than automatic firing" — [ComicBuzz review](https://comicbuzz.com/the-spell-brigade-review/)

**Loop elements**
- Objectives appear on the map as icons. They are **time-limited challenges**, for example "kill 50 enemies within 90 seconds in this zone" or "collect XP orbs from this area". Finishing one on time rewards **an Augmentation for one of your spells** — [Screen Hype review](https://www.screenhype.co.uk/the-spell-brigade-review-addictive-magical-chaos/); [Missi the Achievement Huntress review](https://www.missitheachievementhuntress.com/the-spell-brigade-review/)
- The wiki says there are **5 objectives per loop, the last one being the boss** — [wiki.gg Objectives](https://thespellbrigade.wiki.gg/wiki/Objectives)
- A mission's boss is "the last enemy you will encounter during a mission and defeating [it] will result in a victory" (Sol'phish page) — [wiki.gg Sol'phish](https://thespellbrigade.wiki.gg/wiki/Sol'phish)
- Map unlocks were historically tied to **surviving 12 minutes** on the previous map (see section 5). A guide reports Relics spawning at about **6:30, 13:00 and 19:30**, which suggests a full mission is roughly 20+ minutes — [wiki.gg Frozen Ancients](https://thespellbrigade.wiki.gg/wiki/Frozen_Ancients); relic timings from the [Steam relic discussion](https://steamcommunity.com/app/2904000/discussions/0/597393802249931355/)
- An achievement asks you to "survive a total of 400 minutes" (cumulative) — [thespellbrigade.wiki achievements](https://thespellbrigade.wiki/achievements/) (low-reliability site; also see [Steam Hunters achievements](https://steamhunters.com/apps/2904000/achievements))

**Reception (context)**
- Metacritic Metascore **69** from 6 critic reviews — [Metacritic](https://www.metacritic.com/game/the-spell-brigade/)
- Steam user score was reported as about **86% positive of ~5,066 English reviews** ("Very Positive") when the search ran — [Steam store page](https://store.steampowered.com/app/2904000/The_Spell_Brigade/) (search snippet; the figure changes over time)
- Critic split: GameSpew calls it "a fine survivors-like" that "fails to do anything to make it stand out in a very crowded genre". GameGrin gave it 8/10, "enjoyable both by yourself, friends, or completely random people". A critic quoted on Metacritic says "the power climb is locked behind a steep grind" — [GameSpew review](https://www.gamespew.com/2026/04/the-spell-brigade-review/); [GameGrin review](https://www.gamegrin.com/reviews/the-spell-brigade-review/); [Metacritic](https://www.metacritic.com/game/the-spell-brigade/)

#### Version timeline relevant to run/content mechanics
- **EA launch (16 Sep 2024):** Verdant Meadows, Frozen Ancients and Pyrestorm Pit were present early. Sol'phish was the only boss listed on the old wiki — [wiki.gg Enemies](https://thespellbrigade.wiki.gg/wiki/Enemies); [wiki.gg Pyrestorm Pit](https://thespellbrigade.wiki.gg/wiki/Pyrestorm_Pit)
- **v0.6 "Update 6" (late 2024):** "Frozen Ancients rework" — [thespellbrigade.wiki changelog](https://thespellbrigade.wiki/changelog/) (low-reliability site; snippet truncated)
- **Endless Mode** existed by mid-Dec 2024. The official TikTok "Exploring Endless Mode" video and a YouTube video titled "MAJOR Update! ENDLESS Mode Is Here!!" exist — [official TikTok](https://www.tiktok.com/@thespellbrigade/video/7449468997013228822); [YouTube](https://www.youtube.com/watch?v=uXMKwJhKHgw)
- **EA Update 0.7.2 (29 Jan 2025):** Endless Mode changes. You can now earn an Augmentation for defeating Sol'phish in Endless, and enemy spawning/density goes up after Cycle I — [SteamDB patch notes 0.7.2](https://steamdb.info/patchnotes/17171436/)
- **EA Update 8 (5 Mar 2025)** — [SteamDB patch notes Update 8](https://steamdb.info/patchnotes/17603290/) (contents not retrieved)
- **EA Update 9 "Dark Devotion" (Apr 2025):** added Stampeders (Verdant Meadows), Frostroot (Frozen Ancients) and Swarmlings (Pyrestorm Pit), and raised Endless difficulty — [Steam announcement EA Update 9](https://steamcommunity.com/games/2904000/announcements/detail/528717787215955183)
- **EA Update 10 (mid-2025)** had at least 4 patches — [Steam announcement EA Update 10 Patch 4](https://steamcommunity.com/games/2904000/announcements/detail/498325386812195213) (contents not retrieved)
- **EA Update 12 "The Astral Riftlands" (24 Sep 2025):** 4th realm, the "Light the Braziers" team objective, and enemies Stinky Crabs, Void Hoppers and Rift Sentinels — [Wayside Shakedown](https://waysideshakedown.com/2025/09/22/the-spell-brigade-astral-riftlands-update/); [Steam news EA Update 12](https://store.steampowered.com/news/app/2904000/view/520850995978174568)
- **EA Update 13 "Pumpkin Panic" (Oct 2025):** new spells, pumpkin cosmetics, "frightening foes". Described as the final content update before 1.0 — [Amerime Media](https://www.amerimemedia.com/post/the-spell-brigade-ushers-in-spooky-season-with-update-13-new-spells-pumpkin-fits-and-frightening); [PiratePR press release](https://press.piratepr.com/spooky-update-hits-the-spell-brigade-co-op-wizard-survivors-like-with-10-release-on-the-horizon)
- **1.0 (29 Apr 2026):** thieves (Mana Hoarder, Scroll Hoarder), Elder elites, new boss Mul'gath, Ascension and Trial Covenants, up to 4 Relics per run — [Games Press](https://www.gamespress.com/Gather-Your-Squad-and-Join-the-Fray-The-Spell-Brigade-is-Out-Today); [thespellbrigade.wiki changelog](https://thespellbrigade.wiki/changelog/)
- **1.0.x patches / open betas:** 1.0.4 and 1.0.6 open beta threads exist. Patch 1.0.5.17363 removed the need to ascend specific wizards to unlock Trial Covenants — [Steam 1.0.4 beta thread](https://steamcommunity.com/app/2904000/discussions/0/834998631657419539/); [Steam 1.0.6 beta thread](https://steamcommunity.com/app/2904000/discussions/0/565912359496979114/); [Steam guide "Outdated - All Trial Covenants (V1.0)"](https://steamcommunity.com/sharedfiles/filedetails/?id=3719250290)
- **"Patch 9" (1 Jul 2026):** scroll overhaul (7 new Scrolls, each unlocked by its own Quest), a Scroll HUD, and the Post-1.0 Roadmap announcement — [thespellbrigade.wiki changelog](https://thespellbrigade.wiki/changelog/)
- **"Patch 10":** dated 8 Jul 2026 by Veklar's Steam-news list, but the fan changelog first said none had shipped by 13 Jul and later listed 6 Aug 2026 — [Veklar](https://veklar.com/games/the-spell-brigade); [thespellbrigade.wiki](https://thespellbrigade.wiki/) (conflict)
- **1.1 "Realm Sweep":** each Realm "expanded with additional map variants that offer new level layouts", no new environment, and new wizard Eugenie (Seismic Slam spell). Date conflict: Veklar lists a "1.1 - Realm Sweep" item with scheduled maintenance on 21 Jul 2026 and "1.1 Patch 1" on 2 Sep 2026, while another summary dated Realm Sweep 2 Sep — [Rogueliker Realm Sweep](https://rogueliker.com/the-spell-brigade-realm-sweep/); [Veklar](https://veklar.com/games/the-spell-brigade)
- **1.2 (current):** the official X account bio reads "PS5 & Steam 1.2 OUT NOW". Build **1.2.0.20127 ("06-10-26")** fixed "killing the boss too fast in Endless Mode could break Level Ups" and a race condition in lobby creation that could stop players joining each other — [X @thespellbrigade](https://x.com/thespellbrigade); [Steam announcements](https://steamcommunity.com/app/2904000/announcements/)

### Inferences
- In terms of control the game sits close to Vampire Survivors: you move and position, and casting is automatic. Its "Magicka" flavour comes from co-op chaos and friendly fire, not from manual spell aiming.
- "06-10-26" is most likely **6 October 2026** (the European day-month format fits a Belgian studio, and 1.2 follows 1.1 from Jul–Sep 2026). If so, 1.2 is about one week old at research time.
- A mission follows a fixed arc: early horde phase, then about 4 objectives spread over the run (Relic chests after objectives 2 and 4), then a 5th "objective" which is the boss.

### Gaps
- Exact mission length and whether a boss spawns on a timer or only after objective 4 could not be confirmed. The 12-minute unlock condition and the 19:30 relic time suggest about 20 minutes plus the boss.
- I could not confirm whether spell targeting is nearest-enemy, random, or tied to facing/movement direction.
- The full 1.2 patch notes (beyond the two fixes above) were not retrievable.

## 2. How a run begins and ends (level-ups, XP, upgrades, shops, chests, events, win/loss, revives)

### Takeaway
You pick a wizard (each starts with one spell), a Realm and a Threat Level (plus optional Covenants), then drop into the map. Enemies drop XP orbs. Each level-up offers 3 choices (stats, spell upgrades, elemental infusions), and set levels offer a new spell. Timed map objectives give Augmentations, Relic chests appear at set points, and the boss kill ends the mission in victory (or continues it in Endless). A run is lost when the whole team is dead with no Revive Cores left. Gold and wizard rank carry over between runs as meta-progression. I found no evidence of an in-run shop or merchant.

### Cited Findings
**Start and build-up**
- "You have one starting spell, and other ones are offered to you on certain level-up milestones. **Levels 5, 15, and 25** give you a choice of three random spells from which you have to take one" — [Fantasy Warden beginner's guide](https://fantasywarden.com/games/spell-brigade-beginners-guide) / [Steam guide "The Spell Brigade [1.0]"](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916) (one of these two; low-to-medium reliability)
- "Every time you collect enough XP orbs (dropped by enemies), you level up. Each level-up presents **three upgrade choices**", including stat bonuses, spell upgrades, and **elemental infusions at levels 7 and 14** — [thespellbrigade.wiki beginner's guide](https://thespellbrigade.wiki/guides/beginners-guide/) (low-reliability site)

**Objectives and Augmentations**
- Objectives are optional and timed. Completing them on time gives a spell Augmentation — [Screen Hype](https://www.screenhype.co.uk/the-spell-brigade-review-addictive-magical-chaos/); [Missi review](https://www.missitheachievementhuntress.com/the-spell-brigade-review/)
- Opinions on their value differ. One guide claims one Augmentation "often exceeds ten regular level-up upgrades combined". A review notes they are optional and "you could theoretically ignore these altogether" — [thespellbrigade.wiki beginner's guide](https://thespellbrigade.wiki/guides/beginners-guide/); [Missi review](https://www.missitheachievementhuntress.com/the-spell-brigade-review/)
- The developers said they wanted "to expand on the Augmentations, giving older spells some new stuff as well" — [Steam announcements](https://steamcommunity.com/app/2904000/announcements/)

**Relics (chest rewards)**
- Relics spawn about **6:30, 13:00, 19:30**. Another account says Relic chests appear after the **2nd and 4th objectives, then at the boss**. A wiki line quoted in the thread mentions "three Relic Chests throughout the map" — [Steam discussion "max number of relics"](https://steamcommunity.com/app/2904000/discussions/0/597393802249931355/); [Screen Hype](https://www.screenhype.co.uk/the-spell-brigade-review-addictive-magical-chaos/)
- **Changed in 1.0:** "you can have **4 relics** in a run, the last one is not tied with spawn timer" — [Steam discussion "max number of relics"](https://steamcommunity.com/app/2904000/discussions/0/597393802249931355/)

**Scrolls and thieves**
- Scrolls are a run-affecting item system. Patch 9 (Jul 2026) reworked and removed some scrolls, added 7 new ones (each unlocked by a Quest, e.g. "Lucky Scroll", "Thick Skin") and added a Scroll HUD — [thespellbrigade.wiki changelog](https://thespellbrigade.wiki/changelog/)
- 1.0 added thieves that steal resources: the **Mana Hoarder** and **Scroll Hoarder**. Patch notes mention Scroll Hoarders have a healing effect and fixed them being pushed into walls — [Games Press](https://www.gamespress.com/Gather-Your-Squad-and-Join-the-Fray-The-Spell-Brigade-is-Out-Today); [Steam announcements](https://steamcommunity.com/app/2904000/announcements/)

**End of run and meta-progression**
- Victory comes from killing the mission boss — [wiki.gg Sol'phish](https://thespellbrigade.wiki.gg/wiki/Sol'phish)
- In Endless, killing the boss restarts the level (see section 8)
- After the run, gold and rank progress count. A forum post says "there is no difficulty multiplier, the only thing [that] matters is **mana collected or level**". A guide says base difficulty gives no bonus ascension progress or extra gold, so "keep your gold farming runs on Easy" — [Steam discussion "Ascending your wizard?"](https://steamcommunity.com/app/2904000/discussions/0/838375062933398815/); [tposegaming Ascension guide](https://tposegaming.com/spell-brigade-ascension/)

**Death and revives**
- Revive Cores let you "blast yourself and your teammates back into action" — [Steam store page](https://store.steampowered.com/app/2904000/The_Spell_Brigade/)
- While dead "you cannot collect xp". XP others collect "can affect you while dead" — [Steam discussion (via GameBrief summary)](https://steamcommunity.com/app/2904000/discussions/0/592889031515214595/)
- One guide says solo players "automatically revive after a few seconds once they're down". This is unverified and may be confused with Revive Cores — [whisperofthehouse solo guide](https://www.whisperofthehouse.com/the-spell-brigade/solo-guide) (low reliability)
- Players report you can "lose a life for being afk" in long runs — [Steam discussion "Endless mode is not interesting"](https://steamcommunity.com/app/2904000/discussions/0/595134792309201113/)

### Inferences
- "Mana" seems to be the run's collectable XP/currency resource. The "Mana Hoarder" thief and the "mana collected" reward basis both point that way. Thieves therefore threaten your level-up pace and end-of-run gold, and Scroll Hoarders threaten your scrolls.
- "Lose a life" plus Revive Cores suggests a shared or per-player life stock that Revive Cores add to.

### Gaps
- No source describes an in-run shop or merchant, random events, or extraction. These systems may simply not exist; the absence is not confirmed.
- The exact Revive Core mechanics (how many at start, where they come from, the explosion's damage and radius) were not found.
- The exact loss condition (all players dead with no cores left) is inferred, not stated by any source.

## 3. Co-op specifics (player count, sharing, friendly fire, scaling, solo, online)

### Takeaway
Online co-op supports up to 4 players, with PS5–Steam crossplay since 1.0 (29 Apr 2026). Friendly fire is on by default and can only be turned off through a Covenant (modifier), not a settings toggle. XP appears to be shared: others' pickups affect you, but dead players can't pick up XP. Difficulty scales with squad size, and boss HP in particular has drawn co-op complaints. There is a lobby system with limited matchmaking features, and 1.2 fixed a lobby-join race condition.

### Cited Findings
- 1–4 players, online co-op — [Steam store page](https://store.steampowered.com/app/2904000/The_Spell_Brigade/); [TechGamingReport](https://www.techgamingreport.com/the-spell-brigade-launches-on-ps5-and-steam-with-cross-platform-co-op/)
- Crossplay between PS5 and Steam "is live from launch" (1.0, 29 Apr 2026). It also covers Steam Deck — [GameDaily](https://gamedaily.com/games/the-spell-brigade-launches-ps5-steam-million-players); [TechGamingReport](https://www.techgamingreport.com/the-spell-brigade-launches-worldwide-with-ps5-debut-and-crossplay-support/); [CrossWatch crossplay](https://www.crosswatch.info/games/entities/the-spell-brigade/cross-play)
- **Friendly fire:** GameSpew says it is "turned on by default" and "can only be turned off as a Covenant", and argues it should be a settings toggle. games.gg calls it "always on" (conflict, likely different versions or wording) — [GameSpew review](https://www.gamespew.com/2026/04/the-spell-brigade-review/); [games.gg](https://games.gg/the-spell-brigade/)
- **Scaling:** games.gg lists "Synergy scaling based on squad size". In one co-op run, Krog'wa had far more HP than Sol'phish and the fight lasted over 7 minutes. The poster suspected a co-op scaling issue (unconfirmed) — [games.gg](https://games.gg/the-spell-brigade/); [Steam discussion "Kragwa health vs Sol'phish"](https://steamcommunity.com/app/2904000/discussions/0/601919346587134662/)
- **XP sharing:** "while you are dead you cannot collect xp… Xp that OTHERS collect can affect you while dead however" — [Steam discussion](https://steamcommunity.com/app/2904000/discussions/0/592889031515214595/). A separate thread "Experience Power Ups in multiplayer?" exists but its contents were not retrieved — [Steam discussion](https://steamcommunity.com/app/2904000/discussions/0/595134572710111089/)
- **Revive tip:** one player's Core can pull a downed teammate back immediately, and a guide recommends one player hold the group's spare Cores — [GameBrief tips](https://www.gamebrief.net/blog/the-spell-brigade-tips-guide-2026) (low reliability)
- **Solo:** "Solo play is fully supported… any map, wizard or difficulty alone". The trade-off is losing teammate revives and role coverage. Steam reviewers say the solo early game is slow and that the game shines in co-op — [whisperofthehouse solo guide](https://www.whisperofthehouse.com/the-spell-brigade/solo-guide); [Steam store page reviews](https://store.steampowered.com/app/2904000/The_Spell_Brigade/)
- **Lobbies/matchmaking:** a player asked for a joinable-games list. The developer replied (pre-1.0) that they "will be expanding on [their] matchmaking options in the future". GameGrin mentions playing with "completely random people" — [Steam discussion](https://steamcommunity.com/app/2904000/discussions/0/599640708794566091); [GameGrin review](https://www.gamegrin.com/reviews/the-spell-brigade-review/)
- 1.2.0.20127 fixed "a racing condition during lobby creation that could prevent players from joining each other" — [Steam announcements](https://steamcommunity.com/app/2904000/announcements/)
- In-game **VOIP** exists: a Steam news post is titled "[VOIP] Disconnecting and Reconnecting the headset will…" — [Steam news feed](https://store.steampowered.com/news/posts/?feed=steam_community_announcements&enddate=1738159414)
- A **ping** system exists. Patch notes list "7 enemy types now pingable: Elder Shaman, Elder Bloat Crab, Elder Teethy Worm, Broodmaw, Stampeders, Frostroot, Baby Manta" — [thespellbrigade.wiki changelog](https://thespellbrigade.wiki/changelog/); [Steam announcements](https://steamcommunity.com/app/2904000/announcements/)
- Team objectives are built for coordination. "Herd the Mana Beasts" is "a non-combat, coordination-heavy task" and "Light the Braziers" asks you to "find the correct combination of braziers" — [Screen Hype](https://www.screenhype.co.uk/the-spell-brigade-review-addictive-magical-chaos/); [Steam guide [1.0]](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916)
- PS5 performance caveat: one reviewer saw slowdown in busy moments on console — [Rogueliker 1.0 impressions](https://rogueliker.com/the-spell-brigade-review-impressions/)

### Inferences
- XP looks pooled at team level (others' pickups level you up), and upgrades are chosen per player. That fits the genre norm, but no source states outright that each player picks their own level-up cards.
- Friendly fire plus auto-fire means positioning relative to teammates matters. Players spread out so area spells don't hit allies.

### Gaps
- Whether loot (Relics, Augmentations, gold) is per-player or shared was not confirmed.
- Exact HP and spawn scaling per extra player is not documented.
- Whether public matchmaking (quick-join with strangers) exists alongside friend invites and lobby codes was not confirmed in current (1.2) form.

## 4. Controls and core actions

### Takeaway
Players control **movement only**, and spells cast automatically. No source describes a manual dash/dodge button or an ultimate ability in the current game. "Dodge" shows up as a stat (dodge chance), with a reported soft cap. Controllers are fully supported (XInput, DualSense haptics and adaptive triggers) and the developers recommend one. Rebindable controls were still on the post-1.0 roadmap in July 2026.

### Cited Findings
- Spells fire automatically. Movement is via analog stick or direction keys — [Gamestic review](https://www.gamestic.nl/2026/04/28/review-the-spell-brigade/); [ComicBuzz review](https://comicbuzz.com/the-spell-brigade-review/)
- Dodge is a stat with diminishing offers. "There is a soft cap in place where the chance of receiving a dodge upgrade decreases once you reach a certain percentage", about 75% (user-reported) — [Steam discussion "Dodge cap?"](https://steamcommunity.com/app/2904000/discussions/0/4697908845438737713/); [Steam discussion "Caps for Crit, Luck, and Dodge?"](https://steamcommunity.com/app/2904000/discussions/0/573792389465141072/)
- Controller: XInput controllers, DualSense haptics and adaptive triggers — [PCGamingWiki](https://www.pcgamingwiki.com/wiki/The_Spell_Brigade)
- Developer: "perfectly playable with mouse & keyboard, but we recommend using a controller for the best experience" — [Steam discussion "Controller?"](https://steamcommunity.com/app/2904000/discussions/0/6610810473930762399/)
- Post-1.0 roadmap (Jul 2026) lists "rebindable controls" as planned, along with highscores and a logbook — [thespellbrigade.wiki changelog](https://thespellbrigade.wiki/changelog/)
- A cloud-gaming/mobile streaming guide suggests mapping Space to "dash, dodge, or quick movement if mapped". This is generic and not evidence of a native dash — [StarDesk mobile guide](https://www.stardesk.net/blog/the-spell-brigade-mobile.html) (unreliable for mechanics)
- Ping is an action (see section 3) — [Steam announcements](https://steamcommunity.com/app/2904000/announcements/)

### Inferences
- The core skill is pathing: kiting hordes, dodging boss telegraphs and hazards, standing in objective zones, and spacing from teammates because of friendly fire.

### Gaps
- I found no authoritative control list. Whether there is any active ability, dash, or interact button (e.g. to light braziers or use a Revive Core) is unconfirmed. The Steam store page and in-game control screen could not be read.

## 5. Maps / Realms (names, features, hazards, unlocks)

### Takeaway
There are four Realms: **Verdant Meadows** (starter, no hazards), **Frozen Ancients** (geysers, ice, frost branches), **Pyrestorm Pit** (fire tornadoes, lava), and **Astral Riftlands** (rivers and portals, added Sep 2025). Each Realm has its own unique enemy, and from 1.0 the first three have their own boss. Realms unlock in sequence, and each starts at only the Moderate threat level. 1.1 "Realm Sweep" (Jul–Sep 2026) added alternative map layouts (variants) per Realm. A new 5th Realm is on the roadmap but not released as of Oct 2026.

### Cited Findings
**Verdant Meadows**
- "The first and only map available to the player upon starting the game". It has no hazards, unlike Frozen Ancients and Pyrestorm Pit — [wiki.gg Verdant Meadows](https://thespellbrigade.wiki.gg/wiki/Verdant_Meadows)
- Unique enemy: the **Gnasher**, which "burrows underneath the surface and travels towards the player while being mostly invulnerable". A later patch note says "Gnashers can now be frozen" — [wiki.gg Verdant Meadows](https://thespellbrigade.wiki.gg/wiki/Verdant_Meadows); [Steam announcements](https://steamcommunity.com/app/2904000/announcements/)
- Rivers exist here too. The "Surf's Up" achievement involves fighting Sol'phish in a river as the Star Mage — [GameFAQs PS5 achievements](https://gamefaqs.gamespot.com/ps5/638324-the-spell-brigade/achievements)
- Boss: **Sol'phish** (see section 7) — [thespellbrigade.wiki beginner's guide](https://thespellbrigade.wiki/guides/beginners-guide/)
- Added in EA Update 9: Stampeders — [Steam EA Update 9](https://steamcommunity.com/games/2904000/announcements/detail/528717787215955183)

**Frozen Ancients**
- Unlocks "after surviving the Verdant Meadows for **12 minutes**". Hazards: **sulfuric geysers, ice patches, frost branches**. Unique enemy: **Sneaky Bug** — [wiki.gg Frozen Ancients](https://thespellbrigade.wiki.gg/wiki/Frozen_Ancients)
- Ice patches slow movement — [thespellbrigade.wiki beginner's guide](https://thespellbrigade.wiki/guides/beginners-guide/)
- Boss: **Krog'wa, the Bloated One**. The achievement reads "Boss of Frozen Ancients. Defeat on any Threat Level" — [GameFAQs PC achievements](https://gamefaqs.gamespot.com/pc/462264-the-spell-brigade/achievements)
- Reworked in v0.6 (late 2024). Frostroot added in EA Update 9 — [thespellbrigade.wiki changelog](https://thespellbrigade.wiki/changelog/); [Steam EA Update 9](https://steamcommunity.com/games/2904000/announcements/detail/528717787215955183)

**Pyrestorm Pit**
- "Third map of the game". Unlocks by surviving Frozen Ancients for 12 minutes. Hazards: **searing tornadoes and lava pits**. Unique enemy: **Flying Manta**, which takes no damage from the lava — [wiki.gg Pyrestorm Pit](https://thespellbrigade.wiki.gg/wiki/Pyrestorm_Pit)
- Boss (1.0): **Mul'gath, the Twisted One** — [thespellbrigade.wiki beginner's guide](https://thespellbrigade.wiki/guides/beginners-guide/); [thespellbrigade.wiki changelog](https://thespellbrigade.wiki/changelog/)
- Swarmlings added in EA Update 9. "Baby Manta" also appears in the pingable list — [Steam EA Update 9](https://steamcommunity.com/games/2904000/announcements/detail/528717787215955183); [Steam announcements](https://steamcommunity.com/app/2904000/announcements/)

**Astral Riftlands**
- Added in **EA Update 12 (24 Sep 2025)**, the 4th realm. It brought the **Light the Braziers** team objective and enemies **Stinky Crabs, Void Hoppers, Rift Sentinels** — [Wayside Shakedown](https://waysideshakedown.com/2025/09/22/the-spell-brigade-astral-riftlands-update/); [Saving Content](https://www.savingcontent.com/2025/09/24/the-astral-riftlands-update-lands-for-4-player-wizard-survivors-like-the-spell-brigade/)
- "Rivers in the Astral Riftlands have been reworked so you can move against the current", and portals appear during runs — [Rogueliker Update 12](https://rogueliker.com/the-spell-brigade-update-12/)
- Unlock: "Complete a mission in the Pyrestorm Pit. Unlocks the Astral Riftlands" (achievement text). A Steam thread says it unlocks via Challenges by surviving 12 minutes in Pyrestorm Pit — [thespellbrigade.wiki achievements](https://thespellbrigade.wiki/achievements/); [Steam discussion "Astral Riftlands - new Realm locked?"](https://steamcommunity.com/app/2904000/discussions/0/603042323028337908/)
- Also called "Astral Rifts" in Trial Covenant unlock text ("beat Astral Rifts on hardcore at 9+ devotion") — [treyexgaming Trial Covenants guide](https://www.treyexgaming.com/the-spell-brigade-trial-covenants-guide/)

**Threat-level gating, variants, roadmap**
- "Each map starts with only the moderate threat level, and you must beat every map with a certain threat level to unlock the next one" — [Steam guide "The Spell Brigade [1.0]"](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916)
- 1.1 Realm Sweep: "each Realm has been expanded with additional map variants that offer new level layouts". Rogueliker notes "there is no new environment to play in" — [Rogueliker Realm Sweep](https://rogueliker.com/the-spell-brigade-realm-sweep/)
- Post-1.0 roadmap (Jul 2026): a new realm, spells, scrolls, map variants, rebindable controls, highscores and a logbook. "No release dates have been confirmed" — [thespellbrigade.wiki changelog](https://thespellbrigade.wiki/changelog/)

### Inferences
- Unlock rules changed over time. In EA, surviving 12 minutes unlocked the next map. By 1.0 the achievement wording is "complete a mission", and threat levels gate separately. Both may now apply (Challenges-based unlocks).
- The planned "map variants" roadmap item was probably delivered by 1.1 Realm Sweep. The "new realm" item was still outstanding as of Oct 2026.

### Gaps
- Which boss (if any fixed one) guards Astral Riftlands is not documented. It may draw from the boss pool (see conflict in section 7).
- The names and features of the 1.1 map variants were not found.
- Whether 1.2 added content (e.g. a 5th realm) is unknown. The only 1.2 notes found are bug fixes.

## 6. Enemies (types, factions, elites, behaviors, scaling)

### Takeaway
Enemies are mostly grotesque "dark creatures": crabs, worms, shamans, spitters and so on. There is a shared basic roster, one or more enemies unique to each Realm, and enemies added by updates. 1.0 added **Elder** elite/mini-boss variants and **thief** enemies that steal resources, and special **Golden** crab variants serve as objective targets. Difficulty scales with threat level (density, damage, boss HP) and in Endless with each cycle.

### Cited Findings
**Basic roster (old wiki, about Sept 2024)**
- 18 enemies "counting the different variants of Flesh Crab and Baby Teethy Worms". Basic enemies include **Flesh Crab, Spitter, Shield Crab, Crabladon, Bloat Crab, Shaman, Teethy Worm**. Six enemies are unique to specific maps. Sol'phish was the only listed boss at the time — [wiki.gg Enemies](https://thespellbrigade.wiki.gg/wiki/Enemies)

**Map-unique and update-added enemies**
- Verdant Meadows: Gnasher (burrowing, mostly invulnerable). Frozen Ancients: Sneaky Bug. Pyrestorm Pit: Flying Manta (lava-immune) — [wiki.gg Verdant Meadows](https://thespellbrigade.wiki.gg/wiki/Verdant_Meadows); [wiki.gg Frozen Ancients](https://thespellbrigade.wiki.gg/wiki/Frozen_Ancients); [wiki.gg Pyrestorm Pit](https://thespellbrigade.wiki.gg/wiki/Pyrestorm_Pit)
- EA Update 9 (Apr 2025): Stampeders (VM), Frostroot (FA), Swarmlings (PP) — [Steam EA Update 9](https://steamcommunity.com/games/2904000/announcements/detail/528717787215955183)
- EA Update 12 (Sep 2025): Stinky Crabs, Void Hoppers, Rift Sentinels (Astral Riftlands) — [Wayside Shakedown](https://waysideshakedown.com/2025/09/22/the-spell-brigade-astral-riftlands-update/)
- EA Update 13 (Oct 2025) advertised "frightening foes" (Halloween-themed) — [Amerime Media](https://www.amerimemedia.com/post/the-spell-brigade-ushers-in-spooky-season-with-update-13-new-spells-pumpkin-fits-and-frightening)
- Broodmaw is another named enemy (in the pingable list) — [Steam announcements](https://steamcommunity.com/app/2904000/announcements/)

**Elites and thieves (1.0)**
- Elites: **Elder Bloat Crab, Elder Teethy Worm, Elder Shaman**, described as elite variants that work as mini-bosses — [thespellbrigade.wiki changelog](https://thespellbrigade.wiki/changelog/); [Games Press](https://www.gamespress.com/Gather-Your-Squad-and-Join-the-Fray-The-Spell-Brigade-is-Out-Today)
- Thieves: **Mana Hoarder** and **Scroll Hoarder**. Scroll Hoarders have a healing effect, and a patch fixed them getting pushed into obstacles — [thespellbrigade.wiki changelog](https://thespellbrigade.wiki/changelog/); [Steam announcements](https://steamcommunity.com/app/2904000/announcements/)

**Objective targets**
- Golden Crab objective: "chase and kill the small crab before it escapes". New variants are the **Golden Crablodon** and a **Golden Mothercrab** "that spawns a bunch of tiny Crabs" — [Steam announcements](https://steamcommunity.com/app/2904000/announcements/); [wiki.gg Objectives](https://thespellbrigade.wiki.gg/wiki/Objectives)
- Mana Beasts (herding objective) "have a chance of falling in love with you and will follow you unconditionally" (patch note) — [Steam announcements](https://steamcommunity.com/app/2904000/announcements/)

**Scaling**
- Severe and Hardcore "greatly increase enemy density, damage, and boss health" — [whisperofthehouse solo guide](https://www.whisperofthehouse.com/the-spell-brigade/solo-guide) (low reliability)
- Endless: each cycle increases enemy damage/health. 0.7.2 raised spawning/density after Cycle I, and Update 9 raised Endless difficulty — [Creeping for Scale Models let's play](https://creepingforscalemodels.com/2025/06/01/lets-play-update-the-spell-brigade/); [SteamDB 0.7.2](https://steamdb.info/patchnotes/17171436/); [Steam EA Update 9](https://steamcommunity.com/games/2904000/announcements/detail/528717787215955183)
- Dark element: enemies, and even bosses "like Sol'phish and Krog'wa", "can fall to the darkness if your build is strong enough". This means conversion to your side (from an EA 2025 update; Update 9 is titled "Dark Devotion") — [Steam announcements](https://steamcommunity.com/app/2904000/announcements/); [Steam EA Update 9](https://steamcommunity.com/games/2904000/announcements/detail/528717787215955183)

### Inferences
- Enemies form one "dark creature/crab" faction with Realm flavours rather than distinct factions.
- Elder elites likely appear as spikes mid-run. Their inclusion in the ping list suggests they are threats worth calling out to teammates.

### Gaps
- No current (1.0+) full enemy list with counts was retrievable. The wiki.gg enemy page is about two years old.
- Per-enemy attack behaviours (beyond Gnasher, Flying Manta, Golden Crab and Mothercrab) were not found.
- The exact time-based spawn scaling inside a normal mission is undocumented.

## 7. Bosses (names, location, mechanics, tips)

### Takeaway
There are three named bosses as of 1.0–1.2. **Sol'phish, the Long One** (Verdant Meadows, the original EA boss) has a summoning-circle phase, speeds up over time, and has a stagger window. **Krog'wa, the Bloated One** (Frozen Ancients, added during EA) uses suck-and-blow pull/push. **Mul'gath, the Twisted One** (Pyrestorm Pit, new in 1.0) punishes narrow damage and poor repositioning. Sources conflict on whether bosses are fixed per Realm or rolled from a pool.

### Cited Findings
**Sol'phish, "the Long One"**
- Last enemy of a mission; defeating it means victory — [wiki.gg Sol'phish](https://thespellbrigade.wiki.gg/wiki/Sol'phish)
- Summon phase: "every enemy on the map will start making their way towards a big red summoning circle". Stepping on the circle "will deal 100 damage to the player" — [wiki.gg Sol'phish](https://thespellbrigade.wiki.gg/wiki/Sol'phish)
- Speeds up the longer the fight lasts. "Having an ice infusion on a spell will eventually be a necessity" — [wiki.gg Sol'phish](https://thespellbrigade.wiki.gg/wiki/Sol'phish)
- During a stagger window it takes extra damage. "If you're strong enough to keep the hordes… at bay during this time you can quite easily take off a big chunk of health" — [wiki.gg Sol'phish](https://thespellbrigade.wiki.gg/wiki/Sol'phish)
- "Surf's Up" achievement: fight Sol'phish in a river as Star Mage ("simply lure him toward a river and hit him there") — [GameFAQs PS5 achievements](https://gamefaqs.gamespot.com/ps5/638324-the-spell-brigade/achievements); [whisperofthehouse achievements guide](https://www.whisperofthehouse.com/the-spell-brigade/achievements-guide)
- A 2026 guide advises not focusing it directly and using Dark builds that convert small enemies to damage it (low-reliability source) — [PixelNitro walkthrough](https://pixelnitro.com/the-spell-brigade-walkthrough-2026-ultimate-guide-to-best-builds-spells-and-boss-strategies/)
- In Endless, a player reported about 4.7 million HP in single player. Others say round-2 bosses became "almost impossible" after a monster-HP patch — [Steam discussion "Balance, Progression, and boss Hp tweaks have ruined Endless mode"](https://steamcommunity.com/app/2904000/discussions/0/597398453436331359/)
- Sources disagree on pronoun ("him" vs "her") — [wiki.gg Sol'phish](https://thespellbrigade.wiki.gg/wiki/Sol'phish); [GameFAQs PS5 achievements](https://gamefaqs.gamespot.com/ps5/638324-the-spell-brigade/achievements)

**Krog'wa, "the Bloated One"**
- "Boss of Frozen Ancients. Defeat on any Threat Level". The kill unlocks the "Toad Trampler" title — [GameFAQs PC achievements](https://gamefaqs.gamespot.com/pc/462264-the-spell-brigade/achievements)
- Added during EA as "the new boss". It has a **suck-and-blow** mechanic (pulls players in, then pushes them away) that makes it hard to dodge explosive enemies, which aren't affected by the push/pull — [Steam discussion "The new boss sucks and blows…"](https://steamcommunity.com/app/2904000/discussions/0/597405723931074452/)
- Counter-tips from players: take spells that clear space around you; move in 360° rather than only toward or away; "if you need to avoid an explosion, it's better to go sideways than resist the wind" — [same Steam discussion](https://steamcommunity.com/app/2904000/discussions/0/597405723931074452/)
- Guide view: "movement is everything… never stay still for too long". It punishes standing still, greedy close range, and slow reactions to danger zones — [PixelNitro walkthrough](https://pixelnitro.com/the-spell-brigade-walkthrough-2026-ultimate-guide-to-best-builds-spells-and-boss-strategies/) (low reliability)
- Co-op report of much higher HP than Sol'phish and a 7+ minute fight — [Steam discussion "Kragwa health vs Sol'phish"](https://steamcommunity.com/app/2904000/discussions/0/601919346587134662/)

**Mul'gath, "the Twisted One"**
- New boss in 1.0, tied to Pyrestorm Pit per the fan changelog/guide. The kill unlocks the "Head Hunter" title — [thespellbrigade.wiki changelog](https://thespellbrigade.wiki/changelog/); [GameFAQs PC achievements](https://gamefaqs.gamespot.com/pc/462264-the-spell-brigade/achievements)
- "Punishes narrow damage and poor repositioning", and "the fight can become chaotic quickly" — [PixelNitro walkthrough](https://pixelnitro.com/the-spell-brigade-walkthrough-2026-ultimate-guide-to-best-builds-spells-and-boss-strategies/) (low reliability)

**Boss assignment conflict**
- Fan wiki/guide: Verdant Meadows → Sol'phish, Frozen Ancients → Krog'wa, Pyrestorm Pit → Mul'gath — [thespellbrigade.wiki beginner's guide](https://thespellbrigade.wiki/guides/beginners-guide/)
- Contradicted by a guide calling Sol'phish "one of the three possible end-of-run bosses (1/3 chance to spawn)" — [whisperofthehouse solo guide](https://www.whisperofthehouse.com/the-spell-brigade/solo-guide) (low reliability). The official achievement text ("Boss of Frozen Ancients") supports the fixed mapping, at least for Krog'wa — [GameFAQs PC achievements](https://gamefaqs.gamespot.com/pc/462264-the-spell-brigade/achievements)

**General boss tips**
- Acid infusion on orbiting spells gives each orbit a damage-over-time tick; use it once you reach the boss phase. Acid is also recommended when "bosses, elites, or tanky waves live too long" — [thespellbrigade.wiki beginner's guide](https://thespellbrigade.wiki/guides/beginners-guide/); [ninewiki tier list](https://ninewiki.com/tier-list/the-spell-brigade-tier-list-all-spells-and-elements/) (low reliability)
- 1.2 fixed a bug where killing the boss too fast in Endless could break Level Ups — [Steam announcements](https://steamcommunity.com/app/2904000/announcements/)

### Inferences
- The "1/3 chance" claim may describe Astral Riftlands (no own boss found) or Endless, or it may simply be wrong. The achievement wording favours fixed bosses per Realm.

### Gaps
- No detailed attack list or phase breakdown was found for Krog'wa or Mul'gath. Mul'gath's mechanics are only described in vague terms by a low-reliability guide.
- The Astral Riftlands boss is unidentified.
- I found no evidence of a separate final or super boss.

## 8. Game modes and difficulty

### Takeaway
The main mode is **Missions** on a chosen Realm and **Threat Level** (**Moderate → Severe → Hardcore**, unlocked in sequence per map). On top of that come **Covenants** (run modifiers, including turning off friendly fire) and, since 1.0, **Trial Covenants** with a **Devotion** multiplier tied to the wizard **Ascension** (prestige) system. **Endless Mode** loops a map after the boss with rising enemy stats. **Quests** and **Challenges** act as unlock tracks. I found no daily or weekly runs.

### Cited Findings
**Threat levels**
- Each map starts with only Moderate, and you must beat every map at a threat level to unlock the next one — [Steam guide "The Spell Brigade [1.0]"](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916)
- Severe and Hardcore are the higher tiers. Guides say they increase density, damage and boss HP, and advise mastering Moderate first — [whisperofthehouse solo guide](https://www.whisperofthehouse.com/the-spell-brigade/solo-guide); [Steam discussion "Ascending your wizard?"](https://steamcommunity.com/app/2904000/discussions/0/838375062933398815/)
- Rewards: a forum post says there is no difficulty multiplier on rewards, and suggests 2× gold for Severe and 3× for Hardcore. A guide says to farm gold on the easiest difficulty. Games Press says optional difficulty modifiers give "faster rank gains" — [Steam discussion "Ascending your wizard?"](https://steamcommunity.com/app/2904000/discussions/0/838375062933398815/); [tposegaming](https://tposegaming.com/spell-brigade-ascension/); [Games Press](https://www.gamespress.com/Gather-Your-Squad-and-Join-the-Fray-The-Spell-Brigade-is-Out-Today)

**Covenants**
- Run modifiers. Friendly fire can only be disabled as a Covenant — [GameSpew](https://www.gamespew.com/2026/04/the-spell-brigade-review/); [wiki.gg Covenants](https://thespellbrigade.wiki.gg/wiki/Covenants)
- Endless was reportedly toggled "under the covenants settings" — [Steam discussion "Where is endless mode?"](https://steamcommunity.com/app/2904000/discussions/0/597388342426898046/)

**Ascension and Trial Covenants (1.0)**
- Ascension resets a wizard's rank for a prestige level, with a maximum of two ascensions. The second unlocks Trial Covenants. **Devotion** is the multiplier for ascension progress — [tposegaming Ascension guide](https://tposegaming.com/spell-brigade-ascension/); [whisperofthehouse Trial Covenants guide](https://www.whisperofthehouse.com/the-spell-brigade/trial-covenants-masteries-prestige)
- Conflicts: max rank 10 vs 9. Cost 4,000 gold vs 6,300 gold for the first ascension (player review) — [tposegaming](https://tposegaming.com/spell-brigade-ascension/); [Steam discussion "Ascending your wizard?"](https://steamcommunity.com/app/2904000/discussions/0/838375062933398815/); [Steam review (AnimeMayhem)](https://steamcommunity.com/id/AnimeMayhem/recommended/2904000)
- Trial Covenants and their reported unlock conditions (V1.0):
  - **Mana Drought:** ascend Ludwig and Balthazar twice, plus beat Verdant Meadows on Hardcore at 3+ Devotion.
  - **Torment:** ascend Aldric and Bryony twice, plus beat Frozen Ancients on Hardcore at 5+ Devotion.
  - **Purity:** beat Pyrestorm Pit on Hardcore at 7+ Devotion.
  - **Discipline:** ascend Kavin and Campanelli twice, plus beat Astral Rifts on Hardcore at 9+ Devotion. Its effect is about 20 HP damage on each level-up.
  - **Mortality:** ascend Moon Mage twice. Effect: monsters one-shot you, but the environment doesn't.
  - **Abstinence:** ascend Reginald, Maggie and Pipwick twice. Stacks up to 3×.
  - **Denial:** ascend Wizard King and Star Mage twice. Stacks up to 2×.
  - **Onslaught:** ascend Sun Mage, Hatti and Knelly twice.
  - Sources: [treyexgaming (Oct 2026)](https://www.treyexgaming.com/the-spell-brigade-trial-covenants-guide/); [ninewiki](https://ninewiki.com/guide/the-spell-brigade-how-to-get-trial-covenants/)
- **Changed in patch 1.0.5.17363:** you no longer need to ascend specific wizards to unlock Trial Covenants (per a Steam guide now marked "Outdated") — [Steam guide](https://steamcommunity.com/sharedfiles/filedetails/?id=3719250290)

**Endless Mode**
- Repeats the level after the boss dies, returns you to the start with spells and stats kept, and raises enemy damage/health — [Creeping for Scale Models](https://creepingforscalemodels.com/2025/06/01/lets-play-update-the-spell-brigade/)
- Unlock: defeat Sol'phish once. Another user mentions a Severe mission named "Eternity" (secondhand) — [Steam discussion "Where is endless mode?"](https://steamcommunity.com/app/2904000/discussions/0/597388342426898046/)
- A post-1.0 thread is titled "No endless mode?" — [Steam discussion](https://steamcommunity.com/app/2904000/discussions/0/838375696283863404/)
- No clean exit: "No rewards. You have to die, can't quit". Others say force-closing kept gold and achievements — [Steam discussion "You can't quit endless mode?"](https://steamcommunity.com/app/2904000/discussions/0/844006722408383488/); [Steam discussion "Endless mode -> quit"](https://steamcommunity.com/app/2904000/discussions/0/580550781202135985/)
- History: 0.7.2 (Jan 2025) added an Augmentation for beating Sol'phish in Endless and denser spawns after Cycle I. Update 9 (Apr 2025) raised Endless difficulty. 1.2 (Oct 2026) fixed boss-kill level-up breakage — [SteamDB 0.7.2](https://steamdb.info/patchnotes/17171436/); [Steam EA Update 9](https://steamcommunity.com/games/2904000/announcements/detail/528717787215955183); [Steam announcements](https://steamcommunity.com/app/2904000/announcements/)

**Quests, Challenges and objective unlocks**
- The Quests page lists targets such as defeating Sol'phish, Krog'wa and Mul'gath. Objectives unlock with completions: Sacrifice after 5 completions, Brazier after 25 — [wiki.gg Quests](https://thespellbrigade.wiki.gg/wiki/Quests)
- Patch 9: each of the 7 new Scrolls is unlocked via its own Quest — [thespellbrigade.wiki changelog](https://thespellbrigade.wiki/changelog/)
- Challenges are used to unlock Astral Riftlands — [Steam discussion "Astral Riftlands - new Realm locked?"](https://steamcommunity.com/app/2904000/discussions/0/603042323028337908/)

**Objective types (as reported)**
- **Herd the Mana Beasts** (lead beasts to their enclosure); **Light the Braziers** (find the right brazier combination; Astral Riftlands update); **Boss Killer** (kill the boss) — [Steam guide [1.0]](https://steamcommunity.com/sharedfiles/filedetails/?id=3495481916)
- **Sacrifice** (kill enemies inside the circle; can also appear as a **Death Shrine** that takes damage from anything in the zone) — [wiki.gg Objectives](https://thespellbrigade.wiki.gg/wiki/Objectives); [Steam announcements](https://steamcommunity.com/app/2904000/announcements/)
- **Golden Crab** hunt (chase the crab before it escapes) — [wiki.gg Objectives](https://thespellbrigade.wiki.gg/wiki/Objectives)
- Zone kill-count and XP-collection challenges, e.g. "kill 50 enemies within 90 seconds in this zone" — [Screen Hype](https://www.screenhype.co.uk/the-spell-brigade-review-addictive-magical-chaos/)

**Planned**
- Highscores and a logbook are on the post-1.0 roadmap — [thespellbrigade.wiki changelog](https://thespellbrigade.wiki/changelog/)

### Inferences
- The difficulty stack has three layers: Threat Level, then Covenants, then Trial Covenants with Devotion. The top layer serves as the game's "heat/curse" system and is tied to the 1.0 Ascension meta-progression.
- Endless seems to have moved from a standalone mode (EA) to an option under Covenants or a specific mission over time. That would explain the "Where is endless mode?" and "No endless mode?" threads.

### Gaps
- I found no daily/weekly challenge runs or seeded runs. Highscores were still only planned in Jul 2026.
- Exact numeric effects of each threat level and each regular Covenant were not found.
- The current (1.2) Endless unlock path and how to quit Endless were not confirmed.

## 9. Beginner tips and strategy advice

### Takeaway
Common advice: learn on Moderate, farm gold on easy difficulty (rewards don't scale with difficulty), take objectives your build can handle (Augmentations are powerful), use the hazard-free start area as a safe base, keep moving (especially against Krog'wa), bring Ice for Sol'phish and Acid/DoT for tanky targets, and in co-op keep spare Revive Cores on one player and spread out to limit friendly fire. Several tip sources are low quality, so lean on the forum-sourced tips.

### Cited Findings
- Start on Moderate and don't attempt Hardcore until you can clear Moderate without dying — [whisperofthehouse solo guide](https://www.whisperofthehouse.com/the-spell-brigade/solo-guide) (low reliability)
- Gold farming: base difficulty gives no bonus ascension progress or gold, so farm on Easy — [tposegaming](https://tposegaming.com/spell-brigade-ascension/); [Steam discussion "Ascending your wizard?"](https://steamcommunity.com/app/2904000/discussions/0/838375062933398815/)
- Keep Devotion at a level you can survive, because difficulty rises sharply — [whisperofthehouse Trial Covenants guide](https://www.whisperofthehouse.com/the-spell-brigade/trial-covenants-masteries-prestige)
- Objectives (conflicting advice): one guide says skip objectives that would probably end the run. Another says don't avoid any unless truly necessary. A solo achievement guide says prioritise objective zones — [fantasywarden](https://fantasywarden.com/games/spell-brigade-beginners-guide); [thespellbrigade.wiki beginner's guide](https://thespellbrigade.wiki/guides/beginners-guide/); [whisperofthehouse achievements guide](https://www.whisperofthehouse.com/the-spell-brigade/achievements-guide)
- Hardcore solo on Astral Riftlands: stay in the starting area ("the largest hazard-free zone") and return there after each objective — [Steam discussion "Astral Riftlands Hardcore Solo"](https://steamcommunity.com/app/2904000/discussions/0/603043375716951366/)
- Golden Crab: run away from the icon when it appears and watch whether the crab follows. It can die off-screen before the marker shows — [Steam discussion "BUG: Objective Visibility needs work."](https://steamcommunity.com/app/2904000/discussions/0/597402967401828620/)
- Sol'phish: ice infusion becomes necessary, and burst during the stagger window. Krog'wa: dodge sideways, use area-clearing spells — [wiki.gg Sol'phish](https://thespellbrigade.wiki.gg/wiki/Sol'phish); [Steam discussion "The new boss sucks and blows…"](https://steamcommunity.com/app/2904000/discussions/0/597405723931074452/)
- Revive Cores: have one player hold the group's spares — [GameBrief](https://www.gamebrief.net/blog/the-spell-brigade-tips-guide-2026) (low reliability)
- First wizard: one guide recommends Reginald for his luck bonus to upgrade quality — [whisperofthehouse solo guide](https://www.whisperofthehouse.com/the-spell-brigade/solo-guide) (low reliability)
- Build archetypes for solo: "Solar Pulse Aura" as starting point, "Acid Multi-Hit" for bosses and elites, "Scepter Mesh" for space control (details belong to the spell researcher) — [whisperofthehouse solo guide](https://www.whisperofthehouse.com/the-spell-brigade/solo-guide)
- More tip lists exist but their contents weren't retrieved — [TheGamer "8 Tips To Help Beginners"](https://www.thegamer.com/the-spell-brigade-beginner-tips/); [Steam discussion "Beginner questions"](https://steamcommunity.com/app/2904000/discussions/0/838375062933507325/)

### Inferences
- With auto-fire, the main skill levers are route planning (objective order, safe zones, hazard avoidance) and build choices at level-ups. Tips focus on those rather than on mechanical aim.

### Gaps
- The best source for tips, TheGamer's list, could not be read. The Steam [1.0] guide by the community (id 3495481916) also could not be opened, though it likely contains a fuller run walkthrough.
