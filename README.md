# GDIM 33 In-Class Activities
## W1
### Activity 1

[Moodboard](https://docs.google.com/drawings/d/1W5SQ_580zmz2nhwYdlPm40OwKk12HYX4abZ2ANsyjQI/edit?usp=sharing)

1. The gameplay mechanics from spacehulk deathwing creates slow, dark, shooting based gameplay along with the aesthetic of bloodborne amplifies this. 
I am specifically interested in having a beast style enemy reminiscent of bloodborne, bleach, and warhammer undead enemies. I wanted to focus on players moving through a 
maze like area, very slowly. The player will not be defenseless but I want to focus on the idea that the player doesn't need to be defenseless to get jumpscared

2. Lawrence is interested in a more aesthetic game using the ideas from the chinese drone light shows as enemies. A correlation between our game concepts is an appreciation
for allowing the player to move slowly yet where it differs is where his slowness comes from the ability for exploration 

3. They play fighting games and enjoy each persons skill expression. Appreciates the personal accountability that comes with a 1v1. Rythm games are a commonplace,
specifically mentioning beat saber which I have spent many hours in myself. 


### Activity 2

<img width="1560" height="1186" alt="33 4-1-26 breakdown 2" src="https://github.com/user-attachments/assets/fa85cb15-4bc0-420f-aa79-b4e222ebeb58" />



## W2

N/A

## W3

### Activity 1

<img width="1572" height="1184" alt="w3 new breakdown 33" src="https://github.com/user-attachments/assets/f9876997-2821-44de-bf5a-629fcac72627" />

### Activity 2

1. So that there is a reliable access to the correct event name whenever you want to trigger said event

2. The debug logs are helpful as you can ensure that the states are transitioning correctly and the states are actually changing

3. Set cursor lock state is relevant as my game is in first person and looking around is easier, more intuitive, and less tedious when the cursor is locked

4. I may not be using a high level game state tracker like the explore and dialogue ones used in this activity. However, I plan on using enemy states for wandering, chasing, and attacking.

## W4

### Activity 1

- The player can move around a space and click to show a weapon effect in order to kill enemies that run at you and attack you. You can kill the enemies but they cannot kill you.
The enemies also have animations.

Goals:
- Is the flamethrower style effect satisfying or enjoyable?
- Feedback on the monster behavior

Playtesting Team:
- Nolan Burns, Jayden Ishibashi

Feedback:
- good animations, good choice for monster model, if the enemy attacks the animation stops and the enemy moonwalks. Hard to tell how long the weapon effect is, cannot tell if hitting the enemy.
Put colliders on extra objects. Chase and hit distance is fine.

### Activity 2

1. A writer would easily be able to add more dialogue without code as the inputs for the line adn replies are already created and available in inspector. The writer would only need
to create new scriptable objects in the project window and fill in the line and replies in the inspector and connect them.

2. There is a limit of 4 buttons on the screen at once but there is theoretically no limit to the depth or layering of the choices.

3. The "Regenerate Nodes" button is used to create new nodes for use in visual scripting that are not normally in Unity's libraries. Such as methods or variables made in a C# script,
those will not show in the visual scripting graph as a node until they are regenerated and added to the list of nodes to use.

Bonus Point:

<img width="2540" height="1412" alt="w4 33 bonus point proof" src="https://github.com/user-attachments/assets/cefd3f0d-4b3e-491d-a483-6ea7ef371879" />

## W5

### Activity 1

Keyframe animations
1. Create empty timeline object
2. Create the timeline asset and remove the animator component
3. Keyframe camera pan to enemy
4. Keyframe attack animation
5. Pan out and turn on text and start button

Gameplay integration
1. Create separate scene to hold
2. Play on start
3. No looping
4. Script that hold scene manager to switch scenes where the player will be dropped

### Activity 2

I created a timeline in a new scene and was able to animate the camera to pan down towards an enemy, have the enemy play an attack animation, start the running animation, and 
turn on a button to move to the main scene. There is a script for moving to the main scene connected to the button. I created a skybox material that is dark and turned down
the default lighting to make the scene very dark.

## W6

### Activity 1

Since the last playtest I have added a flamethrower model and flame particle system, added the overheat mechanic to the flamethrower, added the ability to pick up medicine and use
it, fixed the enemy animations, added an intro scene and cutscene using timeline, and allowed the player to die if they take enough damage

[Itch Link](https://bjohnston07.itch.io/playtest-2)

Goals: Does the relationship between movement speed, taking and dealing damage, and healing feel right. Generally try and find bugs

Notes:
- Cutscene instantly transition to run 
- Camera Teleporting (might be mouse issue)
- Collider clipping issue
- Try and make flamethrower particle system bounce off colliders
- Look around and health goes to negative after dying
- Specific ranges where the animation doesn't continue
- Death animation doesn't interrupt 
- Hard to know when the enemies are being hit
- Animation event for player to take damage during attack animation

### Activity 2

1. The color becomes darker and less saturated as when multiplying decimals the product is lower thn the originals, making the RGB values decrease
2. Less for the same reason as before
3. The UV coordinates comes from the vertex data within the mesh
4. It's pretty interesting to me as I learned it in sophomore year of high school as well and made my AP comp sci principles project based around a user being able to create their
1. own color combinations overlayed onto an image

## Week 7

1. The data for the Vertex Color node comes from each vertex in the mesh
2. The interpolation between each vertex creates the blending effect
3. The quality of the texture when using vertex color relies on the sheer quantity of vertices. Vertex color can be used for puposely low poly aesthetics as well as ease of use
and ease of creation
4. There is an odd patch of lighter green on the backside of the shiba
5. You could also map UV data to a color to differentiate the pieces of the UV map
6. The surface normals were opposite directions causing the dot product to be reversed
7. The Blend mode being additive changes the result of the color multiplication onto the shader to be a gradual increase



