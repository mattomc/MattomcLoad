## Welcome to the Loading screen

Welcome to MattomcLoading screen, were here to help you create a new loading screen for your FiveM server.

if you need any support or just wanna have a chat join my Discord server:
https://discord.gg/WP4q95d

<a rel="license" href="http://creativecommons.org/licenses/by-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nd/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nd/4.0/">Creative Commons Attribution-NoDerivatives 4.0 International License</a>.

## EDITING THE LOADING SCREEN

The first thing you need to change is the Music and just have a path as in

    <audio  id="Loading"  autoplay  loop  >
    <source src="folderpath/musictest.mp3"  
    type="audio/mp3"></audio>
so change SRC value to the folder the music is in and the name of the song and the extension at the end (.wav || .mp3).

then you would change the images if you want just follow the last step and you should be gucci

## changing the server name
to change the server name all you need to do is find the value where it has `<p>Default name</p>` and change it to what your server is called

## changing Rules | Information module
to change the rules and Information module in the loading screen its as easy as the other steps. make sure to save the file when your done

to do this:
find the w3-panel where it says "This is the defualt Look of the screen"

to change the rules remove the parts that you dont want and add your own rules in by doign the following

    <ul><li>Number One Rule</li><li>Number Two Rule</li><li>Number three rule</li></ul>
and then save the file and open the index.html. it might show up distorted on a Chrome browser but in game it should look normal

## Troubleshooting
Q: the CSS isn't loading in game and I haven't touched anything
A: make sure you have the resource.lua in the right place and the w3.css is declared in the __resource file

Q: I have modifed the Loading screen but it doesnt load in game
A: Make sure you have started the resource by doing in the server.cfg

    start Mattomc_Load
Q: I have made a new CSS file and it doesnt want to work
A: Make sure you declare it in the `<head>` and have declared it in the __resource.lua

Q: How are you so Awesome?
A: Well Join my Discord server and I will tell you :wink: https://discord.gg/[WP4q95d](https://discord.gg/WP4q95d)

 
## IMAGES
![Load One](https://cdn.discordapp.com/attachments/527811385141362688/556401158063652866/unknown.png)
![Load two](https://cdn.discordapp.com/attachments/527811385141362688/556401225042755604/unknown.png)

