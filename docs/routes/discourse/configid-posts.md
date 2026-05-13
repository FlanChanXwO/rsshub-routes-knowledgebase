# Discourse - Latest posts

## Coverage
`index-only`

## Route
- Namespace: `discourse`
- Namespace Name: `Discourse`
- Route Path: `/:configId/posts`
- Route Name: `Latest posts`
- Example: `/discourse/0/posts`
- URL: `_None_`
- Language: `en`
- Categories: `bbs`
- Maintainers: `dzx-dzx`
- Source Location: `posts.ts`
- Source Module: `() => import('@/routes/discourse/posts.ts')`

## Description
_None_

## Parameters
- `configId`: Environment variable configuration id, see above


## Features
- `requireConfig`: [{"description": "", "name": "DISCOURSE_CONFIG_*"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/discourse/0/posts",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "DISCOURSE_CONFIG_*"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "posts.ts",
  "maintainers": [
    "dzx-dzx"
  ],
  "module": "() => import('@/routes/discourse/posts.ts')",
  "name": "Latest posts",
  "parameters": {
    "configId": "Environment variable configuration id, see above"
  },
  "path": "/:configId/posts"
}
```
