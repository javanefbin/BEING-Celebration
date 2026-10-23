# Japarty

A Black History party quiz for the BEING Celebration. Open `index.html` on the big screen to host. Players join on their phones by scanning the QR code.

## Games
- **Quiz Rush**: timed multiple choice, faster answers score more.
- **True or False Blitz**: 10-second rounds.
- **Guess the Song**: add your own song clips, plus two public-domain starter tunes.
- **Cash or Case**: pick a closed case, open the others, and decide whether to take the Banker's offer. A Black History question before each offer raises it 10% for a right answer. Choose 16, 24, 32 or 40 cases. In live games everyone plays their own case on their phone.
- **Japarty Board**: six categories with a Daily Double and Final Japarty (one shared screen).

Press **Play** on any one-screen game and a **Who's playing?** box asks for your name. Add a box for each person playing on the same screen (up to 8), or choose **Play as teams instead**. Solo play works too.
- **Timeline Shuffle**: drag four events into order (one shared screen).

## Score history
Every finished game is saved: one-screen games, live games and Arena duels. Open **Score history** from the home screen (it shows the reigning champion) or from any results screen:
- **Leaderboard**: everyone ranked by wins, then top-3 finishes, then best score, filtered by game and by all time, this week or today.
- **Recent games**: each game with its date, type and full results.
- **Records**: the high score for each game, most wins and the biggest live game.
- **My results**: your own finishes from live games on your phone, personal bests and your Arena record.

Results screens call out **new records** and **new personal bests**. On this website each device keeps its own history (download it as a CSV anytime). On the shared Claude page, games hosted by editors go into one history everyone sees.

## Arena
Everyone who has the site open shows up as online, with a count on the home screen. Open **Enter the Arena** to see who's around and challenge anyone on their own device:
- **Quiz duel**: 5, 7 or 10 questions, from all categories or just one. Faster right answers score more.
- **True or false duel**: 10 quick statements.
- **Speed round**: 60 seconds to answer as many as you can. Most right answers wins.

**Quick match** posts an open challenge that the first available person can take. You can search the online list, show only available people, switch off challenges, send quick reactions during a duel, and track your wins, streaks, best scores and recent duels. Records are kept on each device.

## Party playlist
Open **Playlist** on the big screen to play songs one after another during the lobby and leaderboards. While a live game is open, players can add a music file from their phone (up to 12 MB, 3 waiting per player). You approve each song before it plays, and the playlist plays quietly or pauses while players answer. Songs stay on the host computer until the page is closed. Only play music you have the right to play at your event.

## Poster
In the live lobby, choose **Make a poster** for a printable sign with the QR code, PIN and steps. To print ahead of time, set your own PIN under **More settings** and use **Play again with the same PIN** for every game.

## Updates
The version number is shown at the bottom of the home screen. When a newer version is published, the site shows a **Refresh now** prompt. Players rejoin their game automatically after refreshing.

## Live games on phones
Live games work with no setup. Open the site on the big screen, choose **Host a live game**, and players scan the QR code. No sign-in or app needed.

The site connects through a free public live server (with a second one as a backup). Game details such as nicknames and answers pass through that shared server. If your Wi-Fi blocks it, players can switch to phone data.

### Optional: your own private live server
1. Create a free [Supabase](https://supabase.com) project.
2. In **Project Settings → API Keys**, copy the Project URL and the anon or publishable key.
3. Open the site, choose **Let anyone join** and paste them, or put them in the `LIVE_SERVER` line near the top of `index.html`.

The free Supabase plan handles about 200 phones at once. Free projects pause after a week without use, so open the Supabase dashboard the day before an event.
