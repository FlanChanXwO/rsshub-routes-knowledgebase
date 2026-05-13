# Mastodon - Instance timeline (federated)

## Coverage
`index-only`

## Route
- Namespace: `mastodon`
- Namespace Name: `Mastodon`
- Route Path: `/remote/:site/:only_media?`
- Route Name: `Instance timeline (federated)`
- Example: `/mastodon/remote/pawoo.net/true`
- URL: `mastodon.social`
- Language: `en`
- Categories: `social-media`
- Maintainers: `hoilc`
- Source Location: `timeline-remote.ts`
- Source Module: `() => import('@/routes/mastodon/timeline-remote.ts')`

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
  "example": "/mastodon/remote/pawoo.net/true",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "timeline-remote.ts",
  "maintainers": [
    "hoilc"
  ],
  "module": "() => import('@/routes/mastodon/timeline-remote.ts')",
  "name": "Instance timeline (federated)",
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
  "path": "/remote/:site/:only_media?",
  "view": 1
}
```
