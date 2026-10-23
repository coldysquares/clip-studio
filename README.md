# Clipwave Studio

A browser-based audio clipping and visualizer tool.

## Features

- 29-second and 59-second clip presets
- Waveform-based clip selection
- WAV and MP3 audio export
- Audio-reactive visualizer
- Landscape and portrait video layouts
- Optional title and artist overlays
- Optional fade-in and fade-out
- Progressive Web App support

## Development

This is currently a static HTML application.

Run it through a local HTTP server rather than opening
index.html directly if you want to test PWA functionality.

## Deployment

Import this repository into Vercel.

Framework preset: Other
Build command: leave blank
Output directory: .
Install command: leave blank

The app should be served over HTTPS for service workers
and PWA installation.

## Privacy

Audio files are processed locally in the browser.
The app does not intentionally upload source audio.

MP3 encoding currently loads the encoder from jsDelivr,
so that feature requires network access unless the
library has been cached.

## Audio rights

Only edit and publish audio you own or have permission
to use.