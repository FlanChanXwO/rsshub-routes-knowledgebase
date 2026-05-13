# Followin - Topic

## Coverage
`index-only`

## Route
- Namespace: `followin`
- Namespace Name: `Followin`
- Route Path: `/topic/:topicId/:lang?`
- Route Name: `Topic`
- Example: `/followin/topic/40`
- URL: `followin.io`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `TonyRL`
- Source Location: `topic.ts`
- Source Module: `() => import('@/routes/followin/topic.ts')`

## Description
_None_

## Parameters
- `topicId`: Topic ID, can be found in URL
- `lang`: Language, see table above, `en` by default


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
  - `followin.io/:lang/topic/:topicId`
  - `followin.io/topic/:topicId`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/followin/topic/40",
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
  "module": "() => import('@/routes/followin/topic.ts')",
  "name": "Topic",
  "parameters": {
    "lang": "Language, see table above, `en` by default",
    "topicId": "Topic ID, can be found in URL"
  },
  "path": "/topic/:topicId/:lang?",
  "radar": [
    {
      "source": [
        "followin.io/:lang/topic/:topicId",
        "followin.io/topic/:topicId"
      ]
    }
  ]
}
```
