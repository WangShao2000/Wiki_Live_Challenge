# Tony Hawk's Pro Skater 2 (Game Boy Advance): A Comprehensive Analysis of Technical Innovation and Portable Game Design
## 1\. Introduction and Historical Significance
The release of *Tony Hawk's Pro Skater 2* for the Game Boy Advance (GBA) in June 2001 marked a pivotal moment in the history of handheld electronic entertainment[1] . Arriving as a launch title for Nintendo's 32-bit portable console in North America, the game represented a significant paradigm shift in what was considered technically feasible on a handheld device. Prior to this release, portable adaptations of three-dimensional console blockbusters were largely reductive experiences, often reimagined as two-dimensional side-scrollers due to the severe hardware limitations of platforms like the Game Boy Color[3] .

Developed by Vicarious Visions and published by Activision, the GBA iteration of *Tony Hawk's Pro Skater 2* defied industry expectations by delivering a gameplay experience that faithfully replicated the physics, momentum, and spatial complexity of its console counterparts on the PlayStation and Dreamcast[2] . Through the utilization of a novel isometric graphics engine and a hybrid rendering technique that combined pre-rendered environments with real-time 3D polygonal character models, Vicarious Visions established a new benchmark for console-to-handheld ports[5] .

The title's critical and commercial success not only cemented the Game Boy Advance's reputation as a capable gaming platform but also launched Vicarious Visions into a long-standing tenure as the premier developer for handheld adaptations of the *Tony Hawk* franchise[6] . This report provides an exhaustive examination of the game's development history, technical architecture, gameplay mechanics, level design, audio engineering, and enduring legacy within the video game industry.

## 2\. Development History
### 2.1 Origins and the "Janitor" Pitch
The genesis of *Tony Hawk's Pro Skater 2* for the Game Boy Advance is rooted in the early experimentation of Vicarious Visions, a studio based in upstate New York. Following their work on *Spider-Man* for the Game Boy Color, the studio began exploring the capabilities of Nintendo's upcoming 32-bit hardware, the Game Boy Advance, in early 2000[4] .

At the time, the prevailing design philosophy for GBA development centered on porting Super Nintendo Entertainment System (SNES) titles or utilizing "Mode 7" style pseudo-3D scaling effects for racing games. According to Vicarious Visions CEO Karthik Bala, the studio initially considered these safe routes but ultimately sought a project that would distinguish them from the competition. Bala recounted in interviews that the idea to adapt *Tony Hawk's Pro Skater*—Activision's "crown jewel" franchise—originated from an offhand suggestion during a brainstorming session, humorously attributed to the studio's janitor[4] .

The proposition was fraught with risk. The *Tony Hawk* franchise was renowned for its precise physics and 3D freedom, elements that seemingly conflicted with the GBA's lack of dedicated 3D hardware and reliance on sprite-based rendering. A failed port could have damaged the brand's prestige and the studio's relationship with Activision.

### 2.2 Prototyping the "Impossible"
To convince Activision of the project's viability, Vicarious Visions embarked on a rapid prototyping phase in roughly April 2000, utilizing early GBA development kits[4] . The team, led by technical directors and artists such as Matt Conte and Andy Lomerson, rejected the notion of a 2D side-scroller. Instead, they theorized an isometric perspective—a fixed 3/4 camera angle—that could simulate three-dimensional movement without the computational cost of a fully rotating 3D world[7] .

The team created a technical demonstration that featured a 3D wireframe skater navigating a static environment. This prototype was presented to Activision executives and Tony Hawk during the Electronic Entertainment Expo (E3) in May 2000\. The demonstration was successful; the physics simulation felt authentic to the console experience, leading to an immediate greenlight and a handshake agreement to develop the game for the GBA's launch window[7] .

### 2.3 Development Timeline and Constraints
Actual production began in August 2000, giving the team approximately nine months to deliver a finished product for the GBA's North American launch in June 2001[4] . The development cycle was characterized by intense pressure to replicate the specific "feel" of the Neversoft-developed original while adhering to the strict storage limits of GBA cartridges and the processing constraints of the ARM7TDMI CPU.

The development team collaborated with Activision's quality assurance testers, some of whom were embedded at Vicarious Visions' studio for weeks to assist in redesigning levels. These testers, experts in the console versions of the game, provided critical feedback on level flow and trick lines, ensuring that the isometric adaptation retained the "flow" that high-level players expected[4] .

## 3\. Technical Architecture
### 3.1 The Isometric Solution
The fundamental technical challenge of *Tony Hawk's Pro Skater 2* on GBA was the rendering of a 3D sport on 2D hardware. Vicarious Visions solved this through a hybrid engine that combined two distinct rendering techniques.

