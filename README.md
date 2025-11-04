# MAEJ Cozy Mystical PS Skin (Gamepad Viewer)

This pack includes a themed **PlayStation** (PS/DualShock layout) skin built around your brand color `#e56e9f`, leaves motif, and chibi art.

## Use in OBS
1. Host this folder somewhere that serves static files (GitHub Pages/Netlify/etc.).
2. Copy the public URL to `skin.css`.
3. In OBS Browser Source, set the URL to:
   `https://gamepadviewer.com/?p=1&css=YOUR_PUBLISHED_URL/skin.css`

## Tweak positions
Open your GPV page, **Inspect** the DOM, and adjust `top/left/width/height` values inside `skin.css` to line up with your controller art on your setup.

## Notes
- Face buttons use selectors: `.button.triangle`, `.button.circle`, `.button.cross`, `.button.square`.
- D-Pad: `.dpad .up/.down/.left/.right`.
- Triggers/Bumpers: `.trigger.left/.right .value`, `.bumper.left/.right`.
- Start/Back map to **Options/Share** visuals in this pack.
