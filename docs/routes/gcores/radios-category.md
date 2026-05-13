# 机核网 - 播客

## Coverage
`index-only`

## Route
- Namespace: `gcores`
- Namespace Name: `机核网`
- Route Path: `/radios/:category?`
- Route Name: `播客`
- Example: `/gcores/radios/45`
- URL: `gcores.com/radios`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `eternasuno`
- Source Location: `radio.tsx`
- Source Module: `() => import('@/routes/gcores/radio.tsx')`

## Description
_None_

## Parameters
- `category`: 分类名，默认为全部，可在分类页面的 URL 中找到，如 Gadio News -- 45


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `gcores.com/categories/:category`
- `target`: `/radios/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/gcores/radios/45",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "location": "radio.tsx",
  "maintainers": [
    "eternasuno"
  ],
  "module": "() => import('@/routes/gcores/radio.tsx')",
  "name": "播客",
  "parameters": {
    "category": "分类名，默认为全部，可在分类页面的 URL 中找到，如 Gadio News -- 45"
  },
  "path": "/radios/:category?",
  "radar": [
    {
      "source": [
        "gcores.com/categories/:category"
      ],
      "target": "/radios/:category"
    }
  ],
  "url": "gcores.com/radios"
}
```