#### 3.1.1 Pre-Rendered Environments
The skate parks were not rendered in real-time. Instead, the developers utilized the high-resolution 3D geometry from the PlayStation version of the game. These environments were positioned at a fixed isometric angle and rendered into high-color static images[5] . This approach allowed the GBA version to display an impressive amount of environmental detail—lighting, textures, and geometry—that matched the console versions, albeit from a locked perspective[2] .

Because the backgrounds were essentially 2D bitmaps, the game required a method to handle depth and occlusion. The engine employed a "software masking" technique. When the skater moved behind a foreground object, such as a pillar or a wall, the engine did not clip the character; instead, the obstructing object was rendered semi-transparently[5] . This ensured that the player maintained visual contact with the skater at all times, a critical requirement for a game demanding high-speed precision.

#### 3.1.2 Real-Time Polygonal Characters
In a significant departure from standard GBA development, the skater characters were not 2D sprites. Vicarious Visions implemented a software-driven 3D engine capable of rendering polygonal models in real-time. Each skater was composed of approximately 300 polygons[5] .

This decision was crucial for gameplay fidelity. 2D sprites would have required thousands of frames of animation to represent every trick from every possible angle (e.g., a kickflip seen from the front, back, side, and 45-degree angles). By using 3D models, the game could interpolate animations fluidly, allowing for smooth transitions between tricks and accurate representation of the board's orientation[8] . While the models lacked textures due to the small screen size and processing limits, the flat-shaded polygons provided a clean, readable aesthetic that stood out against the detailed backgrounds[2] .

### 3.2 Physics Engine Portability
To ensure the gameplay felt identical to the home console versions, Vicarious Visions did not attempt to rewrite the physics code from scratch. Instead, lead programmer Matt Conte utilized the PlayStation assembler executable from Neversoft. The team created a binary that allowed the GBA to interpret the original PlayStation bytecode[7] .

This meant that the underlying mathematical logic governing gravity, momentum, friction, and trick scoring was virtually identical to the Sony PlayStation original. When a player performed an Ollie or a Grind, the GBA was executing the same logic calculations as the console version, resulting in a physics simulation that felt indistinguishable to veteran players, despite the visual differences[4] .

### 3.3 Performance Metrics
The efficiency of the engine allowed *Tony Hawk's Pro Skater 2* to run at a consistent 60 frames per second (FPS)[5] . This high frame rate was essential for the fast-paced nature of the gameplay, providing the responsiveness required for linking complex trick combinations. The game's fluid motion was frequently cited by critics as a technical marvel for a handheld system in its first year on the market[2] .

## 4\. Gameplay Mechanics
### 4.1 Adapting Controls to the Handheld
The transition from the PlayStation's DualShock controller (which featured four face buttons, four shoulder buttons, and a D-pad) to the Game Boy Advance's limited input array (A, B, L, R, D-pad) required a thoughtful reduction and remapping of the control scheme[2] .

The resulting control layout prioritized the most essential actions:

| Action | GBA Input | Function |
| :---- | :---- | :---- |
| **Ollie / Jump** | B Button | The core jump mechanic. Holding B builds speed; releasing it executes a jump. |
| **Grind** | A Button | Engages a grind when near a rail or lip. Also used for wall rides. |
| **Flip Tricks** | L Button \+ D-Pad | Executes flip tricks (e.g., Kickflip, Heelflip). |
| **Grab Tricks** | R Button \+ D-Pad | Executes grab tricks (e.g., Indy, Melon). |
| **Rotation** | D-Pad Left / Right | Rotates the skater while on the ground or in the air. |
| **Manual** | Up, Down / Down, Up | Balances on two wheels to link tricks. |
| **Nollie** | L Button (Tap) | Shifts stance to Nollie before a jump. |
| **Switch** | R Button (Tap) | Switches stance between Regular and Goofy. |

.10

Critics noted that while the reliance on shoulder buttons for primary trick categories presented a learning curve, the system eventually became intuitive. The mapping allowed players to perform the full repertoire of moves, including diagonals for specific tricks (e.g., Up-Left \+ L for a specific flip trick)[2] .

### 4.2 The Combo System
The GBA version retained the pivotal "Manual" mechanic introduced in the console version of *Tony Hawk's Pro Skater 2*. This mechanic allowed players to balance on the front or back wheels of the skateboard (performing a "Manual" or "Nose Manual") to extend combos across flat ground[13] . This connected vertical tricks (airs) and street tricks (grinds), enabling the "infinite combo" style of gameplay that defined the series.

