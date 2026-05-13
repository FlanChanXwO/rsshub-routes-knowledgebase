# 中天新聞網 - 話題

## Coverage
`index-only`

## Route
- Namespace: `ctinews`
- Namespace Name: `中天新聞網`
- Route Path: `/topic/:topic?`
- Route Name: `話題`
- Example: `/ctinews/topic/KDdek5vgXx`
- URL: `ctinews.com`
- Language: `zh-TW`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `topic.ts`
- Source Module: `() => import('@/routes/ctinews/topic.ts')`

## Description
_None_

## Parameters
- `topic`: 話題 ID，可在 URL 中獲取，留空為 `KDdek5vgXx`


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
  - `ctinews.com/news/topics/:topic`
  - `ctinews.com`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/ctinews/topic/KDdek5vgXx",
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
  "module": "() => import('@/routes/ctinews/topic.ts')",
  "name": "話題",
  "parameters": {
    "topic": "話題 ID，可在 URL 中獲取，留空為 `KDdek5vgXx`"
  },
  "path": "/topic/:topic?",
  "radar": [
    {
      "source": [
        "ctinews.com/news/topics/:topic",
        "ctinews.com"
      ]
    }
  ],
  "url": "ctinews.com"
}
```
