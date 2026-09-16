# webthing

A minimal Spotify Connect desk controller / ambient display for an old Android phone.

- Spotify OAuth via Authorization Code + PKCE (no client secret)
- Now-playing artwork, metadata, progress, transport controls
- Spotify Connect device switching and volume
- Idle clock
- Decorative motion visualizer (not derived from Spotify audio)

## Spotify setup

The app uses client ID `535468c73264439eb3e61bca260e4c3c`.
Add every hostname you use as an exact Spotify redirect URI, including the trailing slash. For example:

- `https://webthing-notdevin-1s-projects.vercel.app/`
- `https://webthing.devinliu.xyz/`

Required scopes:

- `user-read-playback-state`
- `user-read-currently-playing`
- `user-modify-playback-state`

Spotify playback control requires Premium.