However, a notable omission in this version—often a point of confusion for modern retro gamers—is the **Revert** mechanic. The Revert, which allows players to land a vert trick and immediately transition into a manual to continue a combo, was not introduced until *Tony Hawk's Pro Skater 3*.14 Therefore, in *Tony Hawk's Pro Skater 2* for GBA, landing a trick in a half-pipe effectively ends the combo unless the player lands directly into a grind on the coping[14] .

### 4.3 Game Modes
The title offered three primary single-player modes:

1. **Career Mode:** The core progression loop where players select a skater and complete varied objectives across multiple levels to earn cash and unlock new stages[15] .  
2. **Free Skate:** A practice mode with no time limit, allowing players to explore levels and refine trick lines without pressure[16] .  
3. **Single Session:** A standard two-minute run to set high scores without the specific goal requirements of Career Mode[15] .

Notably absent were the **Multiplayer** modes (such as HORSE, Tag, and Graffiti) found in the console versions. The GBA Link Cable was not supported, making this a strictly solitary experience[2] . Additionally, the **Park Editor** and **Create-A-Skater** features were removed due to cartridge storage limitations[2] .

### 4.4 Character Progression
While players could not create a custom skater, the game retained the RPG-lite progression mechanics of the console version. Players earned cash by completing level goals, which could be spent in two areas:

* **Edit Stats:** Players could purchase attribute points to improve their skater's Air, Hangtime, Ollie, Speed, Spin, Landing, Switch, Rail Balance, Lip Balance, and Manual stats[11] .  
* **Edit Tricks:** Players could purchase new special moves or re-map existing trick slots to customize their skater's repertoire[17] .  
* **Decks:** Players could purchase new skateboard decks, which were purely cosmetic but offered a sense of progression[17] .

## 5\. Level Design and Analysis
The level roster in *Tony Hawk's Pro Skater 2* for GBA is a curated selection of stages from the PlayStation original, augmented by a classic level from the first game and a platform-exclusive secret level. While the layouts were faithfully recreated, the isometric perspective necessitated subtle adjustments to object placement and geometry to ensure playability[4] .

### 5.1 The Hangar (Meacham Field, TX)
The introductory level serves as a tutorial for vertical and street transitions. The layout consists of a large main room with a half-pipe and a secondary room accessible by breaking through glass.

* **Layout:** The level features a large central half-pipe in the main room and a helicopter in the secondary room.  
* **Objectives:** High Score (10,000), Pro Score (25,000), Sick Score (75,000), Collect S-K-A-T-E, Barrel Hunt, Collect 5 Pilot Wings, Nosegrind Over the Pipe, Hit 3 Hangtime Gaps, Find the Hidden Tape, 100% Goals and Cash[18] .  
* **Secrets:** Grinding the helicopter's rotor blades causes the aircraft to take off, opening the roof. Grinding the propeller on the side wall opens the entrance to the "Wind Tunnel" secret area[18] .  
* **Design Note:** The isometric view makes certain aerial gaps, such as the "Nosegrind Over the Pipe," reliant on the player's ability to track the skater's shadow to judge alignment[19] .

### 5.2 School II (Southern California)
A massive outdoor environment emphasizing street skating, rails, and large stair sets.

* **Layout:** Key areas include the "Leap of Faith" stair set, the gym (accessible when the school bell is ground during a specific time window in console versions; in GBA, simplified triggers are often used), and the Openseam area.  
* **Objectives:** Wallride 5 Bells, Grind 5 Tables, Kickflip TC's Roof Gap, Collect Hall Passes[20] .  
* **Adaptation:** The moving golf cart driver, a dynamic hazard in the console version, was removed to save processing power[2] . The level's scale can be disorienting in isometric view, forcing players to memorize rail locations that may be obscured by buildings.

### 5.3 Marseille (France)
Based on the real-world skatepark, this level focuses on flow and transition skating with interconnected bowls.

* **Layout:** A complex arrangement of bowls, spines, and a street section with lamp posts.  
* **Format:** This is a **Competition Level**. Instead of completing 10 goals, players perform a one-minute run and are judged by AI judges. Players must secure a medal (Bronze, Silver, or Gold) to advance[20] .  
* **Secrets:** Knocking down a specific wooden pole opens a subterranean crypt area, a secret retained from the console version[21] .

### 5.4 NY City (New York)
A dense metropolitan level divided into a park area and a street/subway area.

* **Layout:** Features the "Joey's Sculpture" statuary, subway tracks, and park paths.  
* **Objectives:** Collect 5 Subway Tokens, Ollie the Hydrants, Grind the Subway Rails[22] .  
* **Adaptation:** The bustling traffic, including the moving yellow taxis that could run over the skater, was removed for the GBA port[2] . This creates a safer but more sterile environment compared to the console original. The darker textures of the asphalt and buildings drew criticism for being difficult to see on the original non-backlit GBA screen[9] .

