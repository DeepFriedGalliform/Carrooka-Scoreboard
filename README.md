# carooka-score
Mobile-friendly Carooka score tracker app for two players with foul selection and local storage.

## Using it
1. Tap a player's panel to put them at the table.
2. Tap a coloured ball each time one is potted (red 1, yellow 2, green 3, brown 4, blue 5, pink 6, black 7).
   The panel shows the running break, the total score and the pot history.
3. When the break ends, tap the other player's panel. The break is saved to the history.
4. For a foul, tap the white ball with the red cross and choose the ball involved. The points
   (ball value, minimum 4; white = 4) go to the opponent, and the opponent comes to the table.

**Undo** reverses the last action. **New game** resets the scores but keeps the names (tap ✎ to rename).
The game is saved on the phone, so closing the browser doesn't lose it.

## Putting it on your phone
Host the folder with GitHub Pages (repo **Settings → Pages → Deploy from a branch → `main` / root**),
open the page on your phone, then use **Add to Home Screen** (Safari share menu, or Chrome's ⋮ menu).
It then opens full screen like an app and works offline.
