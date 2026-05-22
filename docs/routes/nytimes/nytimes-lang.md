# The New York Times - News

## Coverage
`index-only`

## Route
- Namespace: `nytimes`
- Namespace Name: `The New York Times`
- Route Path: `/nytimes/:lang?`
- Route Name: `News`
- Example: `/nytimes/dual`
- URL: `nytimes.com/`
- Language: `_None_`
- Categories: `traditional-media, popular`
- Maintainers: `HenryQW, pseudoyu`
- Source Location: `index.ts`
- Source Module: `_None_`

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
    "traditional-media",
    "popular"
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
  "heat": 8103,
  "location": "index.ts",
  "maintainers": [
    "HenryQW",
    "pseudoyu"
  ],
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
  "topFeeds": [
    {
      "description": "纽约时报中文网 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41443203209057308",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cn.nytimes.com/",
      "title": "纽约时报中文网",
      "type": "feed",
      "url": "rsshub://nytimes"
    },
    {
      "description": "纽约时报中文网 - 中英对照版 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41572238273905693",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cn.nytimes.com/",
      "title": "纽约时报中文网 - 中英对照版",
      "type": "feed",
      "url": "rsshub://nytimes/dual"
    }
  ],
  "url": "nytimes.com/",
  "view": 0
}
```
