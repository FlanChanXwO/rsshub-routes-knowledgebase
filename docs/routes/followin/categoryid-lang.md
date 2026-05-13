# Followin - Home

## Coverage
`index-only`

## Route
- Namespace: `followin`
- Namespace Name: `Followin`
- Route Path: `/:categoryId?/:lang?`
- Route Name: `Home`
- Example: `/followin`
- URL: `followin.io`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `TonyRL`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/followin/index.ts')`

## Description
Category ID

| For You | Market | Meme | BRC20 | NFT | Thread | In-depth | Tutorials | Videos |
| ------- | ------ | ---- | ----- | --- | ------ | -------- | --------- | ------ |
| 1       | 9      | 13   | 14    | 3   | 5      | 6        | 8         | 11     |

  Language

| English | 简体中文 | 繁體中文 | Tiếng Việt |
| ------- | -------- | -------- | ---------- |
| en      | zh-Hans  | zh-Hant  | vi         |

## Parameters
- `categoryId`: {"default": "1", "description": "Category ID", "options": [{"label": "For You", "value": "1"}, {"label": "Market", "value": "9"}, {"label": "Meme", "value": "13"}, {"label": "BRC20", "value": "14"}, {"label": "NFT", "value": "3"}, {"label": "Thread", "value": "5"}, {"label": "In-depth", "value": "6"}, {"label": "Tutorials", "value": "8"}, {"label": "Videos", "value": "11"}]}
- `lang`: {"default": "en", "description": "Language", "options": [{"label": "English", "value": "en"}, {"label": "简体中文", "value": "zh-Hans"}, {"label": "繁體中文", "value": "zh-Hant"}, {"label": "Tiếng Việt", "value": "vi"}]}


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
    "finance"
  ],
  "description": "Category ID\n\n| For You | Market | Meme | BRC20 | NFT | Thread | In-depth | Tutorials | Videos |\n| ------- | ------ | ---- | ----- | --- | ------ | -------- | --------- | ------ |\n| 1       | 9      | 13   | 14    | 3   | 5      | 6        | 8         | 11     |\n\n  Language\n\n| English | 简体中文 | 繁體中文 | Tiếng Việt |\n| ------- | -------- | -------- | ---------- |\n| en      | zh-Hans  | zh-Hant  | vi         |",
  "example": "/followin",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/followin/index.ts')",
  "name": "Home",
  "parameters": {
    "categoryId": {
      "default": "1",
      "description": "Category ID",
      "options": [
        {
          "label": "For You",
          "value": "1"
        },
        {
          "label": "Market",
          "value": "9"
        },
        {
          "label": "Meme",
          "value": "13"
        },
        {
          "label": "BRC20",
          "value": "14"
        },
        {
          "label": "NFT",
          "value": "3"
        },
        {
          "label": "Thread",
          "value": "5"
        },
        {
          "label": "In-depth",
          "value": "6"
        },
        {
          "label": "Tutorials",
          "value": "8"
        },
        {
          "label": "Videos",
          "value": "11"
        }
      ]
    },
    "lang": {
      "default": "en",
      "description": "Language",
      "options": [
        {
          "label": "English",
          "value": "en"
        },
        {
          "label": "简体中文",
          "value": "zh-Hans"
        },
        {
          "label": "繁體中文",
          "value": "zh-Hant"
        },
        {
          "label": "Tiếng Việt",
          "value": "vi"
        }
      ]
    }
  },
  "path": "/:categoryId?/:lang?",
  "view": 0
}
```
