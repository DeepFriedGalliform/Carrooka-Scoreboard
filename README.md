# carooka-score
Mobile-friendly Carooka score tracker app for two players with foul selection and local storage.

## Using it
1. Tap a player's panel to put them at the table.
2. Tap a ball each time one is potted (red 1, yellow 2, green 3, brown 4, blue 5, pink 6, black 7,
   white for the cue ball). The panel shows the running break, the total score and the pot history.
3. When the break ends, tap the other player's panel. The break is saved to the history.

The game starts with 15 reds and follows snooker order: red, colour, red, colour… then, once the reds
are gone, yellow → green → brown → blue → pink → black. The line above the balls shows the ball on and
the reds left.

Fouls are detected automatically: potting the white, two reds in a row, a colour when a red is on, or
the wrong colour once the reds are gone. A message shows the foul and the points, which go to the
opponent (the highest of 4, the ball on and the ball potted). The break ends and the opponent comes
to the table.

**Undo** reverses the last action. **New game** resets the scores but keeps the names (tap ✎ to rename).
The game is saved on the phone, so closing the browser doesn't lose it.

## Putting it on your phone
Host the folder with GitHub Pages (repo **Settings → Pages → Deploy from a branch → `main` / root**),
open the page on your phone, then use **Add to Home Screen** (Safari share menu, or Chrome's ⋮ menu).
It then opens full screen like an app and works offline.