### 5.5 Venice Beach (California)
A colorful, sun-drenched level combining boardwalks, graffiti walls, and rooftop transfers.

* **Layout:** Key landmarks include the graffiti pits, the "Venice Ledge," and the seaside rails.  
* **Objectives:** Ollie the Magic Bum 5x, Collect 5 Spray Cans, Tailslide the Venice Ledge, Collect S-K-A-T-E[23] .  
* **Details:** The "Magic Bum" objective requires the player to find a homeless character who changes location after each jump. The GBA version replicates this scripted movement, forcing players to explore the entire map[23] .

### 5.6 Skatestreet (Ventura)
A complex indoor skatepark and the second Competition Level.

* **Layout:** A maze of ramps, rails, and a massive half-pipe.  
* **Adaptation:** The "Rail Garden" secret area outside is included. The level's intricate geometry and overlapping rails make extensive use of the engine's transparency masking to keep the skater visible[15] .

### 5.7 Philadelphia (Pennsylvania)
An unlockable level set in an urban plaza.

* **Layout:** Features a large fountain, planters, and telephone wires.  
* **Objectives:** Drain the Fountain (by grinding the valves), Grind the Telephone Wires.  
* **Unlockable:** Grinding the telephone wires unlocks a secret skate park area, extending the level map[24] .

### 5.8 Bonus and Legacy Levels
* **The Warehouse (Troy, NY):** Unlocked from the start or early in progression, this is the iconic first level from *Tony Hawk's Pro Skater 1*. Objectives were expanded to 10 for this game, including "Destroy 5 Crates" and "5-0 the Big Rail"[22] .  
* **The Bullring (Mexico):** A competition level set in a bullring, featuring a massive loop-the-loop. The bull manure piles from the console version are present as hazards[25] .  
* **Chopper Drop (Hawaii):** A "half-level" consisting of a vert ramp on a boat/platform, focused purely on high scores.  
* **Skate Heaven:** The final unlockable level, set in a surreal outer-space environment with complex rail lines and high-gravity jumps.

### 5.9 GBA Exclusive: Rooftops (Boston)
A unique addition to the handheld version is the **Rooftops** level, which does not appear in the standard console release[24] .

* **Setting:** The level takes place across the tops of several skyscrapers at night, connected by wires, makeshift ramps, and pipes.  
* **Unlock Method:** Typically unlocked by achieving 100% completion with all characters[26] .  
* **Design Philosophy:** The level emphasizes precision and risk. Falling off the edge of a building results in a reset (and a bail animation).  
* **Key Gaps:** "Live Wire" (grinding the connecting cables between buildings) and "Top of the World" (reaching the highest point of the map)[27] .  
* **Note:** While *Tony Hawk's Pro Skater 2x* on Xbox featured a level called "Sky Lines" that also took place on rooftops, the GBA "Rooftops" level is a distinct layout built specifically for the isometric engine[28] .

## 6\. Character Roster
The character roster is identical to the console version, featuring 13 professional skaters. Each skater is defined by a specific style (Vert, Street, or All-Around) and a set of stats[29] .

### 6.1 Professional Skaters
| Skater | Style | Stance | Signature Special (Example) |
| :---- | :---- | :---- | :---- |
| **Tony Hawk** | Vert | Goofy | The 900, Sacktap 29 |
| **Bob Burnquist** | All-Around | Regular | Rocket Air, One Foot Smith |
| **Steve Caballero** | All-Around | Goofy | Hang Ten, Triple Kickflip |
| **Kareem Campbell** | Street | Regular | Ghetto Bird, Casper |
| **Rune Glifberg** | Vert | Regular | Christ Air, Kickflip 1 Foot Tail |
| **Eric Koston** | Street | Goofy | Pizza Guy, Fandangle |
| **Bucky Lasek** | Vert | Regular | Fingerflip Airwalk |
| **Rodney Mullen** | Street | Goofy | Darkslide, Casper to 360 Flip |
| **Chad Muska** | Street | Regular | Muska Nose Manual, Mute Backflip |
| **Andrew Reynolds** | Street | Regular | Triple Heelflip, Nosegrab Tailslide |
| **Geoff Rowley** | Street | Regular | Rowley Darkslide, Double Hardflip |
| **Elissa Steamer** | Street | Regular | Madonna Tailslide, Hospital Flip |
| **Jamie Thomas** | Street | Regular | Beni F-Flip, Laser Flip |

