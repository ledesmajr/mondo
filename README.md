# MONDO

Faith, body and plan. One day at a time.

MONDO is a web app that installs on your iPhone home screen, works offline, and keeps all your data on your phone. No account and no subscription.

## Put it online (free, one time)

Your phone needs to open MONDO from a web address once. Pick one option.

**Option A: Netlify Drop (easiest, about 2 minutes)**
1. On your laptop, unzip this folder.
2. Go to https://app.netlify.com/drop and sign in (free).
3. Drag the whole `mondo` folder onto the page.
4. You get a link like `https://something.netlify.app`. Rename it in Site settings if you want, e.g. `mondo-john.netlify.app`.

**Option B: Vercel (same as your other projects)**
1. Open the `mondo` folder in Terminal or Claude Code.
2. Run `npx vercel` and follow the prompts (Framework: Other, no build command).
3. Run `npx vercel --prod` to get your permanent link.

## Install on your iPhone

1. Open your MONDO link in **Safari** (it must be Safari).
2. Tap the **Share** button (square with an arrow).
3. Scroll down and tap **Add to Home Screen**, then **Add**.
4. Open MONDO from the new icon. It now runs full screen and works offline.

## Your data

- Everything saves automatically on your phone.
- Back up once a week: **Settings → Back up**. Save the file to Files or iCloud Drive.
- New phone or reinstall: **Settings → Restore** and pick your backup file.
- Deleting the home screen icon can delete the app's data, so back up first.

## Updating MONDO later

Change the files (for example with Claude Code), then upload or deploy again to the same link. The app picks up the new version the next time you open it with internet. Your data stays.

## Files

- `index.html`: the whole app
- `sw.js`: lets the app work offline
- `manifest.json`, `icons/`: the name and icon for your home screen
