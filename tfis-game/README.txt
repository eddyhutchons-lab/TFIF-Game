TFIS Game: home-screen version (build 0.6)

This folder is the whole game as an installable web app. It needs to be on a
website (https) before a phone can install it.

1. Put this folder online with any static web host, for example by dragging
   the folder onto Netlify Drop or uploading it to GitHub Pages.
2. Open the address you get on your phone.
   iPhone (Safari): Share, then Add to Home Screen.
   Android (Chrome): the menu, then Install app or Add to Home screen.
3. Open it from the home screen. It runs full screen, sideways, with no
   browser bars, and keeps working without a connection.

When you upload a new build, change VERSION at the top of sw.js so phones
fetch the update.

Files
  index.html            the game
  manifest.webmanifest  name, icon, full screen, landscape
  sw.js                 offline copy
  icon-*.png, apple-touch-icon.png, favicon.png   app icons
