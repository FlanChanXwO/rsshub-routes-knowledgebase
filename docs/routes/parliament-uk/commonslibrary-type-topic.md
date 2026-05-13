# UK Parliament - Commonlibrary

## Coverage
`index-only`

## Route
- Namespace: `parliament.uk`
- Namespace Name: `UK Parliament`
- Route Path: `/commonslibrary/type/:topic?`
- Route Name: `Commonlibrary`
- Example: `/parliament.uk/commonslibrary/type/research-briefing`
- URL: `parliament.uk`
- Language: `en`
- Categories: `government`
- Maintainers: `AntiKnot`
- Source Location: `commonslibrary.ts`
- Source Module: `() => import('@/routes/parliament.uk/commonslibrary.ts')`

## Description
_None_

## Parameters
- `topic`: research by topic, string, example: [research-briefing|data-dashboard]


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
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
    "government"
  ],
  "example": "/parliament.uk/commonslibrary/type/research-briefing",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "commonslibrary.ts",
  "maintainers": [
    "AntiKnot"
  ],
  "module": "() => import('@/routes/parliament.uk/commonslibrary.ts')",
  "name": "Commonlibrary",
  "parameters": {
    "topic": "research by topic, string, example: [research-briefing|data-dashboard]"
  },
  "path": "/commonslibrary/type/:topic?"
}
```
