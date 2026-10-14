# The Last Ember

A cinematic ASCII dark-fantasy action RPG that runs entirely in the browser — one self-contained `index.html`, no build step, no dependencies.

Sir Caelan Voss died holding a cathedral door so twelve children could escape. Something brought him back. Every time he dies again, he loses a memory — and what he remembers decides how the story ends.

## Play

Open `index.html` in any modern browser, or play the deployed version.

| Action | Keys |
|---|---|
| Move | WASD / Arrow keys |
| Attack | J or left-click |
| Block / Parry | K or right-click (hold) |
| Roll | Space |
| Interact / Talk | E |
| Drink flask | F |
| Ember burst | R |
| Call your horse | H |
| Memories | M |
| Gear | I |
| Mute | N |
| Skip prologue | Esc |

Touch controls appear automatically on phones and tablets.

## Chapters

- **Prologue** · The Last Good Autumn
- **I** · The Bell That No Longer Rings
- **II** · The Green Road
- **III** · The Fort of Oaths
- **IV** · The Crypt of Kings
- **V** · The Ashen Crown

Three endings, decided by the memories you keep.

## Deploy on Vercel

1. Push this folder to a GitHub repository.
2. On [vercel.com](https://vercel.com) choose **Add New → Project** and import the repository.
3. Framework preset: **Other**. Leave Build Command and Output Directory empty.
4. Click **Deploy**.

Every push to the main branch redeploys automatically.

## Tech

Plain HTML, CSS and JavaScript. Rendering is a WebGL shader that turns painted scenes into ASCII glyphs; music and sound effects are generated live with the Web Audio API. Progress saves to the browser's local storage.
