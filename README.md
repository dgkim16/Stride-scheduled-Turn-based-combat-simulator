
Donghwan Kim\
https://dgkim16.github.io/optionalPRJ
# Rubrics (to-do list)

Title: Honkai StarRail simulator \
Summary:\
This project aims to mimik the battle system used in a video game titled Honkai StarRail using RBT data structure.\
Their battle system is inspired by, and therefore strongly resemblances that of, the series of video games called Persona.\
There are two groups A, consisting of playable agents, and B, consisting of enemy agents, in this game.\
Each agent has their own preassigned values, such as its name, skill ids, character id, speed, attack, max hp, and type.\
All agents mimik the characters with the type 'hunt' from the original game, so their types are fixated.\
Rounds are taken among all agents with resepct to their BAV values, which is initialized for each agent using their speed values.\
The panels alligned vertically on the left edge of the screen are updated when appropriate to reflect the BAV values in real time.\
The agent with the lowest BAV value takes the turn of that round, and all agents' BAV values are decremented by that lowest amount.\
If the agent is playable, the game waits for input from the user. Otherwise, the enemy agent attacks an ally.\
Which ally is attacked by the enemy agent, and equivalently the enemy agent automatically targeted by an playable agent in its turn, depends on their Hit probability.\
Hit probability for each character is computed using the Aggro value for each agent, which is computed with respect to its predetermined type.\
After the agent with the turn finished, if the game is not over, the agent that played the turn reset its BAV value, and the game goes on to ex\ecute the next round.


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
[X] Both skills aren't instakills\
[X] menu ( start & end )\
[X] Enemies actually do perform an action when their turn comes\
[X] There is a random aggro-target system \
[X] Background music\
[X] Background is not default\
[X] Size is less than 100mb (allows upload to & depolyment via github pages)

### A rubric
---
[X] Stylized menu ( end allows restart )\
[ㅁ] You can modify data (character stats) in start screen\
[X] Implement actual working BAV (spd) mechanism used in the original game.\
[X] Implement actual aggro mechanism used in the original game.\
[X] Implement 3rd skill (ult) that works & is executable\
[X] Make shader reflect the character's ult value.\
[] Shake, or animate the hp bar when affected\
[X] Add a condition for skill 2 (requires skillpoint for execution)\
[X] Make skill 1 give skillpoint\
[X] Adding audio\
[] Make enemies smarter (enemies can buff each other)\
[X] Be able to identify who will be affected by player's action (while awaiting for execution by player input) by looking at turn panels\
[] Create documentation (+ attributions, must credit mixamo)


### A** rubric (Highly doubt these are possible in 2 weeks.)
---
[?] There's no bug\
[X] Implement a priority queue for the current 'turn'.\
[] Add 'break effect / weakness' mechanism to the game\
[] Implement a 'wave' system : in a single battle, the next 'wave' of monsters join the battle only when the current wave of enemies are wiped\
[] Use deep learning to create a model that survives as long as possible.\
[] Make the game 'rogue-like'\
[] Add 'buff' system to the game.\
[] Implement actual dmg equation from the original game.