### 6.2 Unlockable and Secret Characters
* **Spider-Man:** The Marvel superhero appears as a fully playable secret character, a result of the licensing synergy between Activision's *Spider-Man* games (also developed by Vicarious Visions on handhelds) and the *Tony Hawk* series[30] . Spider-Man has unique physics and web-based tricks like the "Spidey Flip" and "Spidey Grind." In the console versions, he is unlocked by 100% completing the game with a Created Skater. Since the GBA version lacks a Create-A-Skater mode, he is unlocked via a specific cheat code (Up, Up, Down, Down, Left, Right, Left, Right, B, A, Start held with R) or by completing the game with specific criteria[32] .  
* **Mindy:** A female police officer character, unlocked via cheat or game completion[32] .  
* **80's Tony Hawk:** A throwback skin for Tony Hawk, unlocked by completing the career mode 100% with the standard Tony Hawk[33] .

## 7\. Audio Engineering: The "Chip-Rock" Soundtrack
One of the most significant deviations from the console version lies in the audio department. The home console versions of *Tony Hawk's Pro Skater 2* are famous for their licensed soundtrack featuring bands like Rage Against the Machine, Papa Roach, and Naughty by Nature[34] . However, the Game Boy Advance cartridges typically held only 8MB to 16MB of data, making the inclusion of CD-quality audio tracks impossible without severely compromising the game content[4] .

### 7.1 Original Composition
Rather than including heavily compressed, low-fidelity snippets of the licensed songs (a common practice in lesser ports), Vicarious Visions commissioned an entirely original soundtrack. The music was composed by **Manfred Linzner** of **Shin'en Multimedia**.35

Linzner composed a set of high-energy instrumental tracks that emulated the genres of the console soundtrack—skate punk, hip-hop, and rock—using the GBA's synthesizer. Tracks were given descriptive titles like "Get what ya got," "Burned Out," and "Bad Vibes" in the game's sound test menu[1] .

### 7.2 The GAX Sound Engine
The audio was powered by Shin'en Multimedia's **GAX Sound Engine**.1 This highly optimized middleware allowed the GBA's ARM7 processor to handle multi-channel audio mixing in software without dragging down the game's frame rate. The result was a soundtrack that, while distinct from the licensed songs, maintained the high-tempo energy required for the gameplay. Reviewers praised the original score, noting that the instrumental loops were less repetitive and annoying than short, digitized vocal clips would have been[2] .

## 8\. Critical Reception and Market Impact
### 8.1 Critical Acclaim
Upon its release, *Tony Hawk's Pro Skater 2* for GBA received universal acclaim. It is widely considered one of the best launch titles for the system and one of the greatest handheld games of all time.

* **IGN:** Awarded the game a **9.5/10**, giving it the "Editor's Choice" award. Craig Harris described it as a "technical marvel" and stated, "Of all the titles that were produced for the Game Boy Advance's US launch, this game is the top of the heap"[2] .  
* **GameSpot:** Scored the game **9.3/10**. Reviewer Jeff Gerstmann wrote, "The result is nothing short of the best portable skateboarding game ever made," praising the graphics and control adaptation[19] .  
* **Metacritic:** The game holds an aggregate score of **95/100**, placing it in the upper echelon of the platform's library[38] .

### 8.2 Awards
The game received numerous industry accolades:

* **BAFTA Interactive Entertainment Awards (2001):** Won the award for **Best Mobile Game**.38  
* **IGN Best of E3 2001:** Won **Best Handheld Game**, beating out first-party Nintendo titles like *Mario Kart Advance*.39  
* **National Academy of Video Game Testers and Reviewers (NAVGTR):** Nominated for multiple awards including "Outstanding Control Precision" and "Outstanding Graphics, Technical"[40] .

### 8.3 Commercial Performance
The game was a commercial success, ranking as one of the top-selling GBA launch titles in North America, second only to *Super Mario Advance* in June 2001[38] . Its success proved that there was a viable market for high-fidelity ports of "core" gamer titles on handheld devices.

## 9\. Legacy and Influence
The success of *Tony Hawk's Pro Skater 2* on GBA established Vicarious Visions as a technical powerhouse in the handheld market. Activision subsequently entrusted the studio with the GBA ports of the entire franchise:

* ***Tony Hawk's Pro Skater 3*** **(GBA):** Introduced the **Revert** mechanic and multiplayer capabilities via link cable[41] .  
* ***Tony Hawk's Pro Skater 4*** **(GBA):** Refined the visuals and removed the timer for a free-roaming career structure[41] .  
* ***Tony Hawk's Underground*** **& *American Sk8land*:** Eventually transitioned the series to a fully 3D (non-isometric) engine on the Nintendo DS, ending the isometric era.

