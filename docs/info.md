<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

Runs a rock,papper, scissors game based on 2 2bit inputs. Input pins 1 and 2 are associated with player1 while input pins 3 and 4 are associated with player2. 
The cirucit is designed around the following logic abstraction:
"00" = No input/error
"01" = Rock
"10" = Paper
"11" = Scissors
If either player's input is an error, then the ouptut is undefined. Otherwise, the winning throw has a hi output while the losing throw will have a low output. 
In the case of a tie, both players will have a high output. Output pin 0 is associate with player1, output pin 1 is associated with player2, and output pin3 is the 
error pin. 

## How to test

The easiest and most basic way to use this project is to tie the inputs to a dip switch and the outputs to LEDs and watch the game work. 

## External hardware

No external hardware other than what is mentioned above will be needed.
