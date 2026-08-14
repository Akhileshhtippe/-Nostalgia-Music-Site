# -Nostalgia-Music-Site
# Nostalgia Music Site

Next.js App Router + TypeScript + Tailwind CSS v4 single-page nostalgia listening room.

## Run

```bash
npm install
npm run dev
```

Open `http://localhost:3000`.

## Add music

Edit `app/player.tsx`. Each song is one line in a playlist array. Replace the placeholder metadata and `videoId` with a YouTube upload you have the right to use and that permits embedding.

The visible YouTube IFrame player is mounted in the artwork slot. It is never hidden or reduced to a 1px/opacity-0 player.

## Backgrounds

- `public/bg/scene-wide.png` is included.
- Add your separately composed portrait asset as `public/bg/scene-tall.png`.

The CSS swaps to the tall asset automatically in portrait orientation.
