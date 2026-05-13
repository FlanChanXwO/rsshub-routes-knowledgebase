# 后续 - Live

## Coverage
`index-only`

## Route
- Namespace: `houxu`
- Namespace Name: `后续`
- Route Path: `/lives/:id`
- Route Name: `Live`
- Example: `/houxu/lives/33899`
- URL: `houxu.app/`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `lives.ts`
- Source Module: `() => import('@/routes/houxu/lives.ts')`

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
  "location": "lives.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/houxu/lives.ts')",
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
  "url": "houxu.app/"
}
```
