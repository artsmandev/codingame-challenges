__The Goal__\
Destroy the mountains before your starship collides with one of them. For that, shoot the highest mountain on your path.

__Rules__\
At the start of each game turn, you are given the height of the 8 mountains from left to right.
By the end of the game turn, you must fire on the highest mountain by outputting its index (from 0 to 7).

_Firing on a mountain will only destroy part of it, reducing its height. Your ship descends after each pass._

__Victory Conditions__\
You win if you destroy every mountain

__Lose Conditions__
* Your ship crashes into a mountain
* You provide incorrect output or your program times out

__Note__\
_Don’t forget to run the tests by launching them from the “Test cases” window. The tests provided and the validators used to calculate your score are slightly different to avoid hard-coded solutions._

__Game Input__\
Within an infinite loop, read the heights of the mountains from the standard input and print to the standard output the index of the mountain to shoot.

__Input for one game turn__\
__8 lines:__ one integer `mountainH` per line. Each represents the height of one mountain given in the order of their index (from 0 to 7).

__Output for one game turn__\
A __single line__ with one integer for the index of which mountain to shoot.

__Constraints__
0 ≤ `mountainH` ≤ 9
Response time per turn ≤ 100ms
