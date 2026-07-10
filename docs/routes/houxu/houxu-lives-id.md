# 后续 - Live

## Coverage
`index-only`

## Route
- Namespace: `houxu`
- Namespace Name: `后续`
- Route Path: `/houxu/lives/:id`
- Route Name: `Live`
- Example: `/houxu/lives/33899`
- URL: `houxu.app/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `lives.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 编号，可在对应 Live 页面的 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `houxu.app/lives/:id`
  - `houxu.app/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/houxu/lives/33899",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "lives.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Live",
  "parameters": {
    "id": "编号，可在对应 Live 页面的 URL 中找到"
  },
  "path": "/lives/:id",
  "radar": [
    {
      "source": [
        "houxu.app/lives/:id",
        "houxu.app/"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-07-10T10:22:36.164Z",
      "errorMessage": "[GET] \"https://houxu.app/api/1/lives/new/threads?limit=500\": 404 Not Found\n",
      "id": "166042410908812294",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://houxu/lives/new"
    }
  ],
  "url": "houxu.app/"
}
```
