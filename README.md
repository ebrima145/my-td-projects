# TD Share

A couple of TouchDesigner projects built on webcam hand tracking.

| File | What it is |
|---|---|
| `hand_lights.toe` | Hand-tracking driven lights |
| `ripple_effect.toe` | Ripple effect |
| `MediaPipe/toxes/hand_tracking.tox` | Hand tracking component used by the projects |

## Setup

The projects need the **MediaPipe plugin for TouchDesigner** by torinmb (MIT license).
Its main component, `MediaPipe.tox`, is 180 MB, which is over GitHub's file size limit, so it isn't in this repo.

1. Download `release.zip` from the plugin's releases page:
   https://github.com/torinmb/mediapipe-touchdesigner/releases
   (these projects were built with **v0.5.3**; newer versions will probably work too)
2. Copy `MediaPipe.tox` from the zip into this repo's `MediaPipe/toxes/` folder, next to `hand_tracking.tox`.
3. Open a `.toe` file in TouchDesigner and allow webcam access.

Keep the folder layout as it is: the projects look for the components at `MediaPipe/toxes/`.
