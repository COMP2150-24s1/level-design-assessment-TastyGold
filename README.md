[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: Phoebe Johns
### Student number: 47863021

## 1. Player Experience

### 1.1. Discovery
| | |
|---|---|
| ![Breakable walls after picking up staff](DocImages/discovery1.png) | ![First enemy encounter](DocImages/discovery2.png) |

The first encounter after picking up the staff involves two breakable columns. It is important to provide the player with a playground to experiment with and understand new mechanics before they are tested on them. This is a philosophy that I tried my best to cling to when designing this level and its sections. The next thing the player will see after breaking the columns is an enemy. This encounter lets the player prove they can handle combat before having to combine it with platforming, more enemies, or other mechanics.

| | |
|---|---|
| ![](DocImages/discovery3.png) | ![](DocImages/discovery4.png) |

Every main section and new mechanic follows a simple design formula. First the player is introduced to the mechanic or mechanics in a safe, experimental environment. After the introductory encounter, a series of developments on those ideas are presented. Each of these encounters present new combinations of established ideas to encourage the player to explore how they can interact with the mechanic. After the player has explored several ideas and approaches regarding a specific mechanic, they reach a ‘final exam’ that tests both their knowledge and execution of the mechanics they have learned. Each of the three main sections crescendo in these final exam encounters, with each section posing a greater challenge than the last.

### 1.2. Drama

What is the intensity curve? How does your design facilitate increasing yet modulating intensity, with moments of tension and relief? 
This process of learning mechanics and building on ideas, as well as the use of the ‘final exam’ design philosophy serves to create a satisfying dramatic arc over the course of the level. In this way, each section serves as a complete dramatic arc of its own with its own peaks and troughs to keep the player in the flow channel as described by Mihaly Csikszentmihalyi. 

| | |
|---|---|
| ![](DocImages/drama1.png) | ![](DocImages/drama2.png) |

Each section concludes with a wind-down in intensity; the player isn’t immediately out of danger after completing the final exam of a section. The danger in these wind-down segments is low, but prevents a jarring drop in the intensity of the level. These sections, always immediately following the final exam, act as one final moment of tension before there can be resolution. They serve the same purpose as the final chord in a piece of music before the resolution, before the cadence is complete. This serves to sweeten and emphasise the relief that the player feels when finally reaching that checkpoint - when finally collecting that key.

### 1.3. Challenge

Players usually have the freedom to choose how they approach an encounter in how they choose to balance their focus between platforming and combat. Some players may choose to defeat every enemy they see as to make platforming easier, while others may put their efforts into evading and manoeuvring around enemies and projectiles. To encourage the player to engage with both systems, certain encounters are staged to heavily favour one approach over another, to give the player practice in all of the game's systems. This also gives them a chance to experiment with different play styles so that by the final exam segments they can have the freedom to express how they wish to play.

There are two main types of challenge in my level: combat and platforming. Both of these types of challenge are taught to the player separately at first and are gradually combined to create interesting encounters. Each encounter serves as development on something that came before. The most challenging encounters in this level are those that combine the mechanics of platforming and combat, requiring the player to balance their priorities and multitask.

### 1.4. Exploration

| | |
|---|---|
| ![](DocImages/exploration1.png) | ![](DocImages/exploration2.png) |

My level design makes liberal use of background tiles and surrounding geometry as tools to inform the feeling of each space and encounter. Despite all sections of the level sporting the same tileset and assets, contrasting spaces and feelings can be created through the use of background tiles, ceilings and stalactite formations. Using both positive and negative spaces to convey context and levels of comfort/danger to the player serves to create feelings in players that drive them forward through the level. 

| | |
|---|---|
| ![](DocImages/exploration3.png) | ![](DocImages/exploration4.png) |

Throughout the level there are several little platforms or ledges off the beaten path that the player can choose to investigate. While the topological structure of the level is very linear, small offshoots such as these offer the player a sense of freedom of exploration. The player is usually rewarded for their efforts with one or two heart pickups, which serve as an incentive to explore these offshoots when they see them again. The frequency of these optional heart pickups means that if the player is struggling for health, they can modify their playstyle to focus more on searching and collecting these heart refills.


## 2. Core Gameplay

### 2.1. Checkpoints

![](DocImages/checkpoint.png)
Checkpoints do not become mechanically relevant in the level until the introduction of acid in the second main section. Though, I still have used them to signify to the player when they have overcome an obstacle or to suggest that one may be coming.

### 2.2. Weapon Pickup (Staff)

![](DocImages/staff.png)
The player is given a safe task to complete with the new mechanic of the staff before they are challenged with an enemy encounter. This ensures that when they do encounter the enemy they already understand swinging the staff.

### 2.3. Spikes

![](DocImages/spikes.png)
This is the first encounter that involves the player interacting with spikes. Previous appearances of spikes in the level are purely decorative. The very first platforming area at the start of the level has spikes under a floating platform to clarify to the player that tiles cannot be jumped through; this remains true until the explicit introduction of pass-through platforms later on.

### 2.4. Chompers

![](DocImages/chomper.png)
A chomper serves as the first encounter that the player must use the staff. Enemies play a significant role in the level, and so introducing combat very early is important.

### 2.5. Health Pickups

![](DocImages/heartpickup.png)

The player sees the heart pickup before they are able to access it, piquing interest in how to acquire it. After they drop they will see the enemy guarding the extra heart and can choose how they wish to engage with the risk/reward of obtaining it.

### 2.6. Spitters

![](DocImages/spitter.png)
The spitter is introduced on a high perch guarded by spikes. This is to ensure the player doesn’t jump and swing at it straight away like the rest of the enemies and has a chance to observe how it shoots its projectiles.

### 2.7. Keys

![](DocImages/key.png)
Keys serve as the reward for completing a main section. They are not hidden or optional as they are mandatory to open the exit door. The player can see the key during the wind down section contributing to the tension and relief that it serves.

### 2.8. Moving Platforms

![](DocImages/movingplatform.png)
Moving platforms are introduced to the player first in a safe environment. In the final level I added a spitter and heart pickup underneath so the player has something to do in case they miss the platform rising and have to wait.

### 2.9. Acid

![](DocImages/acid.png)
Acid serves as an additional layer of depth to the platforming in the level. I introduced it at the start of the second main section to give the player time to acclimate themselves with the controls before introducing punishment for missing a jump.

### 2.10. Passthrough Platforms

![](DocImages/passthrough.png)
Passthrough platforms are placed in a ladder-like formation to hint to the player that they can be jumped up through directly. This is not geometry they have dealt with with solid tiles yet and so will likely now attempt to jump straight up.

### 2.11. Weapon Pickup (Gun)

![](DocImages/gun.png)
It was important to give the player an immediate reason to use the gun over the staff. By this point they have become comfortable with using the staff to defeat enemies so the task was challenging that comfort.


## 3. Spatiotemporal Design
(Recommended: right click -> open image in new tab)
 
### 3.1. Molecule Diagram
![](DocImages/Comp2750_moleculediagram.drawio.png)

### 3.2. Level Map – Section 1
![](DocImages/Comp2750_level_section1.drawio.png)

### 3.3. Level Map – Section 2
![](DocImages/Comp2750_level_section2.drawio.png)

### 3.4. Level Map – Section 3
![](DocImages/Comp2750_level_section3.drawio.png)

## 4. Iterative Design

| | |
|---|---|
| ![](DocImages/iterative1.png) | ![](DocImages/iterative2.png) |
| ![](DocImages/iterative3.png) | ![](DocImages/iterative4.png) |
The final exam of the third main section is a prime example of how iterative design was used to bring an encounter from concept to final implementation. The core idea of this encounter is a moving platform that constantly moves over acid and the player has to fight to stay on the platform to reach the end goal. Informed by previous encounters and finding moving platforms to cause a lot of waiting when they are not in the right spot, the concept of a platform carousel came to mind. Instead of one platform that moves back and forth over the acid, several moving platforms would be used moving in a loop, like a carousel. This meant that there would be a lot less waiting for a platform to return if the player had to try again.

| Prototype | Final |
|---|---|
| ![](DocImages/iterative5.png) | ![](DocImages/iterative6.png) |
| ![](DocImages/iterative7.png) | ![](DocImages/iterative8.png) |
Iterative design was used to create all of the encounters in this level. The level was built on an encounter-by-encounter basis and each followed the same development pipeline. Encounters started in a grey-box-esque form (the final tileset is still used as it automatically tiles and can easily be modified); the main idea for the encounter is present. In the first of the above examples, the main idea is having multiple platforms that rise and sink in sequence to allow the player to jump across. In lieu of playtesting, doing the same jump 4 times back to back didn’t feel very engaging, and so a change was made to widen the gap between the 2nd and 3rd platforms forcing the player to jump higher and further.

![](DocImages/spitterintro.png)
If I were to apply iterative design to further improve one of the existing encounters in the game, it would be the introduction to spitters. In playtesting, I found a common issue to be the player bonking their head on the perch that it is sitting on. The level geometry could be better suited for going under and around a spitter like this. The limited view radius of the spitters makes an encounter like this hard to balance. To achieve a more fluid player experience, the geometry of this encounter could be taken back to the prototyping phase. Several varied small level maps or grey-box prototypes could be created to experiment with ways to improve this encounter and the introduction of this mechanic. Alternatively, moving sections of the level geometry around one tile at a time and experimenting with multiple playtesters would allow for examination of what modifications could work better than this iteration.

## Generative AI Use Acknowledgement
No generative AI or other text generation software was used for this document.


