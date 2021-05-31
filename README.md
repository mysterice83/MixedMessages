# MixedMessages
## GERE Week 6 Group Project 
#
__Specify:____
  * MixedMessages() takes no arguments.
  * MixedMessages stores at least three groups of 'things' in the corresponding number of arrays.
  * The 'things' comprise persons, places, and objects (in that order), corresponding to the 'things' of interest in the board game 'Clue'.
  * MixedMessages() uses a random number generator to select one 'thing' from each array.
  * MixedMessages() combines those three randomly selected things into a phrase that prints to the console.
#
__Ideate:__
  *  Create an object containing three arrays comprising (1) the six people, (2) the nine rooms, and (3) the six weapons in the traditional version of the 'Clue' board game.
  * Create a random number generator using Math.floor() and Math.random(), which uses the length of the three arrays of 'things'.
  * Use a for...in loop to move through the three arrays in the object, selecting a random 'thing' in each array.
  * Use a switch that--depending on the array--pushes an appropriate phrase into a (initially empty) 'accusation' (container) array for storage.
  * Print the complete 'accusation' to the console using the .join array method to connect the individual container array element phrases into one.
  * Adjusted the Clue game to reflect Scooby Doo cartoon mentions
