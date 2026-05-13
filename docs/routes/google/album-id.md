# Google - Public Albums

## Coverage
`index-only`

## Route
- Namespace: `google`
- Namespace Name: `Google`
- Route Path: `/album/:id`
- Route Name: `Public Albums`
- Example: `/google/album/msFFnAzKmQmWj76EA`
- URL: `www.google.com`
- Language: `en`
- Categories: `picture`
- Maintainers: `hoilc`
- Source Location: `album.ts`
- Source Module: `() => import('@/routes/google/album.ts')`

## Description
_None_

## Parameters
- `id`: album ID, can be found in URL, for example, `https://photos.app.goo.gl/msFFnAzKmQmWj76EA` to `msFFnAzKmQmWj76EA`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/google/album/msFFnAzKmQmWj76EA",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "album.ts",
  "maintainers": [
    "hoilc"
  ],
  "module": "() => import('@/routes/google/album.ts')",
  "name": "Public Albums",
  "parameters": {
    "id": "album ID, can be found in URL, for example, `https://photos.app.goo.gl/msFFnAzKmQmWj76EA` to `msFFnAzKmQmWj76EA`"
  },
  "path": "/album/:id"
}
```
