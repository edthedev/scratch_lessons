# Lesson 2: Red Light! Green Light!

![red light welcome](img/redlightwelcome.png)

## Rules to Play

- Use the arrow keys to move left and right.
- Try to only move forward when the light is green. 
- If you accidentally walk when the light is red, take three big steps back.

If you make it to the other side, you win!

## Build the Game

### Lesson 2 Step 1: Start a new Project

Find the *New* option in the *File* menu at the top left.

![NewProject](img/fileNew.png)

### Lesson 2 Step 2: Teach the Cat to walk

Add the following code to the cat sprite, so that it will walk forward and backward when you press the left and right arrow keys.

![cat code](img/walkleftrightcatcode.png)

To find these command blocks, you will need to look in the *Motion* and *Events* script block sections.

- ![motion](img/ScriptsMotion.png)

- ![events](img/ScriptsEvents.PNG)

The *when left arrow is pressed* command makes the command that follows it only happen when you press the left arrow key on the keyboard. Add this block twice. Select 'left arrow' for the first version, and select 'right arrow' for the second version.

![Move10](img/move10steps.png)

The *move 10* command tells the cat to move a bit in the direction it is facing. It is facing to the right, so it will move right. Add this block twice. 

For the *move 10* block below *when left arrow is pressed* put a minus sign (-) in front of the 10. This tells the cat to take 10 steps back, instead of forward. This code lets you use the left arrow key to take three big steps back when you accidentally step forward on a red light.

### Lesson 2 Step 3: Make the Stop Light

![cat and ball sprite listed](img/catandballsprite.png)

Add a new ball sprite. It will become our stop light.

Add the following code to the ball sprite.

![Stop light code](img/redlightcode.png)

![wait 1 sec](img/wait1sec.png)

Without the *wait 1 secs* command, our light would change much to fast, making the game too hard. 

- ![set color red](img/setcolor180.png) ![Green ball](img/greenball.png)
- ![set color red](img/setcolor255.png) ![Red ball](img/redball.png)

These commands change the color of the ball. Different numbers select different colors. I figured out which colors were red and green by trying lots of different numbers. Number 180 makes the ball green. Number 255 makes the ball red.

![control scripts](img/ScriptsControl.png)

From the *Control* scripts, we will need another *forever* and an *if then else*.

- ![forever](img/forever.png)
- ![if...then](img/ifthenelse.png)

![operators scripts](img/ScriptsOperators.PNG)

From the *Operators* scripts, we will need *pick a random number from 1 to 10* and *less than (<)*

- ![pick a random number 1 to 10](img/pickrandom1to10.png)
- ![less than](img/lessthan.png)

To insert the green 'pick random 1 to 10' block into the '< 5' block it use the mouse to grab the far left end of the 'pick random 1 to 10' block, then drag it into the left bubble of the '< 5' block.

- ![connecting blocks](img/connectlogic.png)

Put it together inside the *Ball* sprite, and we have a stop light that randomly changes between red and green every second or so.

![Stop light code](img/redlightcode.png)

## Lesson 2 Step 4: Play!

Press the *Green Flag* to play your new game!

![red light welcome](img/redlightwelcome.png)

You can also [Play or Remix my version](https://scratch.mit.edu/projects/170705647/).
