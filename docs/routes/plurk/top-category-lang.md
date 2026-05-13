# Plurk - Top

## Coverage
`index-only`

## Route
- Namespace: `plurk`
- Namespace Name: `Plurk`
- Route Path: `/top/:category?/:lang?`
- Route Name: `Top`
- Example: `/plurk/top/topReplurks`
- URL: `plurk.com`
- Language: `en`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `top.ts`
- Source Module: `() => import('@/routes/plurk/top.ts')`

## Description
| Top Replurks | Top Favorites | Top Responded |
| ------------ | ------------- | ------------- |
| topReplurks  | topFavorites  | topResponded  |

| English | 中文（繁體） |
| ------- | ------------ |
| en      | zh           |

## Parameters
- `category`: Category, see the table below, `topReplurks` by default
- `lang`: Language, see the table below, `en` by default


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
  "description": "| Top Replurks | Top Favorites | Top Responded |\n| ------------ | ------------- | ------------- |\n| topReplurks  | topFavorites  | topResponded  |\n\n| English | 中文（繁體） |\n| ------- | ------------ |\n| en      | zh           |",
  "example": "/plurk/top/topReplurks",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "top.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/plurk/top.ts')",
  "name": "Top",
  "parameters": {
    "category": "Category, see the table below, `topReplurks` by default",
    "lang": "Language, see the table below, `en` by default"
  },
  "path": "/top/:category?/:lang?",
  "view": 1
}
```
