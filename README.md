> How to install a bookmarklet?

1. Create a bookmark (the star on the right side of the url bar if you are using chrome)
2. Click on more at the bottom left corner
3. Delete everything in the url box
4. Paste in the code.

# 1-Click bookmarks:

- ## 3D Page - Everything will be 3D! (Works on some website)
```javascript
javascript:(function(){var js=document.body.appendChild(document.createElement("script"));js.onerror=function(){alert("Sorry, the script could not be loaded.")};js.src="https://rawgit.com/Krazete/bookmarklets/master/tri.js"})();
```

- ## AutoClicker - Click where you want, and it will click automaticly. it clicks 100 times every second (100cps). (Works on some website)
```javascript
javascript:(function() { var clickerIsMouseDown = false; var clickerCurrentMouseTarget = document.body; document.body.addEventListener('mouseup', () => { clickerIsMouseDown = false; }); document.body.addEventListener('mousedown', () => { clickerIsMouseDown = true; }); document.body.addEventListener('mousemove', (e) => { clickerCurrentMouseTarget = e.target }); setInterval(() => { if (clickerIsMouseDown) clickerCurrentMouseTarget.click(); }, 0); })();
```

- ## Blocked GoGuardan Tab Close - This will make someone who is controlling your computer being unable to close it.
```javascript
javascript:(function () {window.onbeforeunload = function() { return 1; };})()
```

# What do they do?

ComicSansify.js: Change the font to Comic Sans

MinceraftEverywhere.js: Minceraft Everywhere

CursorCoord.js: Show the coordinate of the cursor on the search bar

Spinning.js: Make the webpage spin (Works on most site)

FindInArchive.org.js: Search for the website you're on on Web Archive (Wayback Machine)

FontBomb.js: Create a nuke on screen when you clicked the page and will blow up the page to a mess

EasyInspectElements.js: Basiclly inspect elements but you can edit the page by clicking the text you wanted to edit. Click the bookmark again to turn it off.

TabClock.ks: Change the tab name and icon to disquise as other website.

BlockedGoGuardanTabClose.js: This will make someone who is controlling your computer being unable to close it.

AutoClicker.js: Click where you want, and it will click automaticly. it clicks 100 times every second (100cps).

InspectElement.js: Inspect unblocked. YOu'll find a gear icon on the bottom left of the screen. (Works on some website)

piano.js: A piano controlled by your keyboard

QuizletMatch0.6sec.js: Get a score of 0.6 seconds every time in Quizlet match!

3dPage.js: Everything will be 3D!

HTMLgoggles.js: This lets you edit the raw HTML. It's very advanced editing.

TypingTroll.js: Change any thing you're typing to "Change this text!" [Github/ShadowbreakerGD](https://github.com/ShadowbreakerGD/Bookmarklet-For-Trolling)

TomatoSmash.js: Throw tomatoes at websites, click the tomatos to smash it! [Github/Quinten](https://github.com/Quinten/tomato-smash)



----

BackgroundColour.js: Replace the background colour (Work on most website)

-Customizable by replacing "black" with a colour listed on this website https://www.w3.org/wiki/CSS/Properties/color/keywords
       
From this `javascript:(function(){document.body.style.background = 'black';})();`
       
To this `javascript:(function(){document.body.style.background = 'cyan';})();`

----

Other cool collection of bookmarklets:

[Github/hariprasd/cool-bookmarklets](https://github.com/hariprasd/cool-bookmarklets)

[Github/Priyank-Vaghela/Awesome-Bookmarklets](https://github.com/Priyank-Vaghela/Awesome-Bookmarklets)

place holded

----
Support me by subscribing to https://youtube.com/@radioactive.potato and also check out my twitter https://twitter.com/RadioactiveP724
