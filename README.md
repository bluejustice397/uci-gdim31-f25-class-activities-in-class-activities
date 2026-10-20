# in-class-activities
## Devlogs
### W1
    
    When you separate the camera from the cat, it no longer follows the cat. This happens because the camera is fixed in one spot. When it is attached to the cat it moves with the cat.

    Game Link: https://bluemani56397.itch.io/kit-kat-game

### W2

1. The rgb variables are floats because rgb values can by any number from 0 to 255 including decimals. Int wouldn't work because ints are only whole numbers, string wouldn't work because, rgb values are numerical values not text, and bools wouldn't work because rgb values aren't true or false.


2. The _bounce variable is an int because you can only have a whole number of bounces. You can't have 0.1 of a bounce. Every bounce is one full bounce.


3. The error message told me that it couldn't convert a double to float value without a cast. That means that data types aren't naturally compatible with each other and have to be concatenated if you want to convert one type to another.

### W3
1. The input (Friendship Level) could be an int or a Float.
    The flag (knowsSecret) is a bool.
    Output is a string.


2. The input (Sanity) is a float because sanity can be represented by a decimal.
    The output is void because the method doesn't have an output.


3. The output is a (bool)
    The input is time which is a float

4. Components = Game chars
    Class = Spells
    Member Variables = Spell Stats
    Methods = Status Effects

5. I was not able to get to the step that makes the balls bounce and change color, but I would assume its because the balls change color in correlation to the speed of the ball. The faster the ball moves the faster the color changes, causing it to get super bright.


### W4
1. We figured out the Cat and the Ball need a rigidbody so physics can be applied to them and the goal needs Is Trigger on so it can detect whether or not something has passed through it.


2. In the beginning I had an issue where my cat would get stuck spinning infinitely. To fix this I had to freeze the cats rotation in the constraints section of the collider component. And when I wrote the method to track the time passed in between each goal. I had a bug where the time kept looping the same number, and after looking over my code I realized that I had assigned the variable that represents time passed to Time.deltaTime instead of adding Time.deltaTime. After I fixed that mistake the timeText updated correctly. 
 

## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 