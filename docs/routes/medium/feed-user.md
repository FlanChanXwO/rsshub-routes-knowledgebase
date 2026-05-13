# Medium - Medium Feed

## Coverage
`index-only`

## Route
- Namespace: `medium`
- Namespace Name: `Medium`
- Route Path: `/feed/:user`
- Route Name: `Medium Feed`
- Example: `/medium/feed/zhgchgli`
- URL: `medium.com`
- Language: `en`
- Categories: `blog`
- Maintainers: `pseudoyu`
- Source Location: `feed.ts`
- Source Module: `() => import('@/routes/medium/feed.ts')`

## Description
_None_

## Parameters
- `user`: Username of the Medium


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
  - `medium.com/@:user`
- `target`: `/feed/:user`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/medium/feed/zhgchgli",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "feed.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "module": "() => import('@/routes/medium/feed.ts')",
  "name": "Medium Feed",
  "parameters": {
    "user": "Username of the Medium"
  },
  "path": "/feed/:user",
  "radar": [
    {
      "source": [
        "medium.com/@:user"
      ],
      "target": "/feed/:user"
    }
  ],
  "view": 1
}
```
