# pixiv - Keyword

## Coverage
`index-only`

## Route
- Namespace: `pixiv`
- Namespace Name: `pixiv`
- Route Path: `/search/:keyword/:order?/:mode?/:include_ai?`
- Route Name: `Keyword`
- Example: `/pixiv/search/Nezuko/popular`
- URL: `www.pixiv.net`
- Language: `ja`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `search.ts`
- Source Module: `() => import('@/routes/pixiv/search.ts')`

## Description
_None_

## Parameters
- `keyword`: keyword
- `order`: {"default": "date", "description": "rank mode, empty or other for time order, popular for popular order", "options": [{"label": "time order", "value": "date"}, {"label": "popular order", "value": "popular"}]}
- `mode`: {"default": "no", "description": "filte R18 content", "options": [{"label": "only not R18", "value": "safe"}, {"label": "only R18", "value": "r18"}, {"label": "no filter", "value": "no"}]}
- `include_ai`: {"default": "yes", "description": "whether AI-generated content is included", "options": [{"label": "does not include AI-generated content", "value": "no"}, {"label": "include AI-generated content", "value": "yes"}]}


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
    "social-media"
  ],
  "example": "/pixiv/search/Nezuko/popular",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "search.ts",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/pixiv/search.ts')",
  "name": "Keyword",
  "parameters": {
    "include_ai": {
      "default": "yes",
      "description": "whether AI-generated content is included",
      "options": [
        {
          "label": "does not include AI-generated content",
          "value": "no"
        },
        {
          "label": "include AI-generated content",
          "value": "yes"
        }
      ]
    },
    "keyword": "keyword",
    "mode": {
      "default": "no",
      "description": "filte R18 content",
      "options": [
        {
          "label": "only not R18",
          "value": "safe"
        },
        {
          "label": "only R18",
          "value": "r18"
        },
        {
          "label": "no filter",
          "value": "no"
        }
      ]
    },
    "order": {
      "default": "date",
      "description": "rank mode, empty or other for time order, popular for popular order",
      "options": [
        {
          "label": "time order",
          "value": "date"
        },
        {
          "label": "popular order",
          "value": "popular"
        }
      ]
    }
  },
  "path": "/search/:keyword/:order?/:mode?/:include_ai?",
  "view": 2
}
```
