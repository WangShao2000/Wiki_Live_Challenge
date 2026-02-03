# The Dorfromantik Phenomenon: A Comprehensive Analysis of the Board Game Franchise, Design Philosophy, and Cultural Impact
## 1\. Introduction and Executive Summary
The landscape of modern tabletop gaming has undergone a significant transformation in the post-2020 era, characterized by a distinct shift toward "cozy" gaming experiences—titles that prioritize relaxation, aesthetic pleasure, and low-stakes cooperation over direct conflict and high-stress competition. At the forefront of this movement stands *Dorfromantik: The Board Game* (German: *Dorfromantik: Das Brettspiel*), a cooperative tile-laying game designed by Michael Palm and Lukas Zach and published by Pegasus Spiele[1] .

Released initially in November 2022, *Dorfromantik* is a faithful analog adaptation of the critically acclaimed video game of the same name developed by Toukana Interactive. The board game challenges one to six players to collaboratively construct an idyllic hexagonal landscape composed of forests, grain fields, villages, railway tracks, and waterways. Through a unique blend of spatial puzzling and a non-destructive "legacy" campaign system, players unlock new components and scoring opportunities over repeated sessions, creating a sense of progression rarely seen in family-weight games[1] .

The game’s impact on the industry was cemented in July 2023 when it was awarded the *Spiel des Jahres* (Game of the Year), the most prestigious accolade in the board gaming world[4] . This victory not only validated the commercial viability of video-to-board adaptations—a genre historically fraught with mixed quality—but also signaled a broader acceptance of "cozy" mechanics in mainstream gaming criticism.

As of December 17, 2025, the *Dorfromantik* brand has expanded into a robust franchise. The ecosystem now includes the original *Spiel des Jahres* winner, a competitive two-player spin-off titled *Dorfromantik: The Duel* (2024), a standalone Japanese-themed sequel *Dorfromantik: Sakura* (2024), and a compact travel edition *Dorfromantik: Light Luggage* (2025)[1] . Additionally, mini-expansions such as *The Great Mill* and *The Wetterau* have further enriched the gameplay variety[1] .

This report provides an exhaustive analysis of the *Dorfromantik* board game franchise. It explores the ludological transition from digital to analog formats, dissects the mechanics and mathematical underpinnings of its hexagonal systems, evaluates the strategic depth of its cooperative play, and chronicles the commercial and critical reception that led to its dominance in the family gaming sector.

## 2\. Historical Origins and Transmedia Adaptation
### 2.1 The Digital Progenitor: Toukana Interactive’s *Dorfromantik*
To fully understand the board game's design, one must first examine its digital origin. *Dorfromantik* (the video game) was developed by Toukana Interactive, a small indie studio founded by students from the HTW Berlin (University of Applied Sciences)[2] . Released in Early Access in March 2021 and fully in April 2022, the video game emerged during the height of the COVID-19 pandemic. Its timing was serendipitous; the global population, confined to their homes and subjected to high levels of stress, found solace in the game's pastoral aesthetics, calming soundtrack, and lack of time pressure or combat[8] .

The digital game is a single-player puzzle where players place procedurally generated tiles to match edges (e.g., forest to forest, house to house). The scoring system is complex and algorithmic, tracking "perfect placements" (matching all six edges) and calculating the size of connected territories instantaneously. This computational complexity presented the primary challenge for any potential tabletop adaptation: how to replicate the satisfaction of the digital loop without burdening players with excessive bookkeeping[8] .

### 2.2 The Adaptation Philosophy: Michael Palm and Lukas Zach
The task of adapting *Dorfromantik* fell to veteran German designers Michael Palm and Lukas Zach, whose previous credits included *The Dwarves* (*Die Zwerge*) and *Aventuria*. Pegasus Spiele, a major German publisher, aggressively pursued the license, recognizing the overlap between the video game's demographic and the modern board gamer[10] .

The designers' core philosophy was "translation through simplification." They identified that the emotional core of *Dorfromantik* was not the complex arithmetic of the score, but the visual satisfaction of building a growing landscape and the dopamine hit of completing "quests" (Tasks).

