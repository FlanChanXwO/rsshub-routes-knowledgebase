# SoundOn - Podcast

## Coverage
`index-only`

## Route
- Namespace: `soundon`
- Namespace Name: `SoundOn`
- Route Path: `/p/:id`
- Route Name: `Podcast`
- Example: `/soundon/p/33a68cdc-18ad-4192-84cc-22bd7fdc6a31`
- URL: `player.soundon.fm`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `TonyRL`
- Source Location: `podcast.ts`
- Source Module: `() => import('@/routes/soundon/podcast.ts')`

## Description
_None_

## Parameters
- `id`: Podcast ID


## Features
- `supportPodcast`: true

## Radar
### Rule 1
- `source`:
  - `player.soundon.fm/p/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/soundon/p/33a68cdc-18ad-4192-84cc-22bd7fdc6a31",
  "features": {
    "supportPodcast": true
  },
  "location": "podcast.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/soundon/podcast.ts')",
  "name": "Podcast",
  "parameters": {
    "id": "Podcast ID"
  },
  "path": "/p/:id",
  "radar": [
    {
      "source": [
        "player.soundon.fm/p/:id"
      ]
    }
  ],
  "view": 4
}
```
