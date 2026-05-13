# Corona Virus Disease 2019 - Topics

## Coverage
`index-only`

## Route
- Namespace: `scmp`
- Namespace Name: `Corona Virus Disease 2019`
- Route Path: `/topics/:topic`
- Route Name: `Topics`
- Example: `/scmp/topics/coronavirus-pandemic-all-stories`
- URL: `scmp.com`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `topic.ts`
- Source Module: `() => import('@/routes/scmp/topic.ts')`

## Description
_None_

## Parameters
- `topic`: Topic, can be found in URL


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
  - `scmp.com/topics/:topic`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/scmp/topics/coronavirus-pandemic-all-stories",
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
  "module": "() => import('@/routes/scmp/topic.ts')",
  "name": "Topics",
  "parameters": {
    "topic": "Topic, can be found in URL"
  },
  "path": "/topics/:topic",
  "radar": [
    {
      "source": [
        "scmp.com/topics/:topic"
      ]
    }
  ]
}
```
