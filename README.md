# Safe Pilot

A self-contained arcade flight demo about safety filters. Steer the ship with pointer, touch, WASD, or arrow keys; switch Guardian ON/OFF to feel how the filter changes the route through the asteroid field.

## Fusion and implementation

Safe Pilot fuses pointer-steered arcade flight with a simplified per-obstacle half-space velocity filter. Each frame, iterative projection pushes the desired velocity into the locally safe constraints around nearby asteroids. The glowing amber rays show active outward directions; the cyan arrow shows the filtered velocity. This is an independent teaching implementation, not a reproduction of the paper's spectral-selection algorithm, and it does not establish a real-world safety guarantee.

## Paper

Inspired by “Convex Safety Filtering via Spectral Selection for Nonconvex Safe Sets” by Juan Augusto Paredes Salazar, James Usevitch, and Ankit Goel ([arXiv:2610.12324](https://arxiv.org/abs/2610.12324)). The demo is not endorsed by the authors. Paper license: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). No paper code was copied.

## Run

Open `demo/index.html` in a modern browser. It uses no external assets, libraries, or network requests.
