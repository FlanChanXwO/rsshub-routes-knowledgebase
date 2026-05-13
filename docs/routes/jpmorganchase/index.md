# JPMorgan Chase - Research Topics

## Coverage
`index-only`

## Route
- Namespace: `jpmorganchase`
- Namespace Name: `JPMorgan Chase`
- Route Path: `/`
- Route Name: `Research Topics`
- Example: `/jpmorganchase`
- URL: `www.jpmorganchase.com/institute/all-topics`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `dousha`
- Source Location: `research.ts`
- Source Module: `() => import('@/routes/jpmorganchase/research.ts')`

## Description
_None_

## Parameters
_None_


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
  - `jpmorganchase.com/institute/all-topics`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/jpmorganchase",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "research.ts",
  "maintainers": [
    "dousha"
  ],
  "module": "() => import('@/routes/jpmorganchase/research.ts')",
  "name": "Research Topics",
  "path": "/",
  "radar": [
    {
      "source": [
        "jpmorganchase.com/institute/all-topics"
      ],
      "target": "/"
    }
  ],
  "url": "www.jpmorganchase.com/institute/all-topics"
}
```
