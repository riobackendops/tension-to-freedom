# From Tension to Freedom — landing page

Registration landing page for Dr. Yonatan Grinberg's free live masterclass.

**Tuesday, October 20 · 8–9 PM ET · Live on Zoom · Free**

Date, time and join link verified against the Google Calendar invite
(`calendar.app.google/fXdDJd1bmqvxG8Rj9`).

## Files

| Path | What it is |
| --- | --- |
| `index.html` | The whole page — markup, styles and script in one file. No build step, no dependencies. |
| `img/yonatan-cutout.webp` | Hero figure, cut out against the navy field |
| `img/bow-hand.jpg` | Bow-hold detail, "How it works" |
| `img/yonatan.jpg` | Portrait, "About the instructor" |

Fonts load from Google Fonts: Oranienbaum (the poster title), Cormorant Garamond
(headings and serif body moments), Work Sans (UI and body), Pinyon Script (the swash
capitals, the hero subline and the signature).

## How it's structured

One file holds two views. `#view-register` is the landing page; `#view-thanks` is the
success page. Submitting the form hides the first and shows the second.

## Before this goes live

1. **Wire the form.** `index.html` has a marked `NOTE FOR BUILD` comment in the script
   where the submit handler should post to the email platform. Right now it swaps to the
   success view locally so the copy can be reviewed in place.
2. **Turn on the Zoom waiting room.** The join link and passcode are in the page source
   of a public site, so the waiting room is what actually controls who gets in.

## Brand

Colours, type and voice follow the Dr. Yonatan Grinberg brand kit; copy follows the
approved masterclass landing-page copy. Both live outside this repo, with the project assets.
