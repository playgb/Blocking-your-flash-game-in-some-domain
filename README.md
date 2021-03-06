# Blocking your flash game in some domain
Action Script 3 code to block your flash game in some domain, with an external blacklist in .txt managed by you.

This action script 3 code will help you to block a domain from using your <a href="https://www.playgb.com" title="games">games</a>, there are many reasons for a game developer to do this, for example, the website may be using the game without your authorization and you want to run the game only in authorized websites.

If the website is not authorized to use your game, you can add it to your blacklist and the game will display something like this:

<img src="https://www.playgb.com/posts_images/blocking_flash_game.gif">

## Getting started

- Create a .txt file (example: domains.txt) and host in your server
- Write in this file, the domains that you want to block (comma separated)
- Update the line from the code below, with the address of your list
- Upload the <b>crossdomain.xml</b> file in your server
- Use the code in the file <b>block_domain_as3.fla</b> in the first frame of your game

You can use the same code to do a whitelist too, you will need to change just 1 line. So, if a website is in the .txt file, you run, if it's not there, you block the game.

Feel free to use it on your game, and contact <a href="https://www.playgb.com" title="Play GB">Play GB</a> if you have some question.
