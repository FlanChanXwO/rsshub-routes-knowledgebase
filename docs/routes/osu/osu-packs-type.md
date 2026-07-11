# osu! - Beatmap Packs

## Coverage
`index-only`

## Route
- Namespace: `osu`
- Namespace Name: `osu!`
- Route Path: `/osu/packs/:type?`
- Route Name: `Beatmap Packs`
- Example: `/osu/packs`
- URL: `osu.ppy.sh`
- Language: `_None_`
- Categories: `game`
- Maintainers: `JimenezLi`
- Source Location: `beatmaps/packs.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: pack type, default to `standard`, can choose from `featured`, `tournament`, `loved`, `chart`, `theme` and `artist`


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
    "game"
  ],
  "example": "/osu/packs",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "beatmaps/packs.ts",
  "maintainers": [
    "JimenezLi"
  ],
  "name": "Beatmap Packs",
  "parameters": {
    "type": "pack type, default to `standard`, can choose from `featured`, `tournament`, `loved`, `chart`, `theme` and `artist`"
  },
  "path": "/packs/:type?",
  "topFeeds": [
    {
      "description": "osu! Beatmap Pack - standard - Powered by RSSHub",
      "errorAt": "2026-07-10T03:47:34.308Z",
      "errorMessage": "Failed to fetch\n",
      "id": "83063680805214208",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://osu.ppy.sh/beatmaps/packs?type=standard",
      "title": "osu! Beatmap Pack - standard",
      "type": "feed",
      "url": "rsshub://osu/packs"
    }
  ]
}
```
