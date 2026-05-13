# Spotify - Playlist

## Coverage
`index-only`

## Route
- Namespace: `spotify`
- Namespace Name: `Spotify`
- Route Path: `/playlist/:id`
- Route Name: `Playlist`
- Example: `/spotify/playlist/4UBVy1LttvodwivPUuwJk2`
- URL: `open.spotify.com`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `outloudvi`
- Source Location: `playlist.ts`
- Source Module: `() => import('@/routes/spotify/playlist.ts')`

## Description
::: warning
Due to [limitations by Spotify](https://developer.spotify.com/blog/2024-11-27-changes-to-the-web-api), this endpoint is unable to access "Algorithmic and Spotify-owned editorial playlists".
:::

## Parameters
- `id`: Playlist ID


## Features
- `requireConfig`: [{"description": "", "name": "SPOTIFY_CLIENT_ID"}, {"description": "", "name": "SPOTIFY_CLIENT_SECRET"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `open.spotify.com/playlist/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "::: warning\nDue to [limitations by Spotify](https://developer.spotify.com/blog/2024-11-27-changes-to-the-web-api), this endpoint is unable to access \"Algorithmic and Spotify-owned editorial playlists\".\n:::",
  "example": "/spotify/playlist/4UBVy1LttvodwivPUuwJk2",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "SPOTIFY_CLIENT_ID"
      },
      {
        "description": "",
        "name": "SPOTIFY_CLIENT_SECRET"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "playlist.ts",
  "maintainers": [
    "outloudvi"
  ],
  "module": "() => import('@/routes/spotify/playlist.ts')",
  "name": "Playlist",
  "parameters": {
    "id": "Playlist ID"
  },
  "path": "/playlist/:id",
  "radar": [
    {
      "source": [
        "open.spotify.com/playlist/:id"
      ]
    }
  ],
  "view": 4
}
```