* **From Algorithmic to Discrete:** In the video game, a "perfect placement" grants an immediate tile refund, a calculation easy for a CPU but tedious for a human. Palm and Zach replaced this with the "Task" system. Instead of tracking every edge match, players focus on specific, high-value objectives represented by Task tokens.  
* **From Infinite to Finite:** The video game theoretically continues forever as long as the player plays well. A board game requires a definitive end state. The designers introduced a fixed limit of Landscape tiles, creating a natural arc from start to finish, typically lasting 30 to 60 minutes[2] .

### 2.3 Production and Art Direction
The visual identity of *Dorfromantik* is integral to its brand. The board game retains the art style of the video game, characterized by soft, low-poly aesthetics, vibrant greens and yellows, and a distinct lack of harsh outlines. Illustrator Paul Riebe was tasked with translating the 3D assets into 2D tile art that remained readable across a table[3] . The components—hexagonal tiles, wooden hearts, and cardboard tokens—were produced with a focus on sustainability, aligning with the environmental themes of the game and the German market's increasing demand for plastic-free packaging[6] .

## 3\. Comprehensive Ludology and Mechanics
*Dorfromantik: The Board Game* is a cooperative tile-placement game played on a hexagonal grid. While the rules are accessible (complexity rating \~1.0–1.2/5), the interaction of systems creates a rich puzzle[11] .

### 3.1 Component Architecture
The game box contains:

* **Landscape Tiles:** The fundamental building blocks, depicting combinations of Forest, Grain, Village, Water (Stream), and Track (Rail).  
* **Task Tiles:** A subset of Landscape tiles that feature a specific icon indicating a request from the population (e.g., a speech bubble with a number).  
* **Task Tokens:** Numerical chits corresponding to the demands on the Task tiles.  
* **Campaign Sheet:** A pad used to track progress, scores, and unlocked achievements.  
* **Unlock Boxes (1–5):** Sealed tuck boxes containing new components introduced via the campaign[2] .

### 3.2 The Core Loop: Draft, Place, Check
The gameplay is structured around a continuous turn cycle shared by the group.

#### 3.2.1 The Drafting Decision
The active player's turn begins with a mandatory check of the **Task Slots**. There are three designated slots for active Task tiles.

* **Replenishment:** If there are fewer than three Task tiles currently on the board, the player *must* draw a new Task tile from the Task stack. This ensures the group always has multiple objectives to pursue simultaneously.  
* **Expansion:** If three Tasks are already active, the player draws a standard Landscape tile.

This mechanism acts as a pacing regulator. It prevents players from ignoring objectives to purely expand the map, forcing a balance between "scoring" turns (placing Tasks) and "building" turns (placing Landscapes)[14] .

#### 3.2.2 Hexagonal Topology and Placement Logic
The chosen tile must be placed adjacent to at least one edge of an existing tile. Unlike *Carcassonne*, which requires perfect edge matching (e.g., road to road, city to city), *Dorfromantik* allows for **incongruent placement** with two critical exceptions:

1. **Tracks (Railroads):** A rail edge must connect to another rail edge or an empty space. It cannot be placed against a non-rail edge (e.g., a forest). This rule prevents the visual and logical dissonance of a train crashing into a house.  
2. **Streams (Water):** Similarly, water edges must connect to water or open space.

All other edges (Forest, Grain, Village, Grass) can be placed adjacent to mismatching types. However, mismatching edges is strategically suboptimal, as it often closes off territories that need to grow to fulfill Tasks[3] .

#### 3.2.3 The Task System
When a Task tile is drawn, a Task token is drawn blindly and placed upon it. This token dictates the *exact* size of the territory required.

* **Example:** A "Forest 5" token on a Forest tile means that specific connected forest area must encompass exactly 5 tiles.  
* **Completion:** Once the connected area reaches the target number, the Task is complete. The token is removed and scored, and the Task tile remains as a standard part of the landscape.  
* **Failure Conditions:** If the territory exceeds the target number (e.g., grows to 6\) before the token is removed, the Task is failed. Alternatively, if the territory is "closed off" (surrounded by non-matching edges) while smaller than the target number, it is also failed. Failed tokens are removed from the game[14] .

