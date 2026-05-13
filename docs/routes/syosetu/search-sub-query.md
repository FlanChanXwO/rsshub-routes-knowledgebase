# Syosetu - Search

## Coverage
`index-only`

## Route
- Namespace: `syosetu`
- Namespace Name: `Syosetu`
- Route Path: `/search/:sub/:query`
- Route Name: `Search`
- Example: `/syosetu/search/noc/word=ハーレム&notword=&type=r&mintime=&maxtime=&minlen=30000&maxlen=&min_globalpoint=&max_globalpoint=&minlastup=&maxlastup=&minfirstup=&maxfirstup=&isgl=1&notbl=1&order=new?limit=5`
- URL: `syosetu.com`
- Language: `ja`
- Categories: `reading`
- Maintainers: `SnowAgar25`
- Source Location: `search.ts`
- Source Module: `() => import('@/routes/syosetu/search.ts')`

## Description
_None_

## Parameters
- `sub`: {"description": "The target Syosetu subsite.", "options": [{"label": "小説を読もう", "value": "yomou"}, {"label": "ノクターン", "value": "noc"}, {"label": "ムーンライト", "value": "mnlt"}, {"label": "ミッドナイト", "value": "mid"}]}
- `query`: Search parameters in Syosetu format.


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/syosetu/search/noc/word=ハーレム&notword=&type=r&mintime=&maxtime=&minlen=30000&maxlen=&min_globalpoint=&max_globalpoint=&minlastup=&maxlastup=&minfirstup=&maxfirstup=&isgl=1&notbl=1&order=new?limit=5",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "search.ts",
  "maintainers": [
    "SnowAgar25"
  ],
  "module": "() => import('@/routes/syosetu/search.ts')",
  "name": "Search",
  "parameters": {
    "query": "Search parameters in Syosetu format.",
    "sub": {
      "description": "The target Syosetu subsite.",
      "options": [
        {
          "label": "小説を読もう",
          "value": "yomou"
        },
        {
          "label": "ノクターン",
          "value": "noc"
        },
        {
          "label": "ムーンライト",
          "value": "mnlt"
        },
        {
          "label": "ミッドナイト",
          "value": "mid"
        }
      ]
    }
  },
  "path": "/search/:sub/:query"
}
```
