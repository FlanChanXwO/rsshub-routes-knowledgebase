# jable - Jable 搜索结果

## Coverage
`index-only`

## Route
- Namespace: `jable`
- Namespace Name: `jable`
- Route Path: `/search/:query`
- Route Name: `Jable 搜索结果`
- Example: `/jable/search/みなみ羽琉`
- URL: `jable.tv`
- Language: `zh`
- Categories: `multimedia`
- Maintainers: `eve2ptp`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/jable/index.ts')`

## Description
_None_

## Parameters
- `query`: Search keyword


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `jable.tv/search/:query`
- `target`: `/search/:query`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/jable/search/みなみ羽琉",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "eve2ptp"
  ],
  "module": "() => import('@/routes/jable/index.ts')",
  "name": "Jable 搜索结果",
  "parameters": {
    "query": "Search keyword"
  },
  "path": "/search/:query",
  "radar": [
    {
      "source": [
        "jable.tv/search/:query"
      ],
      "target": "/search/:query"
    }
  ]
}
```