The isometric engine developed for *THPS2* was also utilized in other Vicarious Visions titles, such as *Jet Grind Radio* (GBA) and *Spider-Man: Mysterio's Menace* 6, influencing the aesthetic and technical standards of third-party GBA development for years. By proving that the "unportable" could be ported, *Tony Hawk's Pro Skater 2* remains a defining artifact of the early 2000s handheld gaming landscape.

#### References
[1] Tony Hawk's Pro Skater 2 (Game Boy Advance) \- The Cutting Room Floor, accessed December 17, 2025, [https://tcrf.net/Tony\_Hawk%27s\_Pro\_Skater\_2\_(Game\_Boy\_Advance)](https://tcrf.net/Tony_Hawk%27s_Pro_Skater_2_\(Game_Boy_Advance\))  
[2] Tony Hawk's Pro Skater 2 \- IGN, accessed December 17, 2025, [https://www.ign.com/articles/2001/06/14/tony-hawks-pro-skater-2-9](https://www.ign.com/articles/2001/06/14/tony-hawks-pro-skater-2-9)  
[3] Tony Hawk's Pro Skater 2 \- Wikipedia, accessed December 17, 2025, [https://en.wikipedia.org/wiki/Tony\_Hawk%27s\_Pro\_Skater\_2](https://en.wikipedia.org/wiki/Tony_Hawk%27s_Pro_Skater_2)  
[4] Interview with the Tony Hawk 2 GBA Team \- IGN, accessed December 17, 2025, [https://www.ign.com/articles/2001/05/04/interview-with-the-tony-hawk-2-gba-team](https://www.ign.com/articles/2001/05/04/interview-with-the-tony-hawk-2-gba-team)  
[5] Hands on: Tony Hawk Pro Skater 2 for Game Boy Advance \- IGN, accessed December 17, 2025, [https://www.ign.com/articles/2001/03/24/hands-on-tony-hawk-pro-skater-2-for-game-boy-advance](https://www.ign.com/articles/2001/03/24/hands-on-tony-hawk-pro-skater-2-for-game-boy-advance)  
[6] Vicarious Visions Interview \- Nintendo World Report, accessed December 17, 2025, [https://www.nintendoworldreport.com/interview/2139/vicarious-visions-interview](https://www.nintendoworldreport.com/interview/2139/vicarious-visions-interview)  
[7] The Making Of: Tony Hawk's Pro Skater 2's Surprisingly Stellar GBA Port \- Time Extension, accessed December 17, 2025, [https://www.timeextension.com/features/the-making-of-tony-hawks-pro-skater-2s-surprisingly-stellar-gba-port](https://www.timeextension.com/features/the-making-of-tony-hawks-pro-skater-2s-surprisingly-stellar-gba-port)  
[8] Tony Hawk's Pro Skater 2 review | Eurogamer.net, accessed December 17, 2025, [https://www.eurogamer.net/r-thps2-gba](https://www.eurogamer.net/r-thps2-gba)  
[9] Tony Hawk's Pro Skater 2 Review for Game Boy Advance \- GameFAQs, accessed December 17, 2025, [https://gamefaqs.gamespot.com/gba/471231-tony-hawks-pro-skater-2/reviews/21281](https://gamefaqs.gamespot.com/gba/471231-tony-hawks-pro-skater-2/reviews/21281)  
[10] Game Boy Advance Instruction Manuals: Tony Hawk's Pro Skater 2, accessed December 17, 2025, [http://www.world-of-nintendo.com/manuals/game\_boy\_advance/tony\_hawks\_pro\_skater\_2.shtml](http://www.world-of-nintendo.com/manuals/game_boy_advance/tony_hawks_pro_skater_2.shtml)  
[11] Tony Hawk's Pro Skater 2 \- Guide and Walkthrough \- Game Boy Advance \- GameFAQs, accessed December 17, 2025, [https://gamefaqs.gamespot.com/gba/471231-tony-hawks-pro-skater-2/faqs/12035](https://gamefaqs.gamespot.com/gba/471231-tony-hawks-pro-skater-2/faqs/12035)  
[12] "The Next Level" \- Game Review \- Tony Hawk's Pro Skater 2, accessed December 17, 2025, [https://www.the-nextlevel.com/reviews/handheld/thps2/](https://www.the-nextlevel.com/reviews/handheld/thps2/)  
[13] Lights out, Guerrilla Radio: TONY HAWK'S PRO SKATER 2 (2000/2001) \- 3rd Voice Gaming, accessed December 17, 2025, [https://3rdvoicegaming.com/2022/07/15/lights-out-guerrilla-radio-tony-hawks-pro-skater-2-2000/](https://3rdvoicegaming.com/2022/07/15/lights-out-guerrilla-radio-tony-hawks-pro-skater-2-2000/)  
[14] OG THPS-2 Reverts? \- Reddit, accessed December 17, 2025, [https://www.reddit.com/r/THPS/comments/1di5zu7/og\_thps2\_reverts/](https://www.reddit.com/r/THPS/comments/1di5zu7/og_thps2_reverts/)  
[15] Tony Hawk's Pro Skater 2 Review for Game Boy Advance \- GameFAQs, accessed December 17, 2025, [https://gamefaqs.gamespot.com/gba/471231-tony-hawks-pro-skater-2/reviews/172524](https://gamefaqs.gamespot.com/gba/471231-tony-hawks-pro-skater-2/reviews/172524)  
[16] Tony Hawk's Pro Skater 2 (USA), accessed December 17, 2025, [https://www.videogamemanual.com/gba/Tony%20Hawk's%20Pro%20Skater%202%20(USA).pdf](https://www.videogamemanual.com/gba/Tony%20Hawk's%20Pro%20Skater%202%20\(USA\).pdf)  
[17] Create-A-Skater and Character Customization \- Tony Hawk's Pro Skater 2 Guide \- IGN, accessed December 17, 2025, [https://www.ign.com/wikis/tony-hawks-pro-skater-2/Create-A-Skater\_and\_Character\_Customization](https://www.ign.com/wikis/tony-hawks-pro-skater-2/Create-A-Skater_and_Character_Customization)  
[18] THPS2 Level Guide \- Gameboy Advance \- Hangar \- Planet Tony Hawk, accessed December 17, 2025, [http://planettonyhawk.gamespy.com/View7117.php?view=thps2\_faqs\_guides.Detail\&id=10](http://planettonyhawk.gamespy.com/View7117.php?view=thps2_faqs_guides.Detail&id=10)  
[19] Tony Hawk's Pro Skater 2 Review \- GameSpot, accessed December 17, 2025, [https://www.gamespot.com/reviews/tony-hawks-pro-skater-2-review/1900-2770362/](https://www.gamespot.com/reviews/tony-hawks-pro-skater-2-review/1900-2770362/)  
[20] Tony Hawk's Pro Skater 2 \- Guide and Walkthrough \- Game Boy Advance \- GameFAQs, accessed December 17, 2025, [https://gamefaqs.gamespot.com/gba/471231-tony-hawks-pro-skater-2/faqs/14586](https://gamefaqs.gamespot.com/gba/471231-tony-hawks-pro-skater-2/faqs/14586)  
[21] Level Guides \- Tony Hawk's Pro Skater 2 Guide \- IGN, accessed December 17, 2025, [https://www.ign.com/wikis/tony-hawks-pro-skater-2/Level\_Guides](https://www.ign.com/wikis/tony-hawks-pro-skater-2/Level_Guides)  
[22] THPS2 Level Guide \- Gameboy Advance \- Warehouse \- Planet Tony Hawk \- GameSpy, accessed December 17, 2025, [https://planettonyhawk.gamespy.com/Viewf87f.php?view=thps2\_faqs\_guides.Detail\&id=14](https://planettonyhawk.gamespy.com/Viewf87f.php?view=thps2_faqs_guides.Detail&id=14)  
[23] Venice Beach \- Tony Hawk's Pro Skater 2 Guide \- IGN, accessed December 17, 2025, [https://www.ign.com/wikis/tony-hawks-pro-skater-2/Venice\_Beach](https://www.ign.com/wikis/tony-hawks-pro-skater-2/Venice_Beach)  
[24] Exclusive levels in the early THPS games \- Reddit, accessed December 17, 2025, [https://www.reddit.com/r/THPS/comments/hdccdo/exclusive\_levels\_in\_the\_early\_thps\_games/](https://www.reddit.com/r/THPS/comments/hdccdo/exclusive_levels_in_the_early_thps_games/)  
[25] Hangar \- Tony Hawk's Games Wiki \- Fandom, accessed December 17, 2025, [https://tonyhawkgames.fandom.com/wiki/Hangar](https://tonyhawkgames.fandom.com/wiki/Hangar)  
[26] Rooftops, Boston | Tony Hawk's Games Wiki \- Fandom, accessed December 17, 2025, [https://tonyhawkgames.fandom.com/wiki/Rooftops,\_Boston](https://tonyhawkgames.fandom.com/wiki/Rooftops,_Boston)  
[27] THPS2 GBA Transfer Listing \- Rooftops \- Planet Tony Hawk, accessed December 17, 2025, [http://planettonyhawk.gamespy.com/Viewd9c8.php?view=thps2\_faqs\_guides.Detail\&id=97](http://planettonyhawk.gamespy.com/Viewd9c8.php?view=thps2_faqs_guides.Detail&id=97)  
[28] Sky Lines | Tony Hawk's Games Wiki \- Fandom, accessed December 17, 2025, [https://tonyhawkgames.fandom.com/wiki/Sky\_Lines](https://tonyhawkgames.fandom.com/wiki/Sky_Lines)  
[29] Tony Hawk's Pro Skater 2 \- Special Moves List \- Game Boy Advance \- By OTACON120, accessed December 17, 2025, [https://gamefaqs.gamespot.com/gba/471231-tony-hawks-pro-skater-2/faqs/11932](https://gamefaqs.gamespot.com/gba/471231-tony-hawks-pro-skater-2/faqs/11932)  
[30] Tony Hawk's Pro Skater 2X: SPIDER-MAN at Sky Lines \- YouTube, accessed December 17, 2025, [https://www.youtube.com/watch?v=DMrPaM-3keA](https://www.youtube.com/watch?v=DMrPaM-3keA)  
[31] Why Spider-Man Isn't In Tony Hawk's Pro Skater 1 \+ 2 \- Screen Rant, accessed December 17, 2025, [https://screenrant.com/spider-man-thps-2-secret-character-skater-unlock/](https://screenrant.com/spider-man-thps-2-secret-character-skater-unlock/)  
[32] GBA Cheats \- Tony Hawk's Pro Skater 2 Guide \- IGN, accessed December 17, 2025, [https://www.ign.com/wikis/tony-hawks-pro-skater-2/GBA\_Cheats](https://www.ign.com/wikis/tony-hawks-pro-skater-2/GBA_Cheats)  
[33] Tony Hawk's Pro Skater 2 Cheats, Codes, and Secrets for Game Boy Advance \- GameFAQs, accessed December 17, 2025, [https://gamefaqs.gamespot.com/gba/471231-tony-hawks-pro-skater-2/cheats](https://gamefaqs.gamespot.com/gba/471231-tony-hawks-pro-skater-2/cheats)  
[34] Various – Tony Hawk's Pro Skater 2 | Releases \- Discogs, accessed December 17, 2025, [https://www.discogs.com/master/2717591-Various-Tony-Hawks-Pro-Skater-2](https://www.discogs.com/master/2717591-Various-Tony-Hawks-Pro-Skater-2)  
[35] Tony Hawk's Pro Skater 2 Credit Information \- GameFAQs, accessed December 17, 2025, [https://gamefaqs.gamespot.com/gbc/444438-tony-hawks-pro-skater-2/credit](https://gamefaqs.gamespot.com/gbc/444438-tony-hawks-pro-skater-2/credit)  
[36] Tony Hawk's Pro Skater 2 Credit Information \- GameFAQs, accessed December 17, 2025, [https://gamefaqs.gamespot.com/gba/471231-tony-hawks-pro-skater-2/credit](https://gamefaqs.gamespot.com/gba/471231-tony-hawks-pro-skater-2/credit)  
[37] Tony Hawk's Pro Skater 2 GBA Review \- Nintendo World Report, accessed December 17, 2025, [http://www.nintendoworldreport.com/review/3783/tony-hawks-pro-skater-2-gba-game-boy-advance](http://www.nintendoworldreport.com/review/3783/tony-hawks-pro-skater-2-gba-game-boy-advance)  
[38] Tony Hawk's Pro Skater 2 (GBA video game) \- Wikipedia, accessed December 17, 2025, [https://en.wikipedia.org/wiki/Tony\_Hawk%27s\_Pro\_Skater\_2\_(GBA\_video\_game)](https://en.wikipedia.org/wiki/Tony_Hawk%27s_Pro_Skater_2_\(GBA_video_game\))  
[39] IGNpocket's Best of E3 2001 \- IGN, accessed December 17, 2025, [https://www.ign.com/articles/2001/05/24/ignpockets-best-of-e3-2001](https://www.ign.com/articles/2001/05/24/ignpockets-best-of-e3-2001)  
[40] 2001 Awards \- NAVGTR, accessed December 17, 2025, [https://navgtr.org/2001-awards/](https://navgtr.org/2001-awards/)  
[41] Best Tony Hawk Games Of All Time | Nintendo Life, accessed December 17, 2025, [https://www.nintendolife.com/guides/best-tony-hawk-games-of-all-time?page=2](https://www.nintendolife.com/guides/best-tony-hawk-games-of-all-time?page=2)