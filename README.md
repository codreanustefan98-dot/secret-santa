# 🎄 Christmas invite — locked present game

## Files
- `index.html` — the invite game (what guests open)
- `santa.html` — makes a personal invite link for each friend (don't send this one to guests)

## Put it on GitHub Pages
1. Make a new repo (e.g. `craciun`) and upload both files.
2. Settings → Pages → Source: "Deploy from a branch" → `main` / root → Save.
3. After a minute it's live at `https://<your-username>.github.io/craciun/`.

## Customise
Everything is in the `CONFIG` block at the top of the script in `index.html`:
- `code` — the 4-digit lock code (digit 1 = Counting Elves, digits 2–4 = Santa's Riddle)
- `jigsawNumbers` — numbers on the presents in the jigsaw (a trap for the lock, a key for the riddle)
- `geo` — Street View location, Google Maps key and accepted answers for "Where's Santa?"
- `riddle` — riddle text + accepted answers
- `music` — the looping song + 3 mistake songs in the `songs/` folder
- `invite` — date, place, snacks line and the DrawNames link
- `party` — date, place, dress code, RSVP…
- `naughtySeed` — names already on the Naughty List (inside jokes)
- `elf.onlyHitsCount` — `true`: missed elves don't count; `false`: all elves count
- difficulty knobs: elf speed, jigsaw piece/fire chances

## Send it out
1. Open `https://<you>.github.io/secret-santa/santa.html`
2. Press **WhatsApp** next to each name — everyone gets their own link.
3. "I'm in!" sends them to the DrawNames pool; run the draw on DrawNames once everyone has replied.

## Testing tricks
- `index.html?dev` — shows buttons to skip stations
- `index.html?reset` — wipes your progress on that device
