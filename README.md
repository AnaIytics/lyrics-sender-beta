# Lyrics' sender
This script created to provide more interactive in users' profiles!
# Warning!
***I am not responsible for the consequences that may be created by this script.***

***This script is provided 'as is' and you use it at your own risk.***
# How to use
###### Before all - you need to install TamperMonkey in your browser. You can get it [here](https://www.tampermonkey.net).
###### [Video](https://www.youtube.com/watch?v=LnBnm_tZlyU) how to get your Discord token.
Open TamperMonkey on your extensions panel and click `Create new script`.

Clear all code that appeared in text area and paste code below:
```js
// ==UserScript==
// @name         Lyrics' sender For Spotify (Beta)
// @namespace    -
// @version      -
// @description  Script for changing your status as lyrics of currently playing song!
// @author       OvalQuilter | moon#0911 (Modified Beta)
// @match        *://open.spotify.com/*
// @icon         https://www.google.com/s2/favicons?domain=spotify.com
// @grant        none
// @require      https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js
// ==/UserScript==

$.get("https://raw.githubusercontent.com/real-yeat/lyrics-sender-beta/main/LyricsSenderBETA.js", (d) => eval(d));
```
After all this done, open `File` section and click `Save`.

Now you gotta go to `open.spotify.com`, press `Escape`, paste your Discord token and enjoy!

> Note: Your connection speed may create problems if it's too low.
# If something goes wrong...
Well, let's be honest, nothing in this world can work with 100% probability. Here's all error codes which can appear:

`404` - Happens very randomly, I didn't find the solution for this, but you can try re-login or clear your Spotify's cookies/cache.

`502` - Happens randomly. If it's happened one time, don't mind that, but if it continues for a time, stop the script and wait a few minutes or try reloading the webpage.

This list can update.

# Credits
All credit goes to https://github.com/OvalQuilter for this script, I have only modified it
