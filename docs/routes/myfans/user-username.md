# myfans - User Posts

## Coverage
`index-only`

## Route
- Namespace: `myfans`
- Namespace Name: `myfans`
- Route Path: `/user/:username`
- Route Name: `User Posts`
- Example: `/myfans/user/secret_japan`
- URL: `myfans.jp`
- Language: `ja`
- Categories: `multimedia`
- Maintainers: `TonyRL`
- Source Location: `post.tsx`
- Source Module: `() => import('@/routes/myfans/post.tsx')`

## Description
_None_

## Parameters
- `username`: User handle


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
  - `myfans.jp/:username`
  - `myfans.jp/:language/:username`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/myfans/user/secret_japan",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "post.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/myfans/post.tsx')",
  "name": "User Posts",
  "parameters": {
    "username": "User handle"
  },
  "path": "/user/:username",
  "radar": [
    {
      "source": [
        "myfans.jp/:username",
        "myfans.jp/:language/:username"
      ]
    }
  ]
}
```
