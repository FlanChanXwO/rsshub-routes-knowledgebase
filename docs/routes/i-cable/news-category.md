# 有線新聞 - 新聞

## Coverage
`index-only`

## Route
- Namespace: `i-cable`
- Namespace Name: `有線新聞`
- Route Path: `/news/:category?`
- Route Name: `新聞`
- Example: `/i-cable/news`
- URL: `www.i-cable.com/`
- Language: `zh-HK`
- Categories: `traditional-media`
- Maintainers: `quiniapiezoelectricity`
- Source Location: `news.tsx`
- Source Module: `() => import('@/routes/i-cable/news.tsx')`

## Description
::: tip
分類只可用分類名稱，如：新聞資訊/港聞
:::

## Parameters
- `category`: 分類，默認為新聞資訊


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
  - `www.i-cable.com`
- `target`: `/news`
### Rule 2
- `source`:
  - `www.i-cable.com/category/:category`
- `target`: `/news/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "\n::: tip\n分類只可用分類名稱，如：新聞資訊/港聞\n:::",
  "example": "/i-cable/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.tsx",
  "maintainers": [
    "quiniapiezoelectricity"
  ],
  "module": "() => import('@/routes/i-cable/news.tsx')",
  "name": "新聞",
  "parameters": {
    "category": "分類，默認為新聞資訊"
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "www.i-cable.com"
      ],
      "target": "/news"
    },
    {
      "source": [
        "www.i-cable.com/category/:category"
      ],
      "target": "/news/:category"
    }
  ],
  "url": "www.i-cable.com/"
}
```
