# DP
## Repository for Master Thesis and Thematic Project
This repository contains a WordPress plugin for video playback and management. Current testing enviroment for developement is located on test ```http://testcatv.ga/```. 
### Instalation
This project uses Plyr and Bootstrap. For instalation process you can just use 
```git clone https://github.com/LaserPork/wplyr-better-video```
To install all dependecies required for the building process you can use npm.
```npm install```
After you downloaded all dependecies into node_modules, you can build the projects sass and javascript files by using gulp build file
```gulp build```
All built files are placed in ``./dist`` folder

### Structure
Player implementation is located in a file ``./player/src/js/player.js`` and sass modifications in ``./player/src/sass/custom.scss``

You can check out the demo of the player on [GitHub Pages](https://laserpork.github.io/DP/) or on my [School Homepage](http://home.zcu.cz/~vaverkaj/DP/).