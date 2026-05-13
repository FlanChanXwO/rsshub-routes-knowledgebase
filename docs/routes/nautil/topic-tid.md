# Nautilus - Topics

## Coverage
`index-only`

## Route
- Namespace: `nautil`
- Namespace Name: `Nautilus`
- Route Path: `/topic/:tid`
- Route Name: `Topics`
- Example: `/nautil/topic/arts`
- URL: `nautil.us`
- Language: `en`
- Categories: `new-media`
- Maintainers: `emdoe`
- Source Location: `topics.tsx`
- Source Module: `() => import('@/routes/nautil/topics.tsx')`

## Description
This route provides a flexible plan with full text content to subscribe specific topic(s) on the Nautilus. Please visit [nautil.us](https://nautil.us) and click `Topics` to acquire whole topic list.

## Parameters
- `tid`: topic


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
  - `nautil.us/topics/:tid`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "This route provides a flexible plan with full text content to subscribe specific topic(s) on the Nautilus. Please visit [nautil.us](https://nautil.us) and click `Topics` to acquire whole topic list.",
  "example": "/nautil/topic/arts",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "topics.tsx",
  "maintainers": [
    "emdoe"
  ],
  "module": "() => import('@/routes/nautil/topics.tsx')",
  "name": "Topics",
  "parameters": {
    "tid": "topic"
  },
  "path": "/topic/:tid",
  "radar": [
    {
      "source": [
        "nautil.us/topics/:tid"
      ]
    }
  ]
}
```
