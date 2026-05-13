# PornHub - Category

## Coverage
`index-only`

## Route
- Namespace: `pornhub`
- Namespace Name: `PornHub`
- Route Path: `/category/:caty/:img?`
- Route Name: `Category`
- Example: `/pornhub/category/popular-with-women`
- URL: `pornhub.com`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `category.ts`
- Source Module: `() => import('@/routes/pornhub/category.ts')`

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
    "multimedia"
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
  "location": "category.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/pornhub/category.ts')",
  "name": "Category",
  "parameters": {
    "caty": "category, see [categories](https://www.pornhub.com/webmasters/categories)",
    "img": "show images, set to `img=1` to enable"
  },
  "path": "/category/:caty/:img?",
  "view": 3
}
```
