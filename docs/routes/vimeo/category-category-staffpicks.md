# Vimeo - Category

## Coverage
`index-only`

## Route
- Namespace: `vimeo`
- Namespace Name: `Vimeo`
- Route Path: `/category/:category/:staffpicks?`
- Route Name: `Category`
- Example: `/vimeo/category/documentary/staffpicks`
- URL: `vimeo.com`
- Language: `en`
- Categories: `social-media`
- Maintainers: `MisteryMonster`
- Source Location: `category.ts`
- Source Module: `() => import('@/routes/vimeo/category.ts')`

## Description
_None_

## Parameters
- `category`: Category name can get from url like `documentary` in [https://vimeo.com/categories/documentary/videos](https://vimeo.com/categories/documentary/videos)
- `staffpicks`: type `staffpicks` to sort with staffpicks


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
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
  "example": "/vimeo/category/documentary/staffpicks",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "category.ts",
  "maintainers": [
    "MisteryMonster"
  ],
  "module": "() => import('@/routes/vimeo/category.ts')",
  "name": "Category",
  "parameters": {
    "category": "Category name can get from url like `documentary` in [https://vimeo.com/categories/documentary/videos](https://vimeo.com/categories/documentary/videos) ",
    "staffpicks": "type `staffpicks` to sort with staffpicks"
  },
  "path": "/category/:category/:staffpicks?",
  "view": 3
}
```
