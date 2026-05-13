# The New York Times - News

## Coverage
`index-only`

## Route
- Namespace: `nytimes`
- Namespace Name: `The New York Times`
- Route Path: `/:lang?`
- Route Name: `News`
- Example: `/nytimes/dual`
- URL: `nytimes.com/`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `HenryQW, pseudoyu`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/nytimes/index.ts')`

## Description
By extracting the full text of articles, we provide a better reading experience (full text articles) over the official one.

## Parameters
- `lang`: {"description": "language, default to Chinese", "options": [{"label": "Chinese-English", "value": "dual"}, {"label": "English", "value": "en"}, {"label": "Traditional Chinese", "value": "traditionalchinese"}, {"label": "Chinese-English (Traditional Chinese)", "value": "dual-traditionalchinese"}]}


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
  - `nytimes.com/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "By extracting the full text of articles, we provide a better reading experience (full text articles) over the official one.",
  "example": "/nytimes/dual",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "HenryQW",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/nytimes/index.ts')",
  "name": "News",
  "parameters": {
    "lang": {
      "description": "language, default to Chinese",
      "options": [
        {
          "label": "Chinese-English",
          "value": "dual"
        },
        {
          "label": "English",
          "value": "en"
        },
        {
          "label": "Traditional Chinese",
          "value": "traditionalchinese"
        },
        {
          "label": "Chinese-English (Traditional Chinese)",
          "value": "dual-traditionalchinese"
        }
      ]
    }
  },
  "path": "/:lang?",
  "radar": [
    {
      "source": [
        "nytimes.com/"
      ],
      "target": ""
    }
  ],
  "url": "nytimes.com/",
  "view": 0
}
```
