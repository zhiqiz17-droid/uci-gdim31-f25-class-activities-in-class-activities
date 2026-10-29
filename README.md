# in-class-activities
## Devlogs
### W1
## Activity 1
## In class activity
After I moved the Camera out from under the Cat， the Camera no longer moves along with the Cat. This is because the Camera is no longer a child object of the Cat， so it does not move with it.

## Open-Source Assets
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153

### W2
Create future Devlog sub-headers with the three # symbols， then write your Devlogs below them.
### In class activities
### 1
Because r，g，and b represent color values， which can have decimal values. A float allows values like 0.5， while an int would only allow whole numbers. They aren't bools because they're not simply true/false， and they aren't strings because they're numerical values used for calculations.
### 2
The _bounces variable is an int because the number of times the ball bounces is a whole number. We would not normally have 2.5 bounces. An int also lets us easily increase the number by 1.
### 3
The error after Step 4 showed that the line was missing a semicolon at the end. In C#， the line needs to end with a semicolon， so g -= 0.1f；is the correct version.

### W3
### In class activities
### Devlog question
### Activity 1: methods discussion
For the visual novel, “GetResponse” takes friendship level and whether the player knows the secret as inputs and returns a string. For the horror game, “SetLightDimness” takes sanity level as input and returns void. For the rhythm game, “DidPlayerHitBeat” takes the key press time and beat time as inputs and returns a boolean.

### Activity 2: Components & classes metaphor
A class acts like a blueprint for a game character. Member variables describe the character's attributes—such as health, speed, and color—while methods define its capabilities, such as jumping, moving, and taking damage. A component is an instance of a class that can be attached to a GameObject in Unity, thereby endowing that object with specific properties or behaviors.

### Activity Part 3: Devlog question
The balls become extremely bright because their color is multiplied by 1.5 each time they bounce fast enough. Repeated multiplication makes the color values increase quickly, so after many bounces, the balls can become extremely bright, especially in the Scene view.

### W4
### In class activities
### Devlog question
### Table 13
### 1
We added a Rigidbody to the Cat and the SoccerBall so they could move and interact with other objects using physics. We used colliders to detect collisions. We checked Is Trigger on the Goal's collider so the ball could enter the goal area and trigger the goal event without being blocked by the goal.
### 2
We checked the collider settings, Rigidbody settings, and missing component references in the Inspector. We also tested the game to make sure the cat could kick the ball, the ball could bounce off the wall, and the goal event worked correctly.
