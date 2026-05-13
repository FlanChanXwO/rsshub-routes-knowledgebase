# Mastodon - Instance timeline (local)

## Coverage
`index-only`

## Route
- Namespace: `mastodon`
- Namespace Name: `Mastodon`
- Route Path: `/timeline/:site/:only_media?`
- Route Name: `Instance timeline (local)`
- Example: `/mastodon/timeline/pawoo.net/true`
- URL: `mastodon.social`
- Language: `en`
- Categories: `social-media`
- Maintainers: `hoilc`
- Source Location: `timeline-local.ts`
- Source Module: `() => import('@/routes/mastodon/timeline-local.ts')`

## Description
If the instance address is not `mastodon.social` or `pawoo.net`, then the route requires `ALLOW_USER_SUPPLY_UNSAFE_DOMAIN` to be `true`.

## Parameters
- `site`: instance address, only domain, no `http://` or `https://` protocol header
- `only_media`: {"default": "false", "description": "whether only display media content, default to false, any value to true", "options": [{"label": "true", "value": "true"}, {"label": "false", "value": "false"}]}


## Features
- `requireConfig`: false
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
    "social-media"
  ],
  "description": "If the instance address is not `mastodon.social` or `pawoo.net`, then the route requires `ALLOW_USER_SUPPLY_UNSAFE_DOMAIN` to be `true`.",
  "example": "/mastodon/timeline/pawoo.net/true",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "timeline-local.ts",
  "maintainers": [
    "hoilc"
  ],
  "module": "() => import('@/routes/mastodon/timeline-local.ts')",
  "name": "Instance timeline (local)",
  "parameters": {
    "only_media": {
      "default": "false",
      "description": "whether only display media content, default to false, any value to true",
      "options": [
        {
          "label": "true",
          "value": "true"
        },
        {
          "label": "false",
          "value": "false"
        }
      ]
    },
    "site": "instance address, only domain, no `http://` or `https://` protocol header"
  },
  "path": "/timeline/:site/:only_media?",
  "view": 1
}
```