This "exact match" requirement introduces a layer of precision. Players cannot simply build a massive mega-forest; they must carefully prune and shape territories to hit specific numerical targets, often creating separate, smaller enclaves to fulfill low-number tasks.

### 3.3 End Game and Scoring Calculus
The game ends immediately when the stack of Landscape tiles is depleted. Scoring is a composite of several vectors:

1. **Completed Tasks:** The sum of the values of all collected Task tokens (e.g., 4 \+ 5 \+ 6...).  
2. **Flags:** Certain tiles feature a colored flag in a specific terrain type. If a territory containing a flag is completely closed off (surrounded by incompatible edges), the player scores points equal to the number of tiles in that territory. This incentivizes closing areas, which conflicts with the need to keep areas open for growth tasks—a central tension in the game design[15] .  
3. **Longest Track and Stream:** Players score points for the longest continuous interconnected rail and river segments.  
4. **Campaign Unlocks:** As the campaign progresses, new scoring cards (e.g., the Photographer, the Mill) provide additional ways to score[9] .

The final score is compared against a tiered chart on the Campaign Sheet to determine how many "steps" the group advances on the campaign track.

## 4\. The Campaign: A Non-Destructive Legacy System
The most innovative aspect of *Dorfromantik: The Board Game* is its implementation of campaign play. Traditional "legacy" games (e.g., *Pandemic Legacy*) often involve permanently altering components—writing on boards, tearing up cards—which limits the game's lifespan. *Dorfromantik* utilizes a **non-destructive legacy** model.

### 4.1 Progression Mechanics
The campaign is tracked via a sheet where players cross off circles based on their performance. Crossing off specific milestones unlocks the sealed boxes numbered 1 through 5\.

* **Box 1 & 2:** Often unlock early in the campaign (sometimes after game 1 or 2). They typically introduce new specialized tiles or wooden components that offer new scoring vectors[13] .  
* **Later Boxes:** Introduce more complex objectives, such as "Achievement Cards" (e.g., *Circus*, *Watchtower*) that require specific spatial patterns or high-score thresholds within a specific terrain type[16] .

### 4.2 Replayability and "Failing Forward"
The system is designed so that players effectively "fail forward." Even a mediocre score contributes some progress on the campaign track. There is no "Game Over" state that resets the campaign; rather, the group simply advances slower. This design choice reinforces the "cozy" atmosphere, removing the fear of punishment that drives tension in other cooperative games[3] .

Moreover, the game is fully resettable. The unlocked content can be returned to the boxes, or simply mixed in for a "fully expanded" skirmish game. This flexibility allows the game to function as both a narrative campaign for a dedicated group and a casual filler for ad-hoc play.

## 5\. Strategic Analysis and Cooperative Dynamics
Despite its gentle theme, *Dorfromantik* rewards deep strategic thinking. The cooperative nature of the game relies on distributed cognition—the idea that six eyes are better than two at spotting spatial opportunities on a complex hexagonal grid.

### 5.1 Probability Management
Advanced groups quickly learn to manage the "deck." While players cannot know the exact order of tiles, they can intuit probabilities. For instance, tiles with "sharp turn" rails or "triple branch" rivers are rare. Relying on drawing a specific, rare connector to save a disjointed territory is a high-risk strategy. Therefore, **edge management**—leaving open edges that can accept common tile types—is a key skill[9] .

### 5.2 The "Task Churn" Strategy
Since points are primarily derived from completing tasks, efficient play involves maximizing "Task Churn"—the rate at which new tasks are drawn and completed.

* **Pipeline Setup:** Players will often "pre-build" a territory (e.g., a forest of size 4\) *before* drawing a "Forest 5" task. Once the task appears and is placed, it can be completed instantly with a single tile placement, allowing the group to cycle to the next task immediately.  
* **Task Stacking:** Players must decide whether to attach a new Task to an existing territory (risking it becoming too large or unmanageable) or starting a new territory.

