# Desktop-Friend
Tiny desktop Friend that you can pet. 

[How it looks.](https://i.imgur.com/I0VPIBL.gifv)

## Info
To change the default and rest gifs, go to `src/img/character/` and then change out the `default.gif` and `rest.gif`. If making your own art, it's probably best to stick to the same dimensions unless you want to alter the `style.css` as well. 

## Building
1. Clone repository, move folder to desktop
2. `cd` into the folder 
3. Type `npm install` 
4. Type `npm start` to start app after initial installation 

## Bugs
* App only drags if you click on the right side of the image.
* Sometimes `ctrl+c` won't quit app from terminal, just use activity monitor in such cases and look up electron. 

**Note:** Only tested on a Mac, no idea how it would look on Windows. 
