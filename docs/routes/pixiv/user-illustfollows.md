# pixiv - Following timeline

## Coverage
`index-only`

## Route
- Namespace: `pixiv`
- Namespace Name: `pixiv`
- Route Path: `/user/illustfollows`
- Route Name: `Following timeline`
- Example: `/pixiv/user/illustfollows`
- URL: `www.pixiv.net/bookmark_new_illust.php`
- Language: `ja`
- Categories: `social-media`
- Maintainers: `ClarkeCheng`
- Source Location: `illustfollow.ts`
- Source Module: `() => import('@/routes/pixiv/illustfollow.ts')`

## Description
::: warning
  Only for self-hosted
:::

## Parameters
_None_


## Features
- `requireConfig`: [{"description": "", "name": "PIXIV_REFRESHTOKEN"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `www.pixiv.net/bookmark_new_illust.php`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "::: warning\n  Only for self-hosted\n:::",
  "example": "/pixiv/user/illustfollows",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "",
        "name": "PIXIV_REFRESHTOKEN"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "illustfollow.ts",
  "maintainers": [
    "ClarkeCheng"
  ],
  "module": "() => import('@/routes/pixiv/illustfollow.ts')",
  "name": "Following timeline",
  "parameters": {},
  "path": "/user/illustfollows",
  "radar": [
    {
      "source": [
        "www.pixiv.net/bookmark_new_illust.php"
      ]
    }
  ],
  "url": "www.pixiv.net/bookmark_new_illust.php"
}
```
