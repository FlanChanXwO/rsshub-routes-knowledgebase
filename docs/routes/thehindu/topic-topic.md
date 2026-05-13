# The Hindu - Topic

## Coverage
`index-only`

## Route
- Namespace: `thehindu`
- Namespace Name: `The Hindu`
- Route Path: `/topic/:topic`
- Route Name: `Topic`
- Example: `/thehindu/topic/rains`
- URL: `thehindu.com`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `topic.ts`
- Source Module: `() => import('@/routes/thehindu/topic.ts')`

## Description
_None_

## Parameters
- `topic`: Topic slug, can be found in URL.


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
  - `thehindu.com/topic/:topic`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/thehindu/topic/rains",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "topic.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/thehindu/topic.ts')",
  "name": "Topic",
  "parameters": {
    "topic": "Topic slug, can be found in URL."
  },
  "path": "/topic/:topic",
  "radar": [
    {
      "source": [
        "thehindu.com/topic/:topic"
      ]
    }
  ]
}
```
