# Bluesky (bsky) - Feeds

## Coverage
`index-only`

## Route
- Namespace: `bsky`
- Namespace Name: `Bluesky (bsky)`
- Route Path: `/profile/:handle/feed/:space/:routeParams?`
- Route Name: `Feeds`
- Example: `/bsky.app/profile/jaz.bsky.social/feed/cv:cat`
- URL: `bsky.app`
- Language: `en`
- Categories: `social-media`
- Maintainers: `FerrisChi`
- Source Location: `feeds.ts`
- Source Module: `() => import('@/routes/bsky/feeds.ts')`

## Description
_None_

## Parameters
- `handle`: User handle, can be found in URL
- `space`: Space ID, can be found in URL


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
  "example": "/bsky.app/profile/jaz.bsky.social/feed/cv:cat",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "feeds.ts",
  "maintainers": [
    "FerrisChi"
  ],
  "module": "() => import('@/routes/bsky/feeds.ts')",
  "name": "Feeds",
  "parameters": {
    "handle": "User handle, can be found in URL",
    "space": "Space ID, can be found in URL"
  },
  "path": "/profile/:handle/feed/:space/:routeParams?",
  "view": 1
}
```
