# iThome 台灣 - 专题

## Coverage
`index-only`

## Route
- Namespace: `ithome`
- Namespace Name: `iThome 台灣`
- Route Path: `/zt/:id?`
- Route Name: `专题`
- Example: `/ithome/zt/xijiayi`
- URL: `ithome.com`
- Language: `zh-TW`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `zt.tsx`
- Source Module: `() => import('@/routes/ithome/zt.tsx')`

## Description
::: tip
  更多专题请见 [IT之家专题](https://www.ithome.com/zt)
:::

## Parameters
- `category`: 专题 id，默认为 xijiayi，即 [喜加一](https://www.ithome.com/zt/xijiayi)，可在对应专题页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `ithome.com/zt/:id`
- `target`: `/zt/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n  更多专题请见 [IT之家专题](https://www.ithome.com/zt)\n:::",
  "example": "/ithome/zt/xijiayi",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "zt.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/ithome/zt.tsx')",
  "name": "专题",
  "parameters": {
    "category": "专题 id，默认为 xijiayi，即 [喜加一](https://www.ithome.com/zt/xijiayi)，可在对应专题页 URL 中找到"
  },
  "path": "/zt/:id?",
  "radar": [
    {
      "source": [
        "ithome.com/zt/:id"
      ],
      "target": "/zt/:id"
    }
  ],
  "url": "ithome.com"
}
```
