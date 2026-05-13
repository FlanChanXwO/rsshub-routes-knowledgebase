# QuestN - Community Events

## Coverage
`index-only`

## Route
- Namespace: `questn`
- Namespace Name: `QuestN`
- Route Path: `/community/:communityUrl`
- Route Name: `Community Events`
- Example: `/questn/community/gmnetwork`
- URL: `app.questn.com`
- Language: `zh-CN`
- Categories: `other`
- Maintainers: `cxheng315`
- Source Location: `community.ts`
- Source Module: `() => import('@/routes/questn/community.ts')`

## Description
_None_

## Parameters
- `community_url`: Community URL


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
  - `app.questn.com/:communityUrl`
- `target`: `/community/:communityUrl`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/questn/community/gmnetwork",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "community.ts",
  "maintainers": [
    "cxheng315"
  ],
  "module": "() => import('@/routes/questn/community.ts')",
  "name": "Community Events",
  "parameters": {
    "community_url": "Community URL"
  },
  "path": "/community/:communityUrl",
  "radar": [
    {
      "source": [
        "app.questn.com/:communityUrl"
      ],
      "target": "/community/:communityUrl"
    }
  ],
  "url": "app.questn.com"
}
```
