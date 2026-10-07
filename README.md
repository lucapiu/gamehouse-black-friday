# gamehouse-black-friday

Black Friday marketing campaign for GameHouse.com: a spin-to-win wheel popup.

## What it does

`wheel.html` is a self-contained widget (inline HTML, CSS, JS; no logos, no backend). The only external request is the Source Sans Pro font from Google Fonts.

- The visitor clicks the wheel to start it; it never spins on its own.
- The wheel always lands on the same **30% OFF** slice (`WIN_INDEX`). The wheel has six pastel slices (2x 5% OFF, 2x 10% OFF, 1x TRY AGAIN, 1x gold 30% OFF); the others are decorative.
- It then reveals the code `COUPON123` with a **Copy** button.
- Styled with gamehouse.com's palette (sky blue `#2eb2ea`, orange `#ff6b42`) and the Source Sans Pro font.
- Responsive from phone to desktop, and honors `prefers-reduced-motion` (skips the animation and shows the code).

## Add it to getsitecontrol

1. In getsitecontrol, create a new widget and pick **Custom HTML** (or add a Custom HTML block to a popup).
2. Paste the entire contents of `wheel.html` into the HTML editor.
3. Under targeting, choose the pages and triggers you want (e.g. on page load or exit intent).
4. Set the widget background to transparent and remove any default title or button so only the wheel shows.
5. Preview on desktop and mobile, then publish.

To change the code, edit `COUPON` in the script and the `#ghw-code` text. To preview locally, open `wheel.html` in a browser.
