# Downhill

A self-contained HTML5 Canvas playground: exactly 16 colorful dots falling through an endless seeded procedural course. No dependencies, backend, tracking, or build step.

Open `index.html` directly, or serve this folder with any static server. Pause/resume with the button or Space; restart with the button or R. The layout scales for touch screens and caps pixel density at 2 for performance. Reduced-motion preferences start the experience paused.

Physics uses a fixed 120 Hz timestep, gravity, momentum, capped terminal velocity, circle/capsule collisions, restitution, surface friction, equal-mass particle impulses, and damped squash/stretch. A median-following camera advances downhill. Obstacles are generated ahead and discarded behind. The bottom of the viewport is a bouncing floor. Dots retain their identity and are never repositioned or respawned. Random spikes, clubs, jabbers, and shooters permanently eliminate dots until restart; the HUD tracks survivors. Restart repeats the initial seed.

## GitHub Pages

Publish the `main` branch, `/ (root)` folder in Settings → Pages. `index.html` is the complete app and works under a repository subpath. `.nojekyll` bypasses Jekyll. No secrets or environment variables are needed.
