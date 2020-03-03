# OddestSea Documentation
This is a comprehensive game design document for the project and will be updated frequently as changes are made throughout development.

An early release of OddestSea is currently available for download on [itch.io](https://oddestsea.itch.io/oddest-sea) and has a planned final release Spring 2020.

# Table of Contents
## Introduction

 - [Concept](#concept-statement)
 - [Unique Selling Points](#unique-selling-points)
 - [Audience](#target-audience)

 ## Experience
 

 - [Core Loop](#core-loop)
 - [Player Experience](#player-experience)
 - [Key Moments](#key-moments)
 - [Objectives](#player-objectives)

 ## Mechanics
 

 - [Sailing](#sailing)
 - [Environment](#environment)
 - [Monsters](#monsters)
 - [Light](#light)

 ## Art & Visuals
 
 

 - [Assets](#assets)
 - [Visual Aesthetic](#visual-aesthetic)
 - [User Interface](#user-interface)
 - [Objects](#objects)

 ## Music & Audio
 

 - [Soundscape & SFX](#sfx)
 - [Music](music)

 ## Technical Documentation
 

 - [Conventions](#conventions)

 
 # Concept
## Concept Statement
OddestSea is a fast-paced sailing game about navigating a desolate sea, where the player must evade monsters and reach the lone lighthouse at the center.

## Unique Selling Points
### Hand-Painted Style
Like the grunge of hand-crafted textures and designs? Like a game where the only thing between life and death is your own quick wit? Then this is the game for you.

### Evasion-focused Encounters
Outwit fearsome monsters and put your sailing skills to the ultimate test. In this game you cannot afford to sit still. Use whatever resources you can to your advantage, or else the very beast that is the Oddest Sea will drag you to its darkest depths.

### A Pitch Black World
The encroaching darkness is always hungry, and you're the only bait in sight. The ship's lanterns may keep the shadows at bay, but even those are prone to fail. Cling to the light of the littered buoys or else face the beasts of the Oddest Sea in total darkness.

## Concept Paragraph
OddestSea is a game about sailing through a dark and treacherous sea of craggy rocks and vicious sea monsters lurking in the waves. The player must use their sailing skills and wits in order to flit from buoy to buoy, using the light to stave off the monsters in the dark. Various objects present in the environment can be used to their advantage to outplay the vicious creatures, but plenty more exists to destroy them. Their only salvation from the ruinous dark is the light of a distant lighthouse in the center of the vast sea. 

## Target Audience
* Players who enjoy high difficulty games, where making any wrong decision is the difference between life and death.
* Players who like the thrill of overcoming seemingly unfathomable challenges.

## Platform
OddestSea is planned for release the Summer of 2020 only on Steam.


# Experience
Detailed pages of specific game mechanics and objectives can be found by the links below.
* [Game Mechanics](#mechanics)
* [Game Objects](#objects)

## Core Loop
![Core Game Loop](https://github.com/rockretep/oddestsea/blob/master/documentation%20resources/core%20loop.png)

In OddestSea, the majority of play time will be spent sneaking around and fleeing monsters. The player will encounter various obstacles to be avoided. The player must navigate the hazardous obstacle course in order to reach the lighthouse at the center of the map. In between the player and the lighthouse are buoys that serve as safety zones where they can rest for a brief moment. Once the player reaches the lighthouse, they win the game.

## Player Experience
In this game, the player controls a small and lonely sailboat, which has been trapped in a dark, corrupted sea where deadly monsters roam freely and their only hope of salvation is to reach the glowing lighthouse at the center. The player must fulfill their role of the pursued, as the creatures and obstacles that call the Oddest Sea their home will stop at nothing to sink the ship. With no weapons or friends to help, this game is the ultimate test of stamina and overcoming impossible odds. The player should feel like a survivalist as they use what few resources they have to prepare themselves and continue forward. They should feel a subtle tension at all times, as well as a brief respite for each obstacle they avoid and each stretch of sea they are able to cross before reaching the next buoy.

## Key Moments
A play session of OddestSea will be approximately 10 minutes length-- from the time the player starts the game, to when they win the game (or die). Throughout playing OddestSea, the player will be striving to reach specific checkpoints during their play session: Buoys and the Lighthouse.
One of the key struggles the player must overcome is the constant threat of monsters or obstacles that lay in their path. While trapped in the Oddest Sea, the player should feel a subtle tension that is constantly ready to spike, whether it be due to a monster that has begun the chase, or the feeling of being caught in a tight spot and having to sail carefully out of harm's way.
One of the most frequent and major key victories of the game occurs whenever the player manages to reach a buoy. This moment will be signified by a musical cue that will vastly contrast from the usual tension experienced throughout the game. The player should view this as a moment of respite-- a comforting melody inspiring them to keep going even when things look grim.
Another key moment and resolution point for the player is when they finally reach the central lighthouse. Paired with a final musical cue, this moment should feel like an absolution from every challenge and near-death experience the player has had to overcome. The tension the player has should immediately vanish as they dock at the lighthouse and reflect on their journey as they finally escape the treacherous waters of the Oddest Sea.

## Player Objectives

### The Lighthouse
In OddestSea, the main objective is the lighthouse at the center of the world. Similar to the function of the mountain in Journey, the player can see the lighthouse from any point on the map, but the path to the lighthouse isn't as clear, so they must navigate the various obstacles surrounding the lighthouse in order to reach it.

### The Buoys
Amidst the plethora of dangerous obstacles in the Oddest Sea, there are small safe havens on the player's way to the lighthouse. The buoys, placed sporadically and sparsely throughout the map, offer a respite from the constant anxiety of fleeing monsters and racing around jagged rocks. While sitting within the light of a buoy, no monsters or obstacles can harm the player.

# Mechanics
The essential core mechanic of the game is sailing. Most other mechanics are derived solely from sailing and interact with sailing in some way, shape, or form. If the player cannot sail well or smartly, they cannot win the game. The player is rewarded for sailing well, and punished should they make a mistake. The environment provides various objects and encounters that also challenge or affect how the player sails. These encounters can either be one of two categories: monsters or environmental.

## Sailing
### Physics
The physics of sailing are affected by two main factors: the environment and the player’s input. At a complete stand still the player’s boat will not move forward, backward, or sideways any distance, but it will continue to rock as water moves underneath it (much like a ship docked at a harbor).

While the player is actively sailing, the water serves more so as resistance-- it will rock and pitch the player’s ship according to how large the wave is and what direction it is moving. For example, sailing into a large wave head-on will tilt the nose of the ship up, and then back down again as the boat sails over said wave. Sailing into a wave from the side will tilt the port or starboard side of the ship up (respectively), before tilting back down again to a neutral position. 

The boat will always try to remain on the surface of the water in an upright position. Water cannot get into the boat and it cannot damage the boat, it can only move the boat.

The boat cannot sail backwards. The only way to go backwards is to turn the boat completely around.

## Environment
Natural phenomena are the most common form of obstacle awaiting the player, and the most common reason a player might sail in a particular way. Most of these obstacles serve to change how the ship sails. There are three primary environmental hazards: rocks, seaweed, and wind.

### Rocks
One of the most common obstacles, and can either be found in isolation or giant clusters, and can be any shape or size, as long as they are larger than the player's boat. Rock clusters include both narrow paths the player can sail through, and large open coves. Essentially, rocks do not directly affect the physics of sailing, but they influence the player to sail in a particular way. If the player's ship collides with a rock, they will be knocked backwards.

### Seaweed
Seaweed directly changes the physics of sailing. While the player’s boat is within seaweed, there is greater resistance, thus dramatically slowing down the player’s ship. Once the boat has exited the seaweed, the player begins moving back at normal speed with normal resistance.

Seaweed clumps are visually represented by tall stalks that jut out of the water. Sailing into a seaweed clump, regardless of direction entered, will slow the player’s ship down by an arbitrary amount. Monsters are not affected by seaweed.

### Wind Pockets
Wind is generally a beneficial phenomena that directly affects how the player’s ship sails. Currently, there is only one main source of wind-- wind pockets. Wind pockets can be found anywhere in the world, and upon sailing into one (at any angle), the player's ship will experience a burst of sustained speed for as long as they remain within the wind pocket. Wind pockets will be graphically visualized by a wispy particle effect in the air where it is located, as well as a significant ‘breeze’ sound. Wind does not affect water or monsters. 

## Monsters
Monsters affect the player’s sailing in various detrimental ways and are to avoided at all costs. Monsters cannot be killed by the player directly, but can die by being lured into contact with buoys. Currently, there are 2 different classes of monsters: the Lamprey (small-size) and the Shark (large-size). The size of a monster equates to two different aspects of said monster: how large it is physically, and how much of a threat it poses to the player. Small monsters are at the bottom of that scale, acting more as a nuisance to the player rather than imminent death. Large monsters are a constant threat that pose a quick death for the player if they do not sail smartly. Large monsters are to be avoided at all costs.

### Lamprey

* Length of Encounter
  * 30~ seconds
* Experience
  * While the Lamprey is attached, the player should feel a sense of urgency and caution. They are not dead, but it is likely to happen if they do not find a light source quickly.

* Visuals
  * The Lamprey is the small-sized monster that can be found and is fairly common to encounter. Visually, they are represented by clusters or 'packs' that move and attack in a swarm. While attached to the ship, the Lamprey is represented by a worm-like model that sticks to the side of the player’s ship. 

* Mechanics
  * The Lamprey functions as an obstacle that is detrimental to the player’s sailing. When the player is not in range, the Lampreys will wander a small, circular perimeter collectively. Once a player comes within range of the Lamprey, it will actively pursue the player and try to attach to their ship. 
  * The only way the player can evade the Lamprey initially is by outrunning it. The Lamprey moves slightly slower than the Player’s base maximum speed, and thus, can be outrun if moving forward at maximum speed. Lampreys are most debilitating when encountered in condensed areas or areas over-populated with rocks and other hazards.
  * If the player outruns the Lamprey, it will simply go back to its idle roaming mode. If the Lamprey catches the player, it will ‘stick’ to the side of the player’s ship. While stuck by a Lamprey, the player’s movement controls will be inverted (camera and anchor remain with normal function).
  * To remove the Lamprey from the ship, the player must enter a light source, either by reaching a buoy, or reaching the lighthouse.

### Shark

* Length of Encounter
  * 10~ seconds.
* Experience
  * While the Shark is nearby, but not actively attacking, the player should feel aware and obligated to stay away from it. They should feel a sense of tension in that the danger is nearby, but cannot yet see them.
  * While the Shark has sighted the player and is pursuing, the player should feel a need to get away as quickly as possible.

* Visuals
  * The Shark is the large-sized monster that can be found in the game. Visually, they are represented by a 3D shark model where the top ⅓ of the model (the dorsal fin & some of the body) is peeking out of the water, while the rest remains below the surface. 

* Mechanics
  * While idle, the Shark will move back and forth between two points at an arbitrary speed, with a brief 2~ second pause between movements. The Shark's movements should overall be predictable so the player can make the choice of when to try and sneak past.
  * When spotting the player, the Shark will roar, shaking the screen and letting the player know that a chase has begun. While pursuing, the Shark will dart towards the player in a straight line at a slightly faster speed than the player's maximum speed. After reaching the player's last known position, if the player is not hit, the Shark will pause for 3~ seconds, and if the player is still in range, it will repeat the process. If the player is hit, the Shark will end the pursuit and return to idling.

### Eel

* Length of Encounter
  * 1-3 minutes.
* Experience
  * While the Eel has sighted the player and is pursuing, the player feels panicked, like a flight or fight response. They feel like they need to escape the area immediately and as quickly as possible.

* Visuals
  * The Eel is the largest monster that can be found in the game. Visually, they are represented by a 3D serpentine model where the arches of its body can be seen above water, while the rest remains below the surface. While actively pursuing, it will move in a serpentine pattern, swaying back and forth.

* Mechanics
  * If the player is spotted by an Eel, the Eel will let out a massive roar, which will immediately extinguish the light of all Buoy’s within an arbitrary range. After roaring, the Eel will submerge itself in the water. A spot in front of the player is chosen randomly and bubbles will appear, signaling that the eel is lurking underneath. If the player sails into these bubbles, the eel will spring from underneath, killing the player. If the player avoids the Eel’s trap, the Eel will reemerge after 3~ seconds, and chase the player if it is within an arbitrary of the Eel. If the player is not within range, it will re-submerge and repeat the process. The Eel, like the Shark, only abandons the chase if the player safely arrives at a buoy or somehow outruns it.

## Light
Light serves as a visual representation of the player’s health. The player’s boat has a collection of three 'wisps' of light that float around it. Each wisp is representative of 1 hp, for a total of 3. If the player sustains damage by a monster, one of the wisps will disappear. To regain health, players must visit buoys, which restore 1 hp per visit. If the player takes 3 points of damage without visiting a buoy, they lose the game.

# Art & Visuals
The style for the art and visuals for OddestSea is an illustration-like design that provides a drawn look to the all of the assets. This comprises of a specific color palette, black lining and shading, and hand-painted, messy textures that all work towards supporting the core ideas and themes of the game. All of the objects in the game are 3D models given this drawn texture, while UI assets are 2D, and drawn with the same painted/inked look in mind. [Specific details and the style guide can be found here.](https://docs.google.com/document/d/1GwRiVVY_wHldTxmJfjz9VI3PgRTarklvQEhkOi0aQt4/edit?usp=sharing)

## Assets
The assets appearing in the game have the illustration-like textures noted above. The lining of these objects are created via solid black lines, cross-hatching as a method of shading, and sections of solid black to provide further notions of shadow and form. Each asset's colors are painted by hand with a messy brush, assisting to provide the desired drawn effect. The colors used on each asset are determined by the game's color palette. The designated palette is composed of desaturated purples and low saturation yellows. White and black are permitted. The appearance of the sky and the water are created in-engine through shaders.

All 3D models are exported with the origin at 0 and with rotational values set for export into the Unity game engine. They are low poly, with poly count limits in place. 

![Color Palette](https://github.com/Headlesser/oddestdocumentation/blob/master/documentation%20resources/palette.png)

## Visual Aesthetic
The visuals present in the game are dark, but not dull. The theme of light and darkness is essential to provide the core experience in the game and support the vision; as such, the aesthetics reflect this. 

![Environment Concept](https://github.com/Headlesser/oddestdocumentation/blob/master/documentation%20resources/environmentconcept1.png)

To support the overall feeling of tense, lonely darkness that the player finds themselves in, the world is in a perpetual state of an evening on the edge of nightfall. The sky is dark and cloudy, with no light source via moon or stars to assist the player. The water is darker than the sky, and does not allow for anything below its surface to be seen. There is a constant layer of fog that hangs over the sea, providing the player with poor visibility. The vague outlines of the surrounding environment are just visible, providing the feeling that any distant object may in fact be an approaching monster. The overall darkness and visibility-inhibiting factors are key to invoking the emotion of traveling in the unknown. 

To combat the darkness of the game, when light is present, it serves as a place of serenity and safety. Light in the game ranges from the yellow of the palette to pure white, standing out through the thick fog and dark drudgery of the environment. Small touches of ambient light (such as lichen among the rocks) give the hope of surviving and persevering through the foreboding shadows, but do not provide enough light to combat it. Sources of light which do hold the power to provide the duality of light and dark are visible from a long distance. They cast a halo of light around them. This is especially important for the lighthouse; the rotating beam is visible, no matter where the player is, not letting them lose sight of their goal. 

![Lighthouse Concept](https://github.com/Headlesser/oddestdocumentation/blob/master/documentation%20resources/lighthouseconcept.png)

The environment acts as a method of informing the player with details as to what lives in this world they are in, and to assist in providing the tense feeling of being pursued and the isolation of their situation. The boat the player pilots is smaller than the threats they face, contributing to the fear of the lurking monsters. Large skulls and bones suggest that even monsters on a massive scale have a predator, making the player feel even smaller. Sharp rocks and large structures mimic the shape of monsters in the darkness. Shipwrecks tell the story of those previous who did not make it to the end of their journey. Shells and coral harbor homes for monsters to wander. 

## User Interface
The UI for the game is kept fairly minimal. As noted previously, the UI is supplied in a drawn style when applicable. There are 4 different game screens: the main menu screen, the options menu screen, the in-game screen, and the death menu screen. Each of these screens have a different UI setup.

The main menu is the starting screen for the game. It has three options, each represented by white text. The 'Start Game' button starts a new game, the 'Options' button allows the player to access the options menu, and the 'quit' button closes the program. These are on the left-hand side of the screen, in a small stack to keep interference with visuals minimal. 

The options menu allows the player to change various settings, such as basic adjustments, volume controls, window size, movement controls, and a quit option. The player can access this menu via the main menu, or during the game by pressing the ESCAPE key on the keyboard. 

The in-game screen is the screen in which the player plays the game. There are no UI elements visible here. 

The death screen is available when the player dies. It has two options, each represented by white text. The 'restart' button starts a new game, and the 'quit' button closes the program. These are centered on screen, in a small stack. 

## Objects
This is a comprehensive list of one of every kind of object that can be found within the game.

### Enemies
* Small Monster (Lamprey)
* Large Monster (Shark)
* ~~Giant Monster (Eel)~~

### Environmental Hazards
* Seaweed
* Wind
* Rock

### Landmarks
* Buoy
* Lighthouse
* Tall Mushroom
* Wrecked Ship
* Cracked Shell
* Spiral Shell
* Monster Skull
* Clam Shell
* Water

### Player
* Boat
* Wisp

### UI
* Start Menu
* Options Menu
* Restart Menu
* Start Button
* Brightness Slider
* Restart Button

# Music & Audio
The core sound design for OddestSea consists of an ambient soundscape with musical instances interwoven. We want to illustrate the hazardous nature of the sea to help elevate the feeling of tension we want to portray during general gameplay, while also providing contrasting symphonies during key moments such as reaching the lighthouse or resting at a buoy. Sound variation and management for the game is done using FMOD.

## SFX
The soundscape of the game should be primarily composed of ambient ocean details such as rolling waves, winds picking up and slowing down, and soft rumbling tones when passing by particularly large obstacles. Other SFX should mesh well with the soundscape and provide a sense of urgency depending on the situation. For example, the 'ship damaged' SFX is sudden and jarring, indicating to the player a feeling of danger and jostling the nerves.

## Music
The music of the game is primarily saved for moments of key importance or danger, though there is still a basic 'sailing' theme that plays layered over the soundscape. The sailing music should not overpower the soundscape, but rather merge into it so the sounds of the landscape can still be heard clearly. It should lean towards the side of ambient music rather than having a definitive melody. There are exactly three moments in the game that call for different music: the pursuit theme, the sneaking/sailing theme, and the respite theme. During these three moments, three vastly different compositions will play. All music in the game will be orchestral compositions.

For the monster pursuit theme, this should completely change the mood of the game compared to the normal sailing theme. The music should alert the player that they have been spotted by a monster and are being actively chased. The song should have a much quicker tempo, but not necessarily sound like a 'boss' theme. The music is there to create tension, and upon evading the monster and reaching a buoy, should fade out and be replaced by the calming respite theme.

The respite theme plays as the player reaches a buoy to rest at. This song should provide an calming or soothing feeling, not sounding too bombastic but rather a relaxed melody. It should sound free of tension and contrast appropriately from the pursuit or sailing themes.

# Technical Documentation
## Conventions
**OddestSea follows the general C# naming convention style.**
* Names of scripts, classes and methods should be written in PascalCase and clearly explain what functionality it provides in a short, concise manner. Specific examples of correctly formatted names for scripts are: ‘`AudioManager`’, ‘`BoatPhysics`’, ‘`AbsorbLightFromObj`’, ‘`PlayerCamera`’, ‘`Health`’, etc. Names should not be unnecessarily long or confusing to understand.
* Names of variables and method arguments should be written in camelCase and clearly describe what that variable is tracking or being used for in a short, concise manner. Specific examples of correctly formatted names for scripts are: ‘`player`’, ‘`maxSpeed`’, ‘`damageValue`’, etc. 
Note: If ever unsure, reference C# naming conventions for common good practices.
Code should be commented in areas where clarification might be needed for others to understand what the script or function in question is doing. Comments should be written in-line, next to the section of code being described. Written code should be as clean and condensed as possible to reduce clutter.
Any changes to other scripts, your own or someone else’s, must be communicated to all other members of the tech team.
* Anyone planning to work in editor to change scripts or the master scene should be familiar with pulling/pushing changes regularly and keep the repository up to date. Pushed changes should not include any files that you did not work on yourself. Any excess files should be removed from the commit before pushing. If work is incomplete and will cause the demo to break, those changes should not be merged to the master branch unless told otherwise by the producer or technical lead.
* Planned changes and changes in progress to any scripts, prefabs, or other code should be noted and communicated to the technical lead. Progress on any given task should be communicated to the technical lead throughout the work cycle. Issues encountered during task completion should also be communicated to other members of the team so adjustments can be made.
