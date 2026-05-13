# pixiv - User Bookmark

## Coverage
`index-only`

## Route
- Namespace: `pixiv`
- Namespace Name: `pixiv`
- Route Path: `/user/bookmarks/:id`
- Route Name: `User Bookmark`
- Example: `/pixiv/user/bookmarks/15288095`
- URL: `www.pixiv.net`
- Language: `ja`
- Categories: `social-media`
- Maintainers: `EYHN`
- Source Location: `bookmarks.ts`
- Source Module: `() => import('@/routes/pixiv/bookmarks.ts')`

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
  - `www.pixiv.net/users/:id/bookmarks/artworks`
  - `www.pixiv.net/en/users/:id/bookmarks/artworks`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/pixiv/user/bookmarks/15288095",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "bookmarks.ts",
  "maintainers": [
    "EYHN"
  ],
  "module": "() => import('@/routes/pixiv/bookmarks.ts')",
  "name": "User Bookmark",
  "parameters": {
    "id": "user id, available in user's homepage URL"
  },
  "path": "/user/bookmarks/:id",
  "radar": [
    {
      "source": [
        "www.pixiv.net/users/:id/bookmarks/artworks",
        "www.pixiv.net/en/users/:id/bookmarks/artworks"
      ]
    }
  ]
}
```
