# Fediverse - Timeline

## Coverage
`index-only`

## Route
- Namespace: `fediverse`
- Namespace Name: `Fediverse`
- Route Path: `/timeline/:account`
- Route Name: `Timeline`
- Example: `/fediverse/timeline/Mastodon@mastodon.social`
- URL: `fediverse.observer`
- Language: `en`
- Categories: `social-media`
- Maintainers: `DIYgod, pseudoyu`
- Source Location: `timeline.ts`
- Source Module: `() => import('@/routes/fediverse/timeline.ts')`

## Description
_None_

## Parameters
- `account`: username@domain


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
  "example": "/fediverse/timeline/Mastodon@mastodon.social",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "timeline.ts",
  "maintainers": [
    "DIYgod",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/fediverse/timeline.ts')",
  "name": "Timeline",
  "parameters": {
    "account": "username@domain"
  },
  "path": "/timeline/:account",
  "view": 1
}
```
