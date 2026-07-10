# Hong Kong Independent Commission Against Corruption 香港廉政公署 - Press Releases

## Coverage
`index-only`

## Route
- Namespace: `icac`
- Namespace Name: `Hong Kong Independent Commission Against Corruption 香港廉政公署`
- Route Path: `/icac/news/:lang?`
- Route Name: `Press Releases`
- Example: `/icac/news/sc`
- URL: `icac.org.hk`
- Language: `_None_`
- Categories: `government`
- Maintainers: `linbuxiao, TonyRL`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `lang`: Language, default to `sc`. Supprot `en`(English), `sc`(Simplified Chinese) and `tc`(Traditional Chinese)


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
  - `icac.org.hk/:lang/press/index.html`
- `target`: `/news/:lang`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/icac/news/sc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "linbuxiao, TonyRL"
  ],
  "name": "Press Releases",
  "parameters": {
    "lang": "Language, default to `sc`. Supprot `en`(English), `sc`(Simplified Chinese) and `tc`(Traditional Chinese)"
  },
  "path": "/news/:lang?",
  "radar": [
    {
      "source": [
        "icac.org.hk/:lang/press/index.html"
      ],
      "target": "/news/:lang"
    }
  ],
  "topFeeds": []
}
```
