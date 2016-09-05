# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](http://searchsoftwarequality.techtarget.com/definition/user-story)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss during our next
class.

Submit detailed answers to these in this file via a pull request.

### A wireframe of what your game project will look like.

### The data structure you plan to use.

### How you will take the markup of the game board and represent it in JS

### How you plan to approach this project.
I'd like to put together a very simple page that contains all of the necessary components (sign up/log in forms, log out button, game board, reset/new game button, place to display wins/losses). From there, I can implement the basic authentication/game play functionality, then go back in and start refining the aesthetic and working on extra features.

### 4-8 user stories for your game project.
- As a site visitor, I want to sign up so I can play.
- As a returning user, I want to log in so I can play.
- As a player, I want to start a game so I can play.
- As a player, I want to reset a finished game so I can play again.
- As a player, I want to know whose turn it is so I know when to play.
- As a player, I want to know who won (or whether it's a tie) so I know if *I* won.
- As a player, I want to track how many games I've won so I know how well I've played over time.
- As a player, I want to be matched with an opponent so I can play against someone using a different device.

### How you plan to keep your code modular.
Following the examples in class so far, I plan to separate my JS functionality into index, events, api, and ui files. We haven't yet talked about how to handle different views, but that's one method of separating the display code into discrete chunks. 

### What creative spin will you add to your project.

### How you will use version control to backup / track your project.
I plan to use git to track, with branches for different features (auth, game play, design, potential chat, etc.).

### Do you plan to attempt any of the bonuses.
I'd like to include a win counter, the option to play against someone who's using a different device, and the "Waiting..." message while players are being matched. If that all goes well, I might tackle chat.
