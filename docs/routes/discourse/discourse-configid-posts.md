# Discourse - Latest posts

## Coverage
`index-only`

## Route
- Namespace: `discourse`
- Namespace Name: `Discourse`
- Route Path: `/discourse/:configId/posts`
- Route Name: `Latest posts`
- Example: `/discourse/0/posts`
- URL: `_None_`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `dzx-dzx`
- Source Location: `posts.ts`
- Source Module: `_None_`

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
  "heat": 3,
  "location": "posts.ts",
  "maintainers": [
    "dzx-dzx"
  ],
  "name": "Latest posts",
  "parameters": {
    "configId": "Environment variable configuration id, see above"
  },
  "path": "/:configId/posts",
  "topFeeds": [
    {
      "description": "最新帖子 - Powered by RSSHub",
      "errorAt": "2025-10-29T12:54:59.042Z",
      "errorMessage": "Discourse RSS is disabled due to the lack of <a href=\"https://docs.rsshub.app/deploy/\">relevant config</a>\n",
      "id": "98662879421514752",
      "image": null,
      "ownerUserId": "98535511703575552",
      "siteUrl": "https://shuzimumin.com/",
      "title": "数字牧民 - 最新帖子",
      "type": "feed",
      "url": "rsshub://discourse/0/posts"
    }
  ]
}
```
