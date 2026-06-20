# Summer Smiles

A cute beach-themed photobooth web app that takes a 3-photo strip, lets you decorate it with draggable emoji stickers, and downloads the final strip as a PNG.

## Features

- Live camera preview using the MediaDevices API
- Three-shot photobooth strip flow
- Timer options: 3s, 5s, and 10s
- Small draggable beach stickers
- Sticker decoration before taking photos and after the strip is created
- Finished photo strip preview
- PNG download with timestamped filename
- Responsive single-file app with inline CSS and JavaScript
- Beachy plaid background, soft shadows, rounded frames, and handwritten-style typography

## Files

- `index.html` - the complete app, including HTML, CSS, and JavaScript

## How To Run

Because camera access usually requires a secure origin, run the file through a local server instead of opening it directly from Finder.

From this folder:

```bash
python3 -m http.server 4173
```

Then open:

```text
http://localhost:4173/index.html
```

Allow camera permission when the browser asks.

## How To Use

1. Pick a timer duration.
2. Tap beach stickers to add them to the camera preview.
3. Drag stickers around the video frame.
4. Click `Snap Strip`.
5. The app captures 3 photos with the selected countdown.
6. After the strip appears, tap stickers again to decorate the finished strip.
7. Click `Download` to save the final PNG.

## Notes

- If camera permission is blocked, allow camera access in the browser settings and reload the page.
- The app uses Google Fonts for `Fredoka One` and `Gaegu`.
- No build step or external JavaScript libraries are required.
