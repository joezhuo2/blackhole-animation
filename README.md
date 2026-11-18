# Black Hole Animation

An interactive 3D black hole simulation in a single HTML file. It renders the event horizon shadow, a rotating accretion disk with Doppler brightening, gravitational lensing and a starfield, all in one WebGL shader with no dependencies.

## Run

Open `index.html` in a modern desktop browser. No build step or server is needed.

## Controls

| Action | Mouse / keyboard | Touch |
| --- | --- | --- |
| Orbit | Drag | One-finger drag |
| Zoom | Scroll, or `+` / `-` | Pinch |
| Pan | Shift + drag, or right-drag | Two-finger drag |

Keep zooming in to cross the event horizon and reach the center. Camera movement has inertia and glides to a stop after you let go.

The control panel adjusts rotation speed, disk intensity and lensing strength, toggles the starfield and annotations, pauses the simulation and resets the view.

## Note

The lensing is a visual approximation, not a physically exact ray trace.
