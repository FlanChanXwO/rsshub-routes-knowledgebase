# pixiv - User Activity

## Coverage
`index-only`

## Route
- Namespace: `pixiv`
- Namespace Name: `pixiv`
- Route Path: `/user/:id`
- Route Name: `User Activity`
- Example: `/pixiv/user/15288095`
- URL: `www.pixiv.net`
- Language: `ja`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/pixiv/user.ts')`

## Description
_None_

## Parameters
- `id`: user id, available in user's homepage URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `www.pixiv.net/users/:id`
  - `www.pixiv.net/en/users/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/pixiv/user/15288095",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user.ts",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/pixiv/user.ts')",
  "name": "User Activity",
  "parameters": {
    "id": "user id, available in user's homepage URL"
  },
  "path": "/user/:id",
  "radar": [
    {
      "source": [
        "www.pixiv.net/users/:id",
        "www.pixiv.net/en/users/:id"
      ]
    }
  ],
  "view": 2
}
```
