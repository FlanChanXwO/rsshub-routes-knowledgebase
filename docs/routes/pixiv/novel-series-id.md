# pixiv - Novel Series

## Coverage
`index-only`

## Route
- Namespace: `pixiv`
- Namespace Name: `pixiv`
- Route Path: `/novel/series/:id`
- Route Name: `Novel Series`
- Example: `/pixiv/novel/series/11586857`
- URL: `www.pixiv.net`
- Language: `ja`
- Categories: `social-media`
- Maintainers: `SnowAgar25, keocheung`
- Source Location: `novel-series.ts`
- Source Module: `() => import('@/routes/pixiv/novel-series.ts')`

## Description
_None_

## Parameters
- `id`: Series id, can be found in URL


## Features
- `requireConfig`: [{"description": "\nrefresh_token after Pixiv login, required for accessing R18 novels\nPixiv 登錄後的 refresh_token，用於獲取 R18 小說\n[https://docs.rsshub.app/deploy/config#pixiv](https://docs.rsshub.app/deploy/config#pixiv)", "name": "PIXIV_REFRESHTOKEN", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `www.pixiv.net/novel/series/:id`
- `target`: `/novel/series/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/pixiv/novel/series/11586857",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "\nrefresh_token after Pixiv login, required for accessing R18 novels\nPixiv 登錄後的 refresh_token，用於獲取 R18 小說\n[https://docs.rsshub.app/deploy/config#pixiv](https://docs.rsshub.app/deploy/config#pixiv)",
        "name": "PIXIV_REFRESHTOKEN",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "novel-series.ts",
  "maintainers": [
    "SnowAgar25",
    "keocheung"
  ],
  "module": "() => import('@/routes/pixiv/novel-series.ts')",
  "name": "Novel Series",
  "parameters": {
    "id": "Series id, can be found in URL"
  },
  "path": "/novel/series/:id",
  "radar": [
    {
      "source": [
        "www.pixiv.net/novel/series/:id"
      ],
      "target": "/novel/series/:id"
    }
  ]
}
```
