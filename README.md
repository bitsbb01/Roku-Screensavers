# Roku Screensavers

A home for standalone Roku screensaver projects and their build notes.

## Aquarium collection

The planned aquarium will be one installable Roku screensaver with multiple animated scenes that can rotate or shuffle while the Roku is idle. It will appear as one screensaver in Roku settings, not as a separate menu entry for every scene.

Roku screensavers do not play video files directly. The animation will be built from artwork and Roku SceneGraph animations; video clips can be used as visual references or converted into image frames where suitable.

## Project layout

Each screensaver lives in its own folder under `screensavers/`. Keep its source, assets, build notes, and packaged releases together so it can be maintained and installed again later.

Do not commit Roku passwords, account credentials, or other secrets.