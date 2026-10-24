# Asset provenance

All three pages, `index.html`, `judging.html`, and `closing.html`, use the same assets, except that `judging.html` and `closing.html` show event photos where `index.html` shows the world map.

| Asset | Source and rights | Use |
| --- | --- | --- |
| Steeple ball artwork | The project-owned Dahlonega steeple composition from [Israel-Jauregui/Hacklonega](https://github.com/Israel-Jauregui/Hacklonega) (`src/App.tsx`), embedded as SVG | Texture for the bouncing ball. The back of the ball reuses the same landscape without the steeple |
| Steeple sphere renderer | Ported from the project-owned `steeple-sphere.ts` and `steeple-physics.ts` in the same repository | WebGL sphere, rolling, and squash on impact. A flat 2D fallback runs without WebGL |
| Pixel mountain ridges | Project-owned SVG from `MountainBackdrop.tsx` in the same repository | Club look background |
| `>SWE▮` logo | [club-styling-guide](https://github.com/Software-Engineering-Club-UNG/club-styling-guide) `assets/logo/swe-prompt.svg`, unaltered | Club look footer |
| MLH logo | Major League Hacking's mark as shown in the "Powered by" lockup on hacktoberfest.com (2026), unaltered | "Powered by" credit in both looks. Trademark of Major League Hacking |
| DigitalOcean logo | DigitalOcean's mark as shown in the "Presenting partner" lockup on hacktoberfest.com (2026), unaltered | Track credit in both looks. Trademark of DigitalOcean |
| Snowflake logo | Snowflake's mark as shown in the sponsor list on hacktoberfest.com (2026), unaltered | Track credit in both looks. Trademark of Snowflake |
| World map | Rasterized from [Natural Earth](https://www.naturalearthdata.com/) 1:110m land, public domain | Pixel map in the Hacktoberfest look of `index.html` |
| Event photos | 16 photos of participants taken at Hacklonega on October 24, 2026, provided by the organizers. Resized to 1280px and stripped of all metadata, including location | Photo windows and the photo strip in `judging.html`, embedded as JPEG |
| Closing photos | 43 photos taken at Hacklonega on October 24, 2026, provided by the organizers, including one drone photo. Converted from HEIC, resized to 1280px, and stripped of all metadata, including location | Photo viewer and the photo strip in `closing.html`, embedded as JPEG |
| Hacktoberfest look | Newly authored layout. Its colors and type choices follow the hacktoberfest.com 2026 site | No Hacktoberfest logo artwork or site code is included |
| Fonts | Inter, Martian Mono, and Barlow Semi Condensed from Google Fonts (SIL Open Font License). Courier New and Tahoma are system fonts | No font files are distributed |

Partner logos are shown only to credit this MLH Hack Day's organizer partner and tracks. Remove any of them if MLH or the partner asks.
