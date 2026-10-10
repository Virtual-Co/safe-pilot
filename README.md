# Safe Pilot

A neon arcade game. Move your pointer to lead a swarm of drones through a storm of drifting rocks and fast bullets. Each drone carries a velocity safety filter: it slides around obstacles on its own, shown as glowing mint arcs, so the skill is skimming danger for near-miss combos while grabbing stars that grow the swarm. Waves escalate; lose every drone and it is over.

The filter is a per-obstacle half-space projection of each drone's velocity (control-barrier style), as in the cited paper. The game is a toy built around that idea and does not reproduce the paper's experiments. Single offline file: demo/index.html, no third-party code or assets.

## License

MIT. See [LICENSE](LICENSE).
