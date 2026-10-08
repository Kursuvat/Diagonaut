# Diagonaut

**Play it at [diagonaut.com](https://diagonaut.com)**

Diagonaut is a chess-themed endless runner for the browser. You are a single white pawn racing up a five-lane board. Black pieces come at you, and you capture them the way a pawn does: diagonally. Touch one head-on and the run is over.

The game is built mobile-first and runs in any modern browser, on phones and desktops alike.

## Game modes

- **Classic**: an endless run. Survive long enough and the Black Queen and Black King show up as bosses.
- **Time Attack**: 60 seconds to score as much as you can. No bosses.
- **Dodge Only**: you can't capture anything. Every piece you slip past is worth points.
- **Puzzle**: 36 hand-made levels with up to three stars each.

Every mode except Puzzle comes in four difficulties: Easy, Medium, Hard and Very Hard.

## Features

- Power-up bubbles: shield, multiplier, slow-motion, bomb, extra life and tokens
- A token economy with permanent upgrades
- A market full of cosmetics: piece colors, hats, glasses, companions, trails, auras, capture and defeat effects, enemy piece sets, board themes, promotion to other pieces and profile cards
- Bronze, silver and gold chests
- Levels and XP, achievements, statistics and a tutorial
- 16 languages, including right-to-left Arabic and Moroccan Darija

## Accounts

Playing doesn't require an account. You can start as a guest right away, and your progress is kept on your device.

If you sign in, your progress follows you to every device. You can sign in with:

- **Google**
- **Email and password**, with email verification and password reset

On first sign-in you pick a username: 3 to 16 characters, letters, numbers and underscores only. Usernames are unique. New accounts receive a one-time welcome gift of 1,000 tokens.

You can sign out or permanently delete your account at any time from **Settings → Account**. Deleting an account asks you to confirm your identity first and removes your cloud save, profile and leaderboard entries.

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

## Privacy

Diagonaut stores only what it needs to run accounts, cloud saves and the leaderboard. The full policy is at [diagonaut.com/privacy](https://diagonaut.com/privacy) and inside the game.

## Tech

- A single `index.html` file: plain JavaScript, HTML5 canvas for the game, DOM for the interface
- [Firebase](https://firebase.google.com/) Authentication and Cloud Firestore for accounts, cloud saves and the leaderboard
- Hosted on GitHub Pages, with the domain on Cloudflare

## License

Copyright © Muhammed Kürşad Topkara (Kursuvat). All rights reserved. See [LICENSE](LICENSE).
