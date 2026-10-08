# Diagonaut

**Play it at [diagonaut.com](https://diagonaut.com)**

Diagonaut is a chess-themed endless runner for the browser. You are a single white pawn racing up a five-lane board. Black pieces come at you, and you capture them the way a pawn does: diagonally. Touch one head-on and the run is over.

The game is built mobile-first and runs in any modern browser, on phones and desktops alike.

## Game modes

- **Classic**: an endless run. Survive long enough and the Black Queen and Black King show up as bosses.
- **Time Attack**: 60 seconds to score as much as you can. No bosses.
- **Dodge Only**: you can't capture anything. Every piece you slip past is worth points.
- **Puzzle**: 12 hand-made levels with up to three stars each.

Every mode except Puzzle comes in four difficulties: Easy, Medium, Hard and Very Hard.

Signed-in players can also play **online duels** against each other (see below).

## Features

- Power-up bubbles: shield, multiplier, slow-motion, bomb, extra life and tokens
- A token economy with permanent upgrades
- A market full of cosmetics: piece colors, hats, glasses, companions, trails, auras, capture and defeat effects, enemy piece sets, board themes, promotion to other pieces and profile cards
- Bronze, silver and gold chests
- Levels and XP, achievements, statistics and a tutorial (in **Settings**)
- 16 languages, including right-to-left Arabic and Moroccan Darija
- Every menu fits on one phone screen; long lists are split into pages you can swipe through
- On desktop: arrow keys or WASD to move, **Space** on the main menu to start a match, **Esc** to pause

## Accounts

Playing doesn't require an account. You can start as a guest right away, and your progress is kept on your device.

If you sign in, your progress follows you to every device. You can sign in with:

- **Google**
- **Email and password**, with email verification and password reset

On first sign-in you pick a username: 3 to 16 characters, letters, numbers and underscores only. Usernames are unique. New accounts receive a one-time welcome gift of 1,000 tokens.

Your profile card, duel record and friends are in the **Account** window. You can sign out (with a confirmation) or permanently delete your account at any time from **Settings → Account**. Deleting an account asks you to confirm your identity first and removes your cloud save, profile, friend list and leaderboard entries, including duels.

## Cloud save

When you are signed in, your progress is saved to the cloud automatically.

- Saves are sent at most once every 15 seconds, and never during a match, so they never get in the way of play.
- On the same account, the most recent save wins.
- If you played as a guest before signing in, the save with more progress is kept, so nothing you earned is lost.
- Your settings (language, sound and so on) stay on each device and aren't synced.

## Leaderboard

Signed-in players appear on a global leaderboard for **Classic**, **Time Attack** and **Dodge Only**. Puzzle mode has no leaderboard.

- The top 50 players are shown, along with your own rank.
- Each account has one entry per mode, holding its best score. A score can only go up.
- Rows show each player's avatar and, for Classic, how many bosses (♛ / ♚) they beat in their record run.
- Tap a row to open that player's card: their card design, rank, score, achievement progress and number of matches played.

## Friends

Signed-in players can add each other as friends.

- Open **Friends** on the main menu (or the **Friends** tab of the Account window) and add someone by username. They get a friend request and become your friend once they accept. A badge shows how many requests are waiting for you.
- Your friend list shows who is online, in a match or in a duel, and lets you challenge online friends to a duel.

## Online duels

Tap **Online** on the main menu to open the online modes:

- **Duel**: 3 lives each.
- **Long Duel**: 5 lives each.

Pick a mode, then **Find opponent** for a random match, or invite a friend from your friend list.

Duel rules:

- Classic rules with bosses, on Medium difficulty for everyone.
- Both players see exactly the same pieces in the same places. Each player plays on their own board, and power-up bubbles are random for each player.
- The extra-life bubble only appears when you're on your last life.
- A red and blue bar at the top shows how the two scores compare, live.
- When you run out of lives, you watch your opponent's board until they're out too. Then the higher score wins.
- Pausing is limited to 20 seconds, after which the match resumes on its own.
- Leaving the match, or losing connection for more than 25 seconds, counts as a loss.
- Winning gives 50 tokens. Your wins, losses and draws are shown in the Account window.

### Duel leaderboard

Each duel mode has its own leaderboard of the top 50 runs. A player can appear with up to 3 runs, and each row shows the opponent and the result. Runs from matches you left early don't count.

## Privacy

Diagonaut stores only what it needs to run accounts, cloud saves, leaderboards, friends and duels. The full policy is at [diagonaut.com/privacy](https://diagonaut.com/privacy) and inside the game.

## Tech

- A single `index.html` file: plain JavaScript, HTML5 canvas for the game, DOM for the interface
- [Firebase](https://firebase.google.com/) Authentication and Cloud Firestore for accounts, cloud saves and the leaderboard
- Firebase Realtime Database for friends, online status, matchmaking and live duels
- Hosted on GitHub Pages, with the domain on Cloudflare

## License

Copyright © Muhammed Kürşad Topkara (Kursuvat). All rights reserved. See [LICENSE](LICENSE).
