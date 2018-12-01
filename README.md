# Steven Thomson's Coding interview Challenge

### About
***
This is a simple version of [Conway's Game of Life](https://en.wikipedia.org/wiki/Conway's_Game_of_Life). It is a [zero-player game](https://en.wikipedia.org/wiki/Zero-player_game) consists of a grid of cells, each of which can be alive or dead. For every cycle of the game, the cells can be turned on or off based on the following rules:


  * If a dead cell has exactly three live neighbors, it comes to life.
  * If a live cell has less than two live neighbours, it dies.
  * If a live cell has more than three live neighbours, it dies.
  * If a live cell has two or three live neighbours, it continues living.

By repeating the cycle of these rules over and over, many interesting patterns can be [created](https://www.youtube.com/watch?v=C2vgICfQawE&t=194s)
### Build Process
This was built first by using Create React App as the boilerplate since I knew that under the time constraints I needed to be up and running quickly. It only has two routes that are built out with React Router. It has a super simple Home page and the message board page.

Login is handled by Google Firebase and you can login with your Google credentials as I did not have time to build out a back-end user database. Messaging updates instantly on the React front-end. Messages are also hosted in Google Firebase both for speed and to facilitate the quick build time. (Though I do have experience building a full back-end that can be seen here)

In this project, basic styling was done with Bootstrap as I did not have time to fit completely build out the CSS from scratch. This app is not up to my usual detailed styling standards, as you can see in my other projects. To see more of my normal styling please see my Wiki-What and Jams projects.

Finally all tests are built using the React Testing Library and check for renders of the components

### Tech

### Improvements

### Install

### Author