### 5.3 Solo vs. Multiplayer Dynamics
In solo play, Dorfromantik becomes a pure optimization puzzle, akin to Patience or Solitaire. The player has complete control but lacks the "error-checking" of partners.  
In multiplayer, the game mitigates the "Alpha Gamer" problem (where one player dictates moves) through sheer information overload. The grid grows in six directions, and checking valid placements for all active tasks is cognitively taxing. This encourages a "parliamentary" style of play where suggestions are debated. "I think the Grain 4 goes here," "But that blocks the River for the Longest Stream point." This discussion is the social heart of the game[12] .

## 6\. Expansions and Post-Release Content
Between late 2023 and 2025, Pegasus Spiele released several expansions and standalone games, turning *Dorfromantik* into a flagship franchise.

### 6.1 Mini-Expansions
#### 6.1.1 *The Great Mill* (2023)
Released in October 2023, *The Great Mill* (*Große Mühle*) was the first significant gameplay addition.

* **Components:** A standee of a windmill and two new cards.  
* **Mechanics:** It introduces a specific "Mill" achievement. Once unlocked, players place the Mill standee on a Grain tile. The Mill scores bonus points for every Grain Task completed within its territory and for yellow Flags connected to it. This expansion significantly buffs the "Grain" strategy, which in the base game was often secondary to Forests or Villages due to tile geometry[1] .

#### 6.1.2 *The Wetterau* (2024)
Released in June 2024, this expansion is a love letter to the publisher's home region.

