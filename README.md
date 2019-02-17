## How to run GameCentre:

* Clone the repository
* Create a new AndroidStudio Project
* Use src as the source files for the project
* Make sure you have Android SDK 27 device run the app
* Run app

## Description:

This is a Android Game Centre app that I created with 4 others as part of a CS course.  It can play three games: Sliding Tiles, Memory Puzzle, and Minesweeper, and it has a User system and a Scoreboard system.  The User system does not make use of a database, so it only saves per launch.  All games have an autosave function, although used together with Memory Puzzle it has a few bugs.  Memory Puzzle's undo last move function is also unstable and shouldn't be used for consecutive undoes.

Upon clicking on the games, you will be transferred to the game starting activity where you can select different options to aid your game experience. 

After winning or losing the game you will be transported back to the starting activity where you can view your score if you won. 