
Donghwan Kim\
https://dgkim16.github.io/optionalPRJ
# Rubrics (to-do list)


### C rubric
[X] Uses BST for managing turns\
[X] Uses RBT for managing turns\
[X] Load data from JSON files\
[X] Create a working speed system\
[X] Hide non-affected allies that blocks the view of the Camera\
[X] Both skill button works, and are only visible when it is player's turn\
[X] Turn starts only when all animations are finished.\
[X] There's an indication of some sort that the game finished; that is, loop terminates at some point.\
[X] Communication between animator and script works\
[X] Successful initialization\
[X] Replace resources (texture, objects) to more 'formal' characters.
 
### B rubric
---
[X] Dead aren't targeted and can not be targeted.\
[X] Resolves the edge case where clones of enemies don't break the tree.\
[X] Make use of the animator override controller\
[] Add 'buff' system to the game.\
[X] Enemies actually do perform an action when their turn comes\
[X] There is a random aggro-target system \
[X] Size is less than 100mb (allows upload to & depolyment via github pages)

### A rubric
---
[X] Implement actual working BAV (spd) mechanism used in the original game.\
[X] Implement actual aggro mechanism used in the original game.\
[] Implement actual dmg equation from the original game.\
[X] You can modify data (character stats) in start screen\
[X] Implement 3rd skill (ult) that works & is executable\
[X] Make shader reflect the character's ult value.\
[X] Add a condition for skill 2 (requires skillpoint for execution)\
[X] Make skill 1 give skillpoint\
[] Make enemies smarter (enemies can buff each other)\
[X] Be able to identify who will be affected by player's action (while awaiting for execution by player input) by looking at turn panels\
[X] Create documentation (+ attributions)


### A** rubric (Highly doubt these are possible in 2 weeks.)
---
[?] There's no bug\
[X] Implement a priority queue for the current 'turn'.\
[] Add 'break effect / weakness' mechanism to the game\
[] Implement a 'wave' system : in a single battle, the next 'wave' of monsters join the battle only when the current wave of enemies are wiped\
[] Use deep learning to create a model that survives as long as possible.\
[] Make the game 'rogue-like'

### Features added post-meeting or aren't in rubric
---
[X] Added Indicators for how much HP changed, so one can clearly see how much hp changed by action\
[X] Added Auto and speed changer\
[X] Added heal skill\
[X] Added more motions & multi-hit mechanism\
[X] Improved camera to show relevant characters within its frustrum\
[X] All animator controllers are now replaced with AnimatorControllerOverrides\



### Attribution
---
Robot Kyle - by Unity Technologies, Unity Asset Store, Unity Companion License\
Main menu music - Music by Bensound, License code: STEVGPKNYNB72BDH\
Battle music - Music generated using Suno. https://suno.com/song/5fd88f2f-6d1d-43ae-a92f-30ec229cece9\
Button click sounds - Published by Michsky, Unity Asset Store, Unity Standard License\
hit SFX - Minecraft villager hit sound\
heal SFX - https://youtu.be/eb3Q2SCkd1E\
skybox - by PULSAR BYTES, Unity Asset Store, Unity Standard License\
motions - all from Mixamo\

