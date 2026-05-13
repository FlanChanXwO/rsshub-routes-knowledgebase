# Fantia - User Posts

## Coverage
`index-only`

## Route
- Namespace: `fantia`
- Namespace Name: `Fantia`
- Route Path: `/user/:id`
- Route Name: `User Posts`
- Example: `/fantia/user/3498`
- URL: `fantia.jp`
- Language: `ja`
- Categories: `picture`
- Maintainers: `nczitzk`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/fantia/user.ts')`

## Description
_None_

## Parameters
- `id`: User id, can be found in user profile URL


## Features
- `requireConfig`: [{"description": "The `cookie` after login can be obtained by viewing the request header in the console, If not filled in will cause some posts that require login to read to get exceptions", "name": "FANTIA_COOKIE", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `fantia.jp/fanclubs/:id`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/fantia/user/3498",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "The `cookie` after login can be obtained by viewing the request header in the console, If not filled in will cause some posts that require login to read to get exceptions",
        "name": "FANTIA_COOKIE",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/fantia/user.ts')",
  "name": "User Posts",
  "parameters": {
    "id": "User id, can be found in user profile URL"
  },
  "path": "/user/:id",
  "radar": [
    {
      "source": [
        "fantia.jp/fanclubs/:id"
      ]
    }
  ],
  "view": 2
}
```
