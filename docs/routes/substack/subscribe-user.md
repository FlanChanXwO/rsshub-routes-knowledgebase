# Substack - Substack Subscription

## Coverage
`index-only`

## Route
- Namespace: `substack`
- Namespace Name: `Substack`
- Route Path: `/subscribe/:user`
- Route Name: `Substack Subscription`
- Example: `/substack/subscribe/mangoread`
- URL: `substack.com`
- Language: `en`
- Categories: `blog`
- Maintainers: `pseudoyu`
- Source Location: `subscribe.ts`
- Source Module: `() => import('@/routes/substack/subscribe.ts')`

## Description
_None_

## Parameters
- `user`: Username of the Substack


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
    "blog"
  ],
  "example": "/substack/subscribe/mangoread",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "subscribe.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "module": "() => import('@/routes/substack/subscribe.ts')",
  "name": "Substack Subscription",
  "parameters": {
    "user": "Username of the Substack"
  },
  "path": "/subscribe/:user",
  "view": 1
}
```
