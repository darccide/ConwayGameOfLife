# Steven Thomson's Coding Interview Challenge

## About
This is a simple version of [Conway's Game of Life](https://en.wikipedia.org/wiki/Conway's_Game_of_Life). It is a [zero-player game](https://en.wikipedia.org/wiki/Zero-player_game) consists of a grid of cells, each of which can be alive or dead. For every cycle of the game, the cells can be turned on or off based on the following rules:


  * If a dead cell has exactly three live neighbors, it comes to life.
  * If a live cell has less than two live neighbors, it dies.
  * If a live cell has more than three live neighbors, it dies.
  * If a live cell has two or three live neighbors, it continues living.

By repeating the cycle of these rules over and over, many interesting patterns can be [created](https://www.youtube.com/watch?v=C2vgICfQawE&t=194s)
## Build Process
This was built first by using npm. 
  1. My first step was to create a random two-dimensional grid. 
  2. I wrote a function to enact the rules of the game in order to get the next generation of the game. 
  3. In order to do that correctly I needed to create a function that would count the neighbors of each cell.
  4. I created parameters for the coloring of a cell and a single cell's size.
  5. Now, I was able to write a function to draw the grid for the game.
  6. I then created a function which would make a generation using the functions made for a next generation and to draw the game grid.
  7. I then used window.onload and set the parameters necessary to display the game.
  8. I then created the html styling necessary in the index.html file.
## Tech
 * npm
 * react.js 
 * babel-cli 
 * babel-preset-env

## Improvements
Obviously there are lots of things that could be added, such as allowing the user to pause the game, reset the grid, draw their own patterns on the grid, and testing to name a few. However, all I really wanted to do is get a working version of Life up and running with the time constraints since I needed to figure out many of the mechanics of the game as well as drawing the grid within the 1.5 hour time limit. 

## Install
```
git clone git@github.com:darccide/ConwayGameOfLife `# or clone your own fork`
cd ConwayGameOfLife
npm install
npm start
```
## Author
Steven Thomson is a Fullstack Developer who currently resides in South Korea, but is transistioning back to the U.S. If you would like to contact him:

 * steven.thomson88@gmail.com
 * [Steven Thomson's LinkedIn](https://www.linkedin.com/in/steventhomson1988/)

