# Instagram - User Profile / Hashtag

## Coverage
`index-only`

## Route
- Namespace: `instagram`
- Namespace Name: `Instagram`
- Route Path: `/2/:category/:key`
- Route Name: `User Profile / Hashtag`
- Example: `/instagram/2/user/stefaniejoosten`
- URL: `www.instagram.com`
- Language: `en`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `web-api/index.ts`
- Source Module: `() => import('@/routes/instagram/web-api/index.ts')`

## Description
::: tip
You may need to setup cookie for a less restrictive rate limit and private profiles.
:::


| User timeline | Hashtag |
| ------------- | ------- |
| user          | tags    |

## Parameters
- `category`: Feed category, see table below
- `key`: Username / Hashtag name


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
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
  "description": "::: tip\nYou may need to setup cookie for a less restrictive rate limit and private profiles.\n:::\n\n\n| User timeline | Hashtag |\n| ------------- | ------- |\n| user          | tags    |",
  "example": "/instagram/2/user/stefaniejoosten",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "web-api/index.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/instagram/web-api/index.ts')",
  "name": "User Profile / Hashtag",
  "parameters": {
    "category": "Feed category, see table below",
    "key": "Username / Hashtag name"
  },
  "path": "/2/:category/:key"
}
```
