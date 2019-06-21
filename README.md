# FEND-arcadegam# Classic Arcade Game Clone Project

-   I enjoyed a lot while playing this game and I learned JavaScript object oriented concepts.
## Table of Contents

-   [Instructions](#instructions)
-   [Contributing](#contributing)

## Instructions

Use this [rubric](https://review.udacity.com/#!/rubrics/15/view) for self-checking your submission.

Make sure the functions you write are **object-oriented** - either class functions (like `Player` and `Enemy`) or class prototype functions such as `Enemy.prototype.checkCollisions`. Also make sure that the keyword `this` is used appropriately within your class and class prototype functions to refer to the object the function is called upon.

Your **README.md** file should be updated with instructions on both how to 1. Run and 2. Play your arcade game.

For detailed instructions on how to get started, check out this [guide](https://docs.google.com/document/d/1v01aScPjSWCCWQLIpFqvg3-vXLH2e8_SZQKC8jNO0Dc/pub?embedded=true).

## Contributing

This repository is the starter code for _all_ Udacity students. Therefore, we most likely will not accept pull requests.

# How to download project

-   To run this application, download the **Udacity** zip file or clone the repository.
-   Then unzip file which is given by Udacity .
-   I observed the following folders  in this project
    1.`css`
    2.`HTML`
    3.`js`
    4.`images`
-   At that point open a browser window and inside it open the index.html fine in the registry of your application.

## Code modification

-   I made the following changes in order to develop this game.
-   I opened the `index.html` file with atom software , after that I found that the page seems to be empty.
-   I came to know that few modifications should be done in the `app.js` file.
-   Initially i seen some errors in console by creating `allEnemies[]` and assigned positions for the enemy.
-   So I created a class with name `Player` by using `Object Oriented JavaScript`.
-   I assigned positions of the player by creating object `player` for the `Player` class.
-   After the changes `Player` is visible on the screen in play area.
-   Bugs speed randomly changes and each bug moves with different speed on canvas screen.
-   player had to reach the destination (water level at top of canvas) by escaping from enemy.
-   If player touches the enemy the position of player set to initial level.
-   Similarly every time player reaches the water player position can be set to initial level and with another sprite.

### How to play game

-   Utilize the bolt keys to move left, right, forward or  backward.
-   When you achieve the water, the game will begin once again with different player.
-   In the event that you keep running into another side of the path, When player touch the enemy and the player get backs to its position.
-   The enemy are running over the screen aimlessly areas and with irregular velocities.
e
