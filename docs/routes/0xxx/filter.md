# 0xxx.ws - Source

## Coverage
`index-only`

## Route
- Namespace: `0xxx`
- Namespace Name: `0xxx.ws`
- Route Path: `/:filter?`
- Route Name: `Source`
- Example: `/0xxx/category=Movie-HD-1080p`
- URL: `0xxx.ws`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/0xxx/index.ts')`

## Description
:::tip
To subscribe to [Movie HD 1080p](https://0xxx.ws?category=Movie-HD-1080p), where the source URL is `https://0xxx.ws?category=Movie-HD-1080p`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/0xxx/category=Movie-HD-1080p`](https://rsshub.app/0xxx/category=Movie-HD-1080p).
:::

## Parameters
- `filter`: {"description": "Filter"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nfsw`: true

## Radar
### Rule 1
- `source`:
  - `0xxx.ws`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": ":::tip\nTo subscribe to [Movie HD 1080p](https://0xxx.ws?category=Movie-HD-1080p), where the source URL is `https://0xxx.ws?category=Movie-HD-1080p`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/0xxx/category=Movie-HD-1080p`](https://rsshub.app/0xxx/category=Movie-HD-1080p).\n:::\n",
  "example": "/0xxx/category=Movie-HD-1080p",
  "features": {
    "antiCrawler": false,
    "nfsw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/0xxx/index.ts')",
  "name": "Source",
  "parameters": {
    "filter": {
      "description": "Filter"
    }
  },
  "path": "/:filter?",
  "radar": [
    {
      "source": [
        "0xxx.ws"
      ]
    }
  ],
  "url": "0xxx.ws",
  "view": 0
}
```
