# Ganjing World - posts in a channel

## Coverage
`index-only`

## Route
- Namespace: `ganjingworld`
- Namespace Name: `Ganjing World`
- Route Path: `/channel/posts/:id`
- Route Name: `posts in a channel`
- Example: `/ganjingworld/channel/posts/1fcahpcut9t3gz4zIvYSJR7qd1cs0c`
- URL: `www.ganjingworld.com`
- Language: `en`
- Categories: `social-media`
- Maintainers: `yixiangli2001`
- Source Location: `channel/posts.ts`
- Source Module: `() => import('@/routes/ganjingworld/channel/posts.ts')`

## Description
_None_

## Parameters
- `id`: Channel ID, can be found in channel url


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
  - `ganjingworld.com`
- `target`: `/channel/posts/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/ganjingworld/channel/posts/1fcahpcut9t3gz4zIvYSJR7qd1cs0c",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "channel/posts.ts",
  "maintainers": [
    "yixiangli2001"
  ],
  "module": "() => import('@/routes/ganjingworld/channel/posts.ts')",
  "name": "posts in a channel",
  "parameters": {
    "id": "Channel ID, can be found in channel url"
  },
  "path": "/channel/posts/:id",
  "radar": [
    {
      "source": [
        "ganjingworld.com"
      ],
      "target": "/channel/posts/:id"
    }
  ],
  "url": "www.ganjingworld.com"
}
```
