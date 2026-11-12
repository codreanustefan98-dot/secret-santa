# 🎄 Christmas invite — locked present game

## Files
- `index.html` — the invite game (what guests open)
- `santa.html` — your Secret Santa organiser page (don't send this one to guests)

## Put it on GitHub Pages
1. Make a new repo (e.g. `craciun`) and upload both files.
2. Settings → Pages → Source: "Deploy from a branch" → `main` / root → Save.
3. After a minute it's live at `https://<your-username>.github.io/craciun/`.

## Customise
Everything is in the `CONFIG` block at the top of the script in `index.html`:
- `code` — the 4-digit lock code (digit 1 = elves, 2 = snowman, 3+4 = riddle answer)
- `giftDigits` — numbers on the [red, green, gold] gifts under the tree
- `riddle` — your riddle text + accepted answers (must equal code digits 3+4)
- `party` — date, place, dress code, RSVP…
- `naughtySeed` — names already on the Naughty List (inside jokes)
- `elf.onlyHitsCount` — `true`: missed elves don't count; `false`: all elves count
- difficulty knobs: elf speed, snowflake goal, fire chance, puzzle size (3 = 3×3, 4 = 4×4)

## Send it out
1. Open `https://<you>.github.io/craciun/santa.html`
2. Type the names, budget, any couples who shouldn't draw each other → **Trage la sorți**
3. Press **WhatsApp** next to each name — everyone gets their own link. Their match is revealed only after they open the present.

## Testing tricks
- `index.html?dev` — shows buttons to skip stations
- `index.html?reset` — wipes your progress on that device
