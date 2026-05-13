# Followin - News

## Coverage
`index-only`

## Route
- Namespace: `followin`
- Namespace Name: `Followin`
- Route Path: `/news/:lang?`
- Route Name: `News`
- Example: `/followin/news`
- URL: `followin.io`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `TonyRL`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/followin/news.ts')`

## Description
_None_

## Parameters
- `lang`: {"default": "en", "description": "Language", "options": [{"label": "English", "value": "en"}, {"label": "简体中文", "value": "zh-Hans"}, {"label": "繁體中文", "value": "zh-Hant"}, {"label": "Tiếng Việt", "value": "vi"}]}


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
  - `followin.io/:lang?/news`
  - `followin.io/news`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/followin/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/followin/news.ts')",
  "name": "News",
  "parameters": {
    "lang": {
      "default": "en",
      "description": "Language",
      "options": [
        {
          "label": "English",
          "value": "en"
        },
        {
          "label": "简体中文",
          "value": "zh-Hans"
        },
        {
          "label": "繁體中文",
          "value": "zh-Hant"
        },
        {
          "label": "Tiếng Việt",
          "value": "vi"
        }
      ]
    }
  },
  "path": "/news/:lang?",
  "radar": [
    {
      "source": [
        "followin.io/:lang?/news",
        "followin.io/news"
      ]
    }
  ],
  "view": 0
}
```
