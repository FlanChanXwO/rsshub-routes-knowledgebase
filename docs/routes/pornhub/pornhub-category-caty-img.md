# PornHub - Category

## Coverage
`index-only`

## Route
- Namespace: `pornhub`
- Namespace Name: `PornHub`
- Route Path: `/pornhub/category/:caty/:img?`
- Route Name: `Category`
- Example: `/pornhub/category/popular-with-women`
- URL: `pornhub.com`
- Language: `_None_`
- Categories: `multimedia, popular`
- Maintainers: `nczitzk`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `caty`: category, see [categories](https://www.pornhub.com/webmasters/categories)
- `img`: show images, set to `img=1` to enable


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia",
    "popular"
  ],
  "example": "/pornhub/category/popular-with-women",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2085,
  "location": "category.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Category",
  "parameters": {
    "caty": "category, see [categories](https://www.pornhub.com/webmasters/categories)",
    "img": "show images, set to `img=1` to enable"
  },
  "path": "/category/:caty/:img?",
  "topFeeds": [
    {
      "description": "Pornhub - chinese - Powered by RSSHub",
      "errorAt": "2026-03-14T21:31:30.822Z",
      "errorMessage": "Cannot read properties of undefined (reading 'category')\nCannot read properties of undefined (reading 'category')\n[GET] \"https://www.pornhub.com/webmasters/categories\": <no response> fetch failed\nCannot read properties of undefined (reading 'category')\nCannot read properties of undefined (reading 'category')\nCannot read properties of undefined (reading 'category')\n",
      "id": "64884606299366400",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.pornhub.com/video?c=undefined",
      "title": "Pornhub - chinese",
      "type": "feed",
      "url": "rsshub://pornhub/category/chinese"
    },
    {
      "description": "Pornhub - japanese - Powered by RSSHub",
      "errorAt": "2026-03-20T06:59:47.706Z",
      "errorMessage": "Cannot read properties of undefined (reading 'category')\nAuthentication failed. Access denied.\n/pornhub/category/japanese\nCannot read properties of undefined (reading 'category')\nCannot read properties of undefined (reading 'category')\n",
      "id": "60650857313055744",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.pornhub.com/video?c=111",
      "title": "Pornhub - japanese",
      "type": "feed",
      "url": "rsshub://pornhub/category/japanese"
    }
  ],
  "view": 3
}
```