* **Content:** Three unique landscape tiles depicting landmarks from the Wetterau district in Hesse, Germany: the **Adolfsturm** (a historic tower), the **Pegasus** statue (the company's logo), and the **Winterstein/Steinkopf TV tower**.2  
* **Significance:** While mechanically simple, these tiles add visual variety and serve as "wildcards" for certain connections, easing difficult placement spots.

### 6.2 Standalone Sequels
#### 6.2.1 *Dorfromantik: The Duel* (February 2024\)
This release marked the first divergence from the cooperative format. *The Duel* introduces competitive play for two players or teams.

* **Symmetrical Play:** Both sides receive identical decks of tiles. A central deck dictates the order: "Player A reveals a Forest/Rail tile; Player B must find their matching copy and play it." This eliminates luck of the draw, making the game a test of pure spatial efficiency[2] .  
* **Modules:** It includes two modules to vary difficulty and a simplified legacy track.  
* **Critical Reception:** Reception was mixed. While the mechanics were sound, many critics felt the competitive pressure undermined the "chill" vibe that defined the brand. It was described as "parallel solitaire" with low interaction, yet praised for its speed (30 minutes) and the fairness of its symmetrical setup[17] .

#### 6.2.2 *Dorfromantik: Sakura* (Essen SPIEL 2024\)
Released in late 2024, *Sakura* transports the setting to Japan, capitalizing on the aesthetic popularity of cherry blossoms.

* **Visual Overhaul:** The art replaces European cottages and pine forests with Japanese architecture, rice paddies, and pink cherry blossom trees.  
* **New Mechanics:** The titular "Cherry Blossom" mechanic introduces a new scoring layer distinct from standard Tasks. The campaign is deeper, featuring **six** unlockable boxes (compared to the original's five) and over 40 achievements, suggesting Pegasus Spiele aimed to cater to veteran players wanting a longer, richer experience[2] .  
* **Reception:** Early reviews from Essen 2024 highlighted the beautiful table presence and the successful integration of the new mechanics, which added complexity without sacrificing accessibility[23] .

#### 6.2.3 *Dorfromantik: Light Luggage* (Late 2025\)
Released in October/November 2025, this version addresses the criticism regarding the original game's table footprint.

* **Design:** Packaged in a magnetic closure box, *Light Luggage* reduces component size and quantity to fit on smaller surfaces (e.g., train tables, coffee tables).  
* **Player Count:** Supports 1-4 players (down from 6).  
* **Content:** Despite the size, it retains a full campaign mode, positioning it as a robust standalone product rather than a stripped-down demo[24] .

## 7\. Commercial Performance and Industry Impact
### 7.1 The *Spiel des Jahres* 2023 Victory
The crowning achievement for the franchise was winning the **Spiel des Jahres** (SdJ) in July 2023\. The jury selected *Dorfromantik* over *Fun Facts* and *Next Station: London*.

* **Jury Statement:** The jury praised the game for "taking the pressure out of everyday life," explicitly linking its value to its relaxing nature. They noted the campaign "entices you to play new games" and that the difficulty curve ensures "everyone is in their comfort zone"[5] .  
* **Historical Context:** This win was historic as it was the first time a direct video game adaptation won the main SdJ award. While *Carcassonne* inspired video games, *Dorfromantik* proved the flow could reverse successfully. It also validated the inclusion of "legacy" elements in family games, a mechanic previously reserved for "Expert" (Kennerspiel) titles like *Pandemic Legacy*.4

### 7.2 Awards and Nominations Table
The game's reception was globally positive, reflected in numerous awards:

| Year | Award | Category | Result | Source |
| :---- | :---- | :---- | :---- | :---- |
| **2023** | **Spiel des Jahres** | **Game of the Year** | **Winner** | 1 |
| 2023 | Guldtärningen (Sweden) | Game of the Year | Winner | 2 |
| 2023 | Golden Geek Awards | Cooperative Game | Nominated | 26 |
| 2023 | Golden Geek Awards | Innovative | Nominated | 27 |
| 2024 | American Tabletop Awards | Strategy Games | Recommended | 2 |
| 2024 | As d'Or (France) | Game of the Year | Nominated | 28 |

### 7.3 Critical Analysis
Critics have widely lauded *Dorfromantik* for successfully bridging the gap between digital and analog gaming. *The Dice Tower* and *Meeple Mountain* both highlighted its accessibility, noting it serves as a perfect "gateway game" for video gamers entering the hobby[3] .

However, the game is not without detractors. The most common criticism concerns the **table sprawl**. A late-game map can easily exceed the boundaries of a standard dining table, creating logistical issues[2] . Additionally, some "heavy" gamers found the lack of fail states boring, describing the game as an activity rather than a challenge. The 2024 release of *The Duel* attempted to address this demographic but alienated the core "cozy" audience, highlighting the difficulty of balancing these two gamer psychologies[17] .

## 8\. Comparative Ludology
To contextualize *Dorfromantik*, it is useful to compare it with its peers:

* **Vs. *Carcassonne*:** Both are tile-laying games. *Carcassonne* is competitive and confrontational (stealing cities); *Dorfromantik* is cooperative. *Carcassonne* uses squares; *Dorfromantik* uses hexes, which offer 6 degrees of freedom vs. 4, allowing for more organic, less grid-like maps.  
* **Vs. *Cascadia*:** *Cascadia* (SdJ 2022 winner) is also a nature-themed hex-placement game. However, *Cascadia* focuses on two separate layers (terrain and animals) and is competitive. *Dorfromantik* integrates the objectives *into* the terrain (Tasks) and adds the legacy campaign element.  
* **Vs. *Pandemic Legacy*:** *Pandemic Legacy* destroys components and has a finite end. *Dorfromantik* unlocks components without destruction and can be reset, representing a more sustainable and family-friendly approach to the legacy genre.

## 9\. Conclusion
*Dorfromantik: The Board Game* stands as a watershed moment in 21st-century board gaming. It successfully translated the ephemeral "vibes" of a cozy video game into rigorous tabletop mechanics without losing the soul of the original. Its success—capped by the *Spiel des Jahres* win—demonstrated that the market was hungry for high-quality cooperative puzzles that prioritized construction over destruction.

Through its expansions and standalone sequels like *Sakura* and *The Duel*, Pegasus Spiele has cultivated *Dorfromantik* into a versatile franchise that caters to soloists, couples, families, and travelers alike. As of late 2025, with the release of *Light Luggage*, the franchise shows no signs of slowing down, having firmly established itself as a modern classic alongside the likes of *Catan* and *Ticket to Ride*.

## 10\. References
*(Citation identifiers integrated directly into the text as per guidelines.)*

## References
[1] Dorfromantik \- Wikipedia, accessed December 17, 2025， [https://en.wikipedia.org/wiki/Dorfromantik](https://en.wikipedia.org/wiki/Dorfromantik)  
[2] Dorfromantik (board game) \- Wikipedia, accessed December 17, 2025， [https://en.wikipedia.org/wiki/Dorfromantik\_(board\_game)](https://en.wikipedia.org/wiki/Dorfromantik_\(board_game\))  
[3] Dorfromantik: The Board Game Review \- Meeple Mountain, accessed December 17, 2025， [https://www.meeplemountain.com/reviews/dorfromantik-the-board-game/](https://www.meeplemountain.com/reviews/dorfromantik-the-board-game/)  
[4] Spiel des Jahres 2023 \- Game of the Year \- Tabletop Gaming, accessed December 17, 2025， [https://www.tabletopgaming.co.uk/news/spiel-des-jahres-2023-game-of-the-year/](https://www.tabletopgaming.co.uk/news/spiel-des-jahres-2023-game-of-the-year/)  
[5] "Dorfromantik" is the "Game of the Year 2023" \- Galaxus, accessed December 17, 2025， [https://www.galaxus.de/en/page/dorfromantik-is-the-game-of-the-year-2023-28760](https://www.galaxus.de/en/page/dorfromantik-is-the-game-of-the-year-2023-28760)  
[6] Dorfromantik \- Light Luggage \- Pegasus Spiele, accessed December 17, 2025， [https://pegasusna.com/News/Dorfromantik-Light-Luggage/](https://pegasusna.com/News/Dorfromantik-Light-Luggage/)  
[7] Dorfromantik: The Great Mill Mini-Expansion \- Board Game Barrister, accessed December 17, 2025， [https://store.boardgamebarrister.com/dorfromantik-the-great-mill-mini-expansion/](https://store.boardgamebarrister.com/dorfromantik-the-great-mill-mini-expansion/)  
[8] Dorfromantik: The Board Game wins 2022 Spiel des Jahres \- The Daily Worker Placement, accessed December 17, 2025， [https://dailyworkerplacement.com/2023/07/25/dorfromantik-the-board-game-wins-2022-spiel-des-jahres/](https://dailyworkerplacement.com/2023/07/25/dorfromantik-the-board-game-wins-2022-spiel-des-jahres/)  
[9] r/soloboardgaming \- Opinion on Dorfromantik after the 5th box opened (minor spoilers), accessed December 17, 2025， [https://www.reddit.com/r/soloboardgaming/comments/1apwnox/opinion\_on\_dorfromantik\_after\_the\_5th\_box\_opened/](https://www.reddit.com/r/soloboardgaming/comments/1apwnox/opinion_on_dorfromantik_after_the_5th_box_opened/)  
[10] “It's clear there are too many games being published”: Pegasus ..., accessed December 17, 2025， [https://boardgamewire.com/index.php/2023/10/31/its-clear-there-are-too-many-games-being-published-pegasus-spieles-co-founder-talks-dorfromantik-economic-uncertainty-and-how-it-keeps-winning-board-gamings-biggest-prize/](https://boardgamewire.com/index.php/2023/10/31/its-clear-there-are-too-many-games-being-published-pegasus-spieles-co-founder-talks-dorfromantik-economic-uncertainty-and-how-it-keeps-winning-board-gamings-biggest-prize/)  
[11] Dorfromantik and the Simple Joy of an Early Campaign Ending \- Gameward Bound, accessed December 17, 2025， [https://gamewardbound.com/dorfromantik-solo-play/](https://gamewardbound.com/dorfromantik-solo-play/)  
[12] Game Review: Dorfromantik \- Tumbleweird, accessed December 17, 2025， [https://tumbleweird.org/game-review-dorfromantik/](https://tumbleweird.org/game-review-dorfromantik/)  
[13] Dorfromantik questions : r/boardgames \- Reddit, accessed December 17, 2025， [https://www.reddit.com/r/boardgames/comments/1c8xhcj/dorfromantik\_questions/](https://www.reddit.com/r/boardgames/comments/1c8xhcj/dorfromantik_questions/)  
[14] Dorfromantik \- What's Eric Playing?, accessed December 17, 2025， [https://whatsericplaying.com/2024/01/01/dorfromantik/](https://whatsericplaying.com/2024/01/01/dorfromantik/)  
[15] Dorfromantik: The Board Game | The Dice Tower, accessed December 17, 2025， [https://www.dicetower.com/board-game/370591](https://www.dicetower.com/board-game/370591)  
[16] Rules clarification : r/Dorfromantik \- Reddit, accessed December 17, 2025， [https://www.reddit.com/r/Dorfromantik/comments/1i0mvr3/rules\_clarification/](https://www.reddit.com/r/Dorfromantik/comments/1i0mvr3/rules_clarification/)  
[17] Dorf Romantik \- holy crap\! : r/boardgames \- Reddit, accessed December 17, 2025， [https://www.reddit.com/r/boardgames/comments/1h1m2u0/dorf\_romantik\_holy\_crap/](https://www.reddit.com/r/boardgames/comments/1h1m2u0/dorf_romantik_holy_crap/)  
[18] Dorfromantik board game sequel trades idyllic calm for a village building competition, accessed December 17, 2025， [https://www.dicebreaker.com/games/dorfromantik/news/dorfromantik-das-duell-competitive-sequel-announcement](https://www.dicebreaker.com/games/dorfromantik/news/dorfromantik-das-duell-competitive-sequel-announcement)  
[19] Dorfromantik: The Duel \- Board Game Review \- Meeple and the Moose, accessed December 17, 2025， [https://meepleandthemoose.com/2025/10/04/dorfromantik-the-duel-board-game-review/](https://meepleandthemoose.com/2025/10/04/dorfromantik-the-duel-board-game-review/)  
[20] Dorfromantik: the Duel Game Review \- Meeple Mountain, accessed December 17, 2025， [https://www.meeplemountain.com/reviews/dorfromantik-the-duel/](https://www.meeplemountain.com/reviews/dorfromantik-the-duel/)  
[21] Dorfromantik Sakura \- Gameology, accessed December 17, 2025， [https://www.gameology.com.au/products/dorfromantik-sakura](https://www.gameology.com.au/products/dorfromantik-sakura)  
[22] Dorfromantik: Sakura \- Meeple Mountain, accessed December 17, 2025， [https://www.meeplemountain.com/boardgame/dorfromantik-sakura/](https://www.meeplemountain.com/boardgame/dorfromantik-sakura/)  
[23] Dorf Romantik Sakura in about 3 minutes \- YouTube, accessed December 17, 2025， [https://www.youtube.com/watch?v=TiodkiwX0gU](https://www.youtube.com/watch?v=TiodkiwX0gU)  
[24] Wide landscapes in small format \- Blog und News \- Pegasus Spiele, accessed December 17, 2025， [https://news.pegasus.de/en/dorfromantik-light-luggage/](https://news.pegasus.de/en/dorfromantik-light-luggage/)  
[25] Dorfromantik: Light Luggage \- Cardhaus Games, accessed December 17, 2025， [https://www.cardhaus.com/dorfromantik-light-luggage/](https://www.cardhaus.com/dorfromantik-light-luggage/)  
[26] Dorfromantik has won Spiel des Jahres 2023 : r/boardgames \- Reddit, accessed December 17, 2025， [https://www.reddit.com/r/boardgames/comments/151d7w3/dorfromantik\_has\_won\_spiel\_des\_jahres\_2023/](https://www.reddit.com/r/boardgames/comments/151d7w3/dorfromantik_has_won_spiel_des_jahres_2023/)  
[27] Blood on the Clocktower leads nominations for 17th Golden Geek Awards \-, accessed December 17, 2025， [https://boardgamewire.com/index.php/2023/04/25/blood-on-the-clocktower-leads-nominations-for-17th-golden-geek-awards/](https://boardgamewire.com/index.php/2023/04/25/blood-on-the-clocktower-leads-nominations-for-17th-golden-geek-awards/)  
[28] Golden Geek Awards \- Philibert, accessed December 17, 2025， [https://www.philibertnet.com/en/awards/18-golden-geek-awards](https://www.philibertnet.com/en/awards/18-golden-geek-awards)