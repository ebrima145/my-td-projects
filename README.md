# TD Share

A couple of TouchDesigner projects built on webcam hand tracking.

Made by **Ebrima** · Instagram [@ebjxyz](https://www.instagram.com/ebjxyz/)

| File | What it is |
|---|---|
| `hand_lights.toe` | Hand-tracking driven lights |
| `ripple_effect.toe` | Ripple effect |

## Setup

The projects need the **MediaPipe plugin for TouchDesigner** by torinmb (MIT license).
It isn't in this repo (`MediaPipe.tox` alone is 180 MB, over GitHub's file size limit).

1. Download `release.zip` from the plugin's releases page:
   https://github.com/torinmb/mediapipe-touchdesigner/releases
   (these projects were built with **v0.5.3**; newer versions will probably work too)
2. Unzip it and copy its `toxes` folder into a `MediaPipe` folder here, so you end up with
   `MediaPipe/toxes/MediaPipe.tox` and `MediaPipe/toxes/hand_tracking.tox` next to the `.toe` files.
3. Open a `.toe` file in TouchDesigner and allow webcam access.

Keep the folder layout as it is: the projects look for the components at `MediaPipe/toxes/`.
