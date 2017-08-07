# Red Light! Green Light!

## Rules to Play

Use the arrow keys to move left and right.
Try to only move forward when the light is green. 
If you accidentally walk when the light is red, take three big steps back.

If you make it to the other side, you win!

## Build the Game

### Teach the Cat to walk

Add the following code to the cat sprite, so that it will walk forward and backward when you press the left and right arrow keys.

![cat code](walkleftrightcatcode.png)

![Move10](move10.png)

The *move 10* command tells the cat to move a bit in the direction it is facing. It is facing to the right, so it will move right.

Notice the minus sign in front of the 10 under the left arrow key code. This tells the cat to take 10 steps back.

### Make the Stop Light

![cat and ball sprite listed](/Downloads/catandballsprites.png)

Add a new ball sprite. It will become our stop light.

Add the following code to the ball sprite.

![Stop light code](/Downloads/redlightcode.png)

These commands change the color of the ball. Different numbers select different colors. I figured out which colors were red and green by trying lots of different numbers.

![set color red](setcolorto180.png) ![Green ball](greenball.png)

![set color red](setcolorto255.png) ![Red ball](redball.png)


![Red Ball](redball.png)

[Play or Remix my version](https://scratch.mit.edu/projects/170705647/)
