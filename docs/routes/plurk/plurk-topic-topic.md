# Plurk - Topic

## Coverage
`index-only`

## Route
- Namespace: `plurk`
- Namespace Name: `Plurk`
- Route Path: `/plurk/topic/:topic`
- Route Name: `Topic`
- Example: `/plurk/topic/standwithukraine`
- URL: `plurk.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `topic.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `topic`: Topic ID, can be found in URL


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
  - `plurk.com/topic/:topic`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/plurk/topic/standwithukraine",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "topic.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Topic",
  "parameters": {
    "topic": "Topic ID, can be found in URL"
  },
  "path": "/topic/:topic",
  "radar": [
    {
      "source": [
        "plurk.com/topic/:topic"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "view": 1
}
```
