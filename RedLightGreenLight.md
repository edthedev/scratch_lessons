# Red Light! Green Light!

![red light welcome](redlightwelcome.png)

## Rules to Play

- Use the arrow keys to move left and right.
- Try to only move forward when the light is green. 
- If you accidentally walk when the light is red, take three big steps back.

If you make it to the other side, you win!

## Build the Game

### Teach the Cat to walk

Add the following code to the cat sprite, so that it will walk forward and backward when you press the left and right arrow keys.

![cat code](walkleftrightcatcode.png)

To find these command blocks, you will need to look in the *Events* and *Motion* script block sections.

![events](events.png)
![motion](motion.png)

The *when left arrow is pressed* command makes the command that follows it only happen when you press the left arrow key on the keyboard. Add this block twice. Select 'left arrow' for the first version, and select 'right arrow' for the second version.

![Move10](move10steps.png)

The *move 10* command tells the cat to move a bit in the direction it is facing. It is facing to the right, so it will move right. Add this block twice. 

For the *move 10* block below *when left arrow is pressed* put a minus sign in front of the 10. This tells the cat to take 10 steps back, instead of forward. This code lets you use the left arrow key to take three big steps back when you accidentally step forward on a red light.

### Make the Stop Light

![cat and ball sprite listed](catandballsprite.png)

Add a new ball sprite. It will become our stop light.

Add the following code to the ball sprite.

![Stop light code](redlightcode.png)

![wait 1 sec](wait1sec.png)

Without the *wait 1 secs* command, our light would change much to fast, making the game too hard. 

- ![set color red](setcolor180.png) ![Green ball](greenball.png)
- ![set color red](setcolor255.png) ![Red ball](redball.png)

These commands change the color of the ball. Different numbers select different colors. I figured out which colors were red and green by trying lots of different numbers. Number 180 makes the ball green. Number 255 makes the ball red.

## Play!

Press the *Green Flag* to play your new game!

![Green Flag](greenflag.png)

![red light welcome](redlightwelcome.png)

You can also [Play or Remix my version](https://scratch.mit.edu/projects/170705647/).
