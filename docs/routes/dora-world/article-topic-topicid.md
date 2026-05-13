# Doraemon Channel - Article

## Coverage
`index-only`

## Route
- Namespace: `dora-world`
- Namespace Name: `Doraemon Channel`
- Route Path: `/article/:topic/:topicId?`
- Route Name: `Article`
- Example: `/dora-world/article/contents`
- URL: `www.dora-world.com`
- Language: `en`
- Categories: `anime`
- Maintainers: `AChangAZha`
- Source Location: `article.ts`
- Source Module: `() => import('@/routes/dora-world/article.ts')`

## Description
_None_

## Parameters
- `topic`: Topic name, can be found in URL. For example: the topic name of [https://www.dora-world.com/movie](https://www.dora-world.com/movie) is `movie`
- `topicId`: Topic id, can be found in URL. For example: the topic id of [https://www.dora-world.com/contents?t=197](https://www.dora-world.com/contents?t=197) is `197`


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
  - `www.dora-world.com/:topic`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/dora-world/article/contents",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "article.ts",
  "maintainers": [
    "AChangAZha"
  ],
  "module": "() => import('@/routes/dora-world/article.ts')",
  "name": "Article",
  "parameters": {
    "topic": "Topic name, can be found in URL. For example: the topic name of [https://www.dora-world.com/movie](https://www.dora-world.com/movie) is `movie`",
    "topicId": "Topic id, can be found in URL. For example: the topic id of [https://www.dora-world.com/contents?t=197](https://www.dora-world.com/contents?t=197) is `197`"
  },
  "path": "/article/:topic/:topicId?",
  "radar": [
    {
      "source": [
        "www.dora-world.com/:topic"
      ]
    }
  ],
  "view": 0
}
```
