# Tyre Shelf Planner

A single-page web tool for planning shelves for Matchbox / Hot Wheels cars fitted inside an old tyre. Enter your measurements and it draws the layout to scale, works out every cut, and shows how to mark out your wood.

## Features

- **Scale drawing** of the shelves inside the tyre, with the sidewall lip shown over the hidden shelf ends
- **Cut list** with each shelf's length, the height to mark it at (from the inside wall and from the opening edge), the gap above it and roughly how many cars it holds
- **Square or angled ends**: angled ends are bevelled to sit flush on the curved tyre wall, giving the long-point length, bevel angle and short-face length
- **Spacing modes**
  - *Use my wood*: spreads the shelves as evenly as your wood allows
  - *Even*: equal bands across the inside of the tyre
  - *Fixed gap*: every gap exactly the size you set
- **Top and bottom space**: pin the top and/or bottom shelf at a set distance from the wall; leave blank for automatic
- **Board layout**: fits the pieces onto one or more boards (longest first), allowing for saw kerf, and warns if you're short
- **Export**: copy the cut list as text, or save a single A4 PDF of the drawings and cut list

All measurements are in millimetres.

## Using it

Open `index.html` in any modern browser; there's nothing to install or build. To host it, enable **GitHub Pages** for this repository (Settings → Pages → deploy from the `main` branch, root folder).

Your settings are remembered in your browser. The PDF export loads [jsPDF](https://github.com/parallax/jsPDF) from cdnjs; everything else runs offline.

## Measuring your tyre

| Setting | What to measure |
| --- | --- |
| Internal diameter | Across the inside of the tread, at the widest point |
| Sidewall | How far the rubber lip reaches in from the inside wall to the edge of the opening |
| End clearance | Optional allowance taken off each end, e.g. if the inside wall curves towards the sidewalls |

Shelves longer than the opening at their height go in by flexing the sidewall back, which also helps hold them in place.

## Licence

[MIT](LICENSE)
