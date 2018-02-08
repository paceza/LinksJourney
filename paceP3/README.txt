Project 3


Title: Link's Journey


Author:
 Zack Pace

Lab Section:

 Morning Tues. 9am

What works:

 My board initializes when you start the program. Link can
move around the grid by user input and stops being able to chop trees
once he's chopped 10. Every 5 moves, the grid evaluates the existing 
trees to add and delete trees according to evauate. If a tree lands on
on Link during adding, the game ends and you can restart. Stepping on 
the Rupee ends the game and congrats you. Also you can't go off the 
boarder.

What doesn't work: My Rupee counter is unable to keep track of 
the number of times you reach the end. I'm guessing that I'm not passing
my stored 'Score' correctly when I call init & initRandom after reaching
the finish. I added 'prevScore' as a parameter in my int function;however,
it won't display an updated score on the screen.
Another aspect that doesn't work in my game is the fact that my initRand
function doesn't add trees along the outside of the grid allowing the 
player to walk along the edges where no trees spawn and reach the end
with ease.
Another aspect the doesn't work is a running count of moves and trees 
chopped down. It evaluates the trees and adds them accordingly every
5 moves, that's when it also updates the moves and trees chopped down.
But I would like to get it to where it's updating every single move.



What I have done for extra credit:





N/a