# Odaily 星球日报 - 用户文章

## Coverage
`index-only`

## Route
- Namespace: `odaily`
- Namespace Name: `Odaily 星球日报`
- Route Path: `/odaily/user/:id`
- Route Name: `用户文章`
- Example: `/odaily/user/2147486902`
- URL: `odaily.news`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 用户 id，可在用户页地址栏中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `0daily.com/user/:id`
  - `0daily.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/odaily/user/2147486902",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "user.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "用户文章",
  "parameters": {
    "id": "用户 id，可在用户页地址栏中找到"
  },
  "path": "/user/:id",
  "radar": [
    {
      "source": [
        "0daily.com/user/:id",
        "0daily.com/"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "- Odaily星球日报 - Powered by RSSHub",
      "errorAt": "2025-07-24T19:02:43.242Z",
      "errorMessage": "Cannot read properties of undefined (reading 'items')\n",
      "id": "130082513246536704",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.odaily.news/user/2147486902",
      "title": "- Odaily星球日报",
      "type": "feed",
      "url": "rsshub://odaily/user/2147486902"
    }
  ]
}
```
