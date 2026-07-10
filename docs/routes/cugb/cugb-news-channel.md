# China University of Geosciences (Beijing) - 校园新闻

## Coverage
`index-only`

## Route
- Namespace: `cugb`
- Namespace Name: `China University of Geosciences (Beijing)`
- Route Path: `/cugb/news/:channel?`
- Route Name: `校园新闻`
- Example: `/cugb/news/bdxw`
- URL: `cugb.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `syncmeta`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `channel`: 栏目，默认为 `bdxw` 北地新闻


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
  - `www.cugb.edu.cn/:channel.jhtml`
- `target`: `/news/:channel`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/cugb/news/bdxw",
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
    "syncmeta"
  ],
  "name": "校园新闻",
  "parameters": {
    "channel": "栏目，默认为 `bdxw` 北地新闻"
  },
  "path": "/news/:channel?",
  "radar": [
    {
      "source": [
        "www.cugb.edu.cn/:channel.jhtml"
      ],
      "target": "/news/:channel"
    }
  ],
  "topFeeds": []
}
```
