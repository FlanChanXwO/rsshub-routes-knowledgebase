# hotukdeals - thread

## Coverage
`index-only`

## Route
- Namespace: `hotukdeals`
- Namespace Name: `hotukdeals`
- Route Path: `/:type`
- Route Name: `thread`
- Example: `/hotukdeals/hot`
- URL: `www.hotukdeals.com`
- Language: `en`
- Categories: `shopping`
- Maintainers: `DIYgod`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/hotukdeals/index.ts')`

## Description
_None_

## Parameters
- `type`: should be one of highlights, hot, new, discussed


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/hotukdeals/hot",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/hotukdeals/index.ts')",
  "name": "thread",
  "parameters": {
    "type": "should be one of highlights, hot, new, discussed"
  },
  "path": "/:type"
}
```
