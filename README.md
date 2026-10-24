# Hacklonega Countdown

A projector countdown for Hacklonega, the Hacktoberfest Hack Day at the University of North Georgia in Dahlonega, Georgia, on October 24, 2026. It counts down to the 9:30 AM opening ceremony in MCCB 109.

Made by the UNG Software Engineering Club.

## What it does

- Counts down to 9:30 AM Eastern, then switches to "Opening ceremony is starting now."
- Swaps between two looks every 40 seconds with a pixel wipe: the SWE club Typewriter look and the Hacktoberfest 2026 look.
- Bounces the Dahlonega steeple ball from [hacklonega.dev](https://hacklonega.dev) around the screen like the old DVD logo. When it hits a corner, the corner counter goes up.
- Types out tips for arriving hackers: the Discord, check-in, rooms, and what to bring.
- Plays no sound, so you can run your own music.

## Run it

Download `index.html` and open it in a browser. It is one file with no build step.

| Key | Does |
| --- | --- |
| `F` or double-click | Fullscreen |
| `M` | Switch looks now |
| `C` | Aim the ball at the next corner |

Add `#demo` to the end of the address to preview the last 20 seconds and the 9:30 moment.

The cursor and key hints hide after a few seconds without mouse movement. The page asks the browser to keep the screen awake.

The Hacktoberfest look loads Inter, Martian Mono, and Barlow Semi Condensed from Google Fonts. Offline, it falls back to system fonts.

## Change the time

Edit `OPENING` near the top of the script in `index.html`. It is in UTC: 9:30 AM EDT is 13:30 UTC.

## Credits

Where every image, logo, font, and dataset came from is in [docs/ASSET-PROVENANCE.md](docs/ASSET-PROVENANCE.md).
