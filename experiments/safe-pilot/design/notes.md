# Safe Pilot — experience notes

## Visual system
- Palette: deep blue-black space (`#071018`), layered slate panels, luminous cyan for the guardian and intended safe flight, amber for obstacle constraints, and coral red for raw-flight impact.
- Typography: system sans stack only. Large, tightly tracked two-line title; compact uppercase instrument labels; tabular score numerals.
- Motion: continuous but restrained star drift and asteroid spin, eased ship response, soft target pulse, glows on the safety geometry, brief impact shake and particle burst. Cap device pixel ratio at 1.6. Under `prefers-reduced-motion`, remove star drift and decorative pulsing while keeping direct control feedback.

## Interaction and first five seconds
- The page opens with a brief headline, one sentence, and an immediately moving asteroid field. The player's ship and target marker are visible without reading a paragraph.
- Pointer/touch drag steers directly; tap sets a heading; WASD and arrows provide keyboard steering. Guardian ON/OFF is a persistent, keyboard-focusable button.
- First five seconds: notice the moving field, touch/drag toward a rock, and see amber constraint rays plus the cyan filtered velocity bend. Toggle Guardian OFF to compare the unfiltered response.
- On-screen hint: “DRAG TO STEER · WASD / ARROWS — Tap anywhere to set a heading.”

## Layout
- Desktop: title and one-line pitch upper left, mode toggle and compact science note upper right, score instruments lower left, control hint lower right.
- Mobile: full-height 390×844 canvas; compact toggle; science note kept above the lower HUD; title and controls stay visible without blocking the central flight lane.
