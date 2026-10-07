# ABC 123 — prototype v0.1

A small offline web app for a 4-year-old: letters (name → sound → word) and numbers (count, "how many?", a 1–10 board walk), with English and Japanese shown together and spoken one language at a time.

## Install on iPad / iPhone
1. Open the site URL in **Safari**.
2. Share → **Add to Home Screen**.
3. Open it from the Home Screen once while online (it then works offline).
4. Parent settings: **hold the ⚙︎ button (top right) for 2 seconds** → set the child's name and Toshi's photo.
5. Optional: Settings → Accessibility → **Guided Access** to lock the device to this app.

## Privacy
No accounts, ads, analytics or network calls. Name, photo and progress stay in the device's local storage.

## Updating
After changing files, bump `VERSION` in `sw.js` so devices pick up the new version (open the app twice).

## What's in v0.1
- Session: hello → letter card → find the letter (+1 review) → child picks *How many?* or *Toshi's walk* → EN/JP bridge → home mission → bye.
- Two sessions a day, then "Toshi is resting".
- Mastery = correct on 3 separate days (parent panel).
- Speech uses the device voices (EN/JP). Family recordings come in the MVP.
