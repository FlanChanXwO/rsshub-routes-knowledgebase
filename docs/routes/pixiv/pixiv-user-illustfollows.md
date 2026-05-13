# pixiv - Following timeline

## Coverage
`index-only`

## Route
- Namespace: `pixiv`
- Namespace Name: `pixiv`
- Route Path: `/pixiv/user/illustfollows`
- Route Name: `Following timeline`
- Example: `/pixiv/user/illustfollows`
- URL: `www.pixiv.net/bookmark_new_illust.php`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `ClarkeCheng`
- Source Location: `illustfollow.ts`
- Source Module: `_None_`

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
  "description": "::: warning\nOnly for self-hosted\n:::",
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
  "heat": 17,
  "location": "illustfollow.ts",
  "maintainers": [
    "ClarkeCheng"
  ],
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
  "topFeeds": [
    {
      "description": "Pixiv关注的画师们的最新作品 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60197119360862208",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.pixiv.net/bookmark_new_illust.php",
      "title": "Pixiv关注的新作品",
      "type": "feed",
      "url": "rsshub://pixiv/user/illustfollows"
    }
  ],
  "url": "www.pixiv.net/bookmark_new_illust.php"
}
```
