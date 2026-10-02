# Blast Multimedia

Blast Multimedia is a FiveM multimedia resource currently in development. This repository is the public project overview.

## Current development

The first module is an interactive boombox with music search, direct URL playback, playlists, nearby positional audio, playback controls, and an expanded now-playing interface. The interface includes a lyrics view. A browser preview is used during development alongside the FiveM resource.

## Planned modules

- **Smart TV:** media apps, remote control, nearby mouse interaction, and interface personalization.
- **Voice radio:** frequency selection, volume controls, participant and speaking indicators, and optional radio voice effects.
- **Administration:** an in-game configuration panel with ACE permissions for the multimedia modules.

The resource aims to keep its multimedia logic independent of roleplay frameworks, with adapters for server integrations where needed.

## Lyrics integration

Integration with the Spicy Lyrics developer API is planned and is not yet active. Lyrics will be displayed inside the multimedia player for its users.

The implementation is intended to:

- Request lyrics through the server, keeping secret API credentials outside the client interface.
- Display provider attribution from each response alongside the lyrics, including linked uploader and maker credits when supplied for community syncs.
- Refetch or discard any cached Spicy Lyrics response within 30 days.
- Keep lyrics inside the application rather than providing a public lyrics API, data download, dataset, mirror, or archive.
- Match the song version and use the playback clock for synchronization.

API access does not grant rights to song lyrics. Any required rights permissions must be addressed separately before use or distribution.

This is an independent project and is not affiliated with or endorsed by Spicy Lyrics, Spotify, Apple Music, YouTube, or Cfx.re.

## Status

In development. This public repository contains the project description; it does not provide a downloadable release.
