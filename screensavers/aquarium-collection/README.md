# Aquarium Collection

## Goal

Create one standalone Roku screensaver app that installs once and cycles through ten aquarium scenes while the Roku is idle.

## Planned scenes

The ten scenes will be defined as the artwork and animation are created. The app can either rotate through them in order or shuffle them. Roku screensaver settings may be used for simple choices where practical.

## Implementation notes

- Use Roku SceneGraph animations for fish movement, bubbles, drifting particles, gentle plant movement, and transitions.
- Build the motion as graphics and timed animation rather than direct video playback, which Roku screensavers do not support.
- Keep the source, artwork, build instructions, and final Roku package in this project folder.
- Ensure the saver exits promptly when a remote button is pressed.

This folder is a project outline; source code and artwork will be added as the scenes are built.