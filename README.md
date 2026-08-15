# Garmin Activity Editor

A private, client-side web tool for correcting Garmin activities where an active round was recorded as rest.

## What it does

- Opens a local `.FIT` file in the browser—no Garmin account or activity upload required.
- Finds Garmin **Set** records (global message 225).
- Converts Rest sets to Round / Active, individually or all at once.
- Lets you edit a set, delete Rest sets, or add a round.
- Preserves the FIT records that contain GPS, heart-rate, pace, and other underlying activity data.
- Downloads an edited copy; the original file is not overwritten.

## Use on iPhone

1. Open the GitHub Pages site in Safari.
2. Tap **Choose a Garmin .FIT file** and select an activity from Files.
3. Make the desired Set edits.
4. Tap **Save corrected FIT**.
5. Keep the original file and test the downloaded copy in Garmin Connect.

## Important limitation

This is a prototype FIT editor. Its export has not yet been validated against the user's FIT file and Garmin Connect, so it must not be considered production-safe. Always retain the original activity file.

## Development

The app is static HTML/CSS/JavaScript. Open `index.html` through a local web server for desktop testing, or use the GitHub Pages deployment.

