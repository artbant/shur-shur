# Rustle

A tactile web toy: a plastic bag you can crumple, rub, and shake until it collapses into a tiny ball.

Built with a 352-vertex physics mesh, procedural pink-noise audio, and device haptics. Zero dependencies — everything lives in a single `index.html`.

## Controls

- **Tap** — local rustle at that point
- **Drag** — sustained rub sound, trail of creases
- **Shake** — multiple impacts (requires gyro permission on iOS)
- **Volume** slider — adjust rustle loudness
- **Smooth** button — reset after 5+ touches

Fully collapses into a crumpled ball at 150 touches.

## Notes

- Vibration does not work in iOS Safari (Apple hasn't implemented the Vibration API)
- Gyroscope on iOS 13+ requires explicit permission — tap the `gyro` button to trigger the system prompt

## Credits

Made as a minimal tactile-noise experiment.
