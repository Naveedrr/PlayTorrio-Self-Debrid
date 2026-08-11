# Self-Debrid integration

Added a `Self-Debrid` provider to PlayTorrio Native.

## Changes
- New Debrid Service option: `Self-Debrid`.
- Configurable Self-Debrid server URL.
- Optional API key field.
- Calls Self-Debrid's AllDebrid-compatible `/v4/link/unlock` endpoint.
- Rewrites Self-Debrid's `localhost` stream URLs to the configured server host so PlayTorrio can run on another device.
- Added dispatcher support for normal playback and resume/next-episode playback.
- Added a GitHub Actions workflow to build a release Android APK.

The APK still requires a running Self-Debrid server. This project does not bundle Self-Debrid or qBittorrent.
