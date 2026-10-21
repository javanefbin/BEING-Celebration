# Japarty

A Black History party quiz for the BEING Celebration. Open `index.html` on the big screen to host. Players join on their phones by scanning the QR code.

## Games
- **Quiz Rush**: timed multiple choice, faster answers score more.
- **True or False Blitz**: 10-second rounds.
- **Name That Tune**: add your own song clips, plus two public-domain starter tunes.
- **Japarty Board**: six categories with a Daily Double and Final Japarty (one shared screen).
- **Timeline Shuffle**: drag four events into order (one shared screen).

## Live games on phones
Live games use a free [Supabase](https://supabase.com) project so anyone can join without an account.

1. Create a free Supabase project.
2. In **Project Settings → API Keys**, copy the Project URL and the anon or publishable key.
3. Either open the site, choose **Let anyone join** and paste them, or put them in the `LIVE_SERVER` line near the top of `index.html` so every visitor is ready.
4. Choose **Host a live game**. Players scan the QR code; no sign-in or app needed.

The free plan handles about 200 phones at once. Free projects pause after a week without use, so open the Supabase dashboard the day before an event.
