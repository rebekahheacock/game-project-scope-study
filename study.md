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

| User |
| --- |
| id | 
| email | 
| password | 
| token (? set on login) | 
| games | 

| Game |
| --- |
| id | 
| cells |
| over |
| player_x |
| player_o |  

| Chat (tbd) |
| --- |
| id |
| player_x |
| player_o |

| Message (tbd) |
| --- |
| id |
| chat_id |
| author |
| content |


### How you will take the markup of the game board and represent it in JS

The game board will be a grid of divs (or possibly spans?). Each one will have an id that corresponds to its position in the game's `cells` array.

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
Following the examples in class so far, I plan to separate my JS functionality into index, events, api, and ui files. We haven't yet talked about how to handle different views in a single-page app, but that's one method of separating the display code into discrete chunks. 

### What creative spin will you add to your project.
I've been looking at mobile game apps for design inspiration (particularly those designed by [Dots.co](https://www.dots.co/). Tic-Tac-Toe is a pretty simple game at its core, and I'd like to keep the design fairly streamlined/minimalist to match. 

I plan to design from a mobile-first perspective (which should be fairly easy, since we're using Bootstrap). I made the mobile wireframes first, and then built the larger screen wireframes based on those.

In terms of functionality, I'm considering offering two or three color scheme options and letting players choose one (and maybe storing this in their localStorage so it persists across sessions).

Super cool would be to implement [this version](http://tabtimes.com/how-two-developers-turned-age-old-game-something-much-more-12963/) of the game, which uses nine game boards (one board in what is normally an empty square in a basic tic-tac-toe game) and has a [more complex set of rules](https://mathwithbaddrawings.com/2013/06/16/ultimate-tic-tac-toe/). The provided API isn't really set up for this, but I might be able to figure out a way to sort of hack this together using localStorage. This is currently set to "iff I somehow figure out how to do everything else on the bonus list before my time is up" goal status.

### How you will use version control to backup / track your project.
I plan to use git to track, with branches for different features (auth, game play, design, potential chat, etc.).

### Do you plan to attempt any of the bonuses.
I'd like to include a win counter, the option to play against someone who's using a different device, and the "Waiting..." message while players are being matched. If that all goes well, I might tackle chat.
