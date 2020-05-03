# unity-assignment1
https://victor-avelar.github.io/unity-assignment1/

Approach
Please refer to my attempt at the solution, click on this link to run in your browser. Take note that these two are "built" version of the games, and, it can take significant time to build your game from the Unity editor. E.g., I think it took somewhere between 5 to 10 minutes to build the browser version of the game. Remember to always reserve time for building your games for submission. 

With the world width of 50-unit, here are the functionality you must support on the green arrow hero object,

Hero Motion
Hero travels at a constant speed (without the need to press any keys). 

Initial speed speed of 20-unit/sec
Up/Down arrow to increase or decrease the speed
P key to set the speed to zero [not supported in my solution]
Direction control with A and D keys
Hero Interaction with the World Bounds
Hero should reflect when its bounds touches the world bounds:

If collide with the side walls, flip the x-component of transform.up
If collide with the top/bottom walls, flip the y-component of transform.up
Hero Egg Spawning Behavior
"Space" bar to spawn an egg
There is a cool-down period in between egg spawning 
The cool-down period is under user control via a scroll bar, the range is between 0 to 1 second
The cool-down bar
A cool-down bar must be drawn reflecting the amount of time left in the cool-down
The cool-down bar size is always 200-pixel and (not 100-pixel) wide initially and decrease gradually to 0 pixels when egg spawning is allowed
Hint: I use a UI-Image, and control the RectTransform.sizeDelta [the Width/Height fields shown in the editor GUI]
Spawned egg behavior
Spawned eggs are aligned with the up-direction of the hero when first spawned (the tip is aligned with the tip of the green arrow).
Spawned eggs travel in its tip direction at a speed of 40-unit per second
Spawned eggs expires when either of the following conditions are true
It reaches the world bound
It has been spawned for more than 1 second
Quit Application
Quit the application with the "q" key [not supported in my solution]

Credit Distribution
(25%) Hero Motion
(10%) Initial speed speed of 20-unit/sec
(10%) Up/Down arrow to increase or decrease the speed
(3%) P key to set the speed to zero [not supported in my solution]
(2%) Direction control with A and D keys
(10%) Hero reflect off world bounds
(5%) Touching the horizontal walls
(5%) Touching the vertical walls
(35%) Hero Egg Spawning Behavior
(5%) "Space" bar to spawn an egg
(10%) Correct cool down period behavior
(10%) Cool down bar UI
Initial size of 200-pixel (and not 100 pixels) [for any cool down period]
Size reduces to zero during the cool-down
(10%) Cool down scroll bar support
Cool down range between 0 to 1 second
(15%) Spawned egg behavior
(5%) Aligned with hero when spawned
(3%) Travel at a speed of 40-unit per second
(2%) Expires when touches world bounds
(5%) Expires after 1 second
(5%) Q-key to quit application
(10%) Proper submission
(10%) Submission to Canvas with a zip
Unzip and run in the editor properly
(10%) Submission include a URL
Click to run the game
