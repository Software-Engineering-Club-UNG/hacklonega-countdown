# Hacklonega Countdown

Projector countdowns for Hacklonega, the Hacktoberfest Hack Day at the University of North Georgia in Dahlonega, Georgia, on October 24, 2026.

| Page | Counts down to |
| --- | --- |
| `index.html` | The 9:30 AM opening ceremony in MCCB 109 |
| `judging.html` | 4:45 PM judging, with the 4:30 PM submission deadline |

Made by the UNG Software Engineering Club.

## What they do

- Count down to the event, then switch to "starting now." with confetti.
- Swap between two looks every 40 seconds with a pixel wipe: the SWE club Typewriter look and the Hacktoberfest 2026 look.
- Bounce the Dahlonega steeple ball from [hacklonega.dev](https://hacklonega.dev) around the screen like the old DVD logo. When it hits a corner, the corner counter goes up.
- Type out tips for hackers.
- Play no sound, so you can run your own music.

The judging page also:

- Shows the submission deadline under the clock with its own countdown. It flashes in the last 5 minutes.
- Shows "pencils down." at 4:30, then points hackers to their judging room in Discord.
- Shows the rest of the day: 1:00 Lunch, 4:30 Submit, 4:45 Judging, 5:30 Awards. The next item is highlighted and past ones are crossed out.
- Shows 16 photos from the day. In the club look they open as retro desktop windows that load in blocky passes, with the time each was taken in the status bar. In the Hacktoberfest look they scroll past as a strip of photo cards where the world map was.

## Run it

Download the page you want and open it in a browser. Each page is one file with no build step.

| Key | Does |
| --- | --- |
| `F` or double-click | Fullscreen |
| `M` | Switch looks now |
| `C` | Aim the ball at the next corner |

Add `#demo` to the end of the address to preview the last 20 seconds. On the judging page, submissions close 10 seconds before the end of the demo.

The cursor and key hints hide after a few seconds without mouse movement. The pages ask the browser to keep the screen awake.

The Hacktoberfest look loads Inter, Martian Mono, and Barlow Semi Condensed from Google Fonts. Offline, it falls back to system fonts.

## Change the times

- `index.html`: edit `OPENING` near the top of the script. It is in UTC: 9:30 AM EDT is 13:30 UTC.
- `judging.html`: edit `JUDGING` and `DUE` near the top of the script. `eastern(16, 45)` means 4:45 PM Eastern. The schedule strip times are the `data-until` values in the markup, also in Eastern time.

## Credits

Where every image, logo, font, and dataset came from is in [docs/ASSET-PROVENANCE.md](docs/ASSET-PROVENANCE.md).
