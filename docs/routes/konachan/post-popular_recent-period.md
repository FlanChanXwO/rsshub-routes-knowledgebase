# Konachan.com Anime Wallpapers - Popular Recent Posts

## Coverage
`index-only`

## Route
- Namespace: `konachan`
- Namespace Name: `Konachan.com Anime Wallpapers`
- Route Path: `/post/popular_recent/:period?`
- Route Name: `Popular Recent Posts`
- Example: `/konachan/post/popular_recent/1d`
- URL: `konachan.com`
- Language: `en`
- Categories: `picture`
- Maintainers: `magic-akari, NekoAria, sineeeee`
- Source Location: `post.ts`
- Source Module: `() => import('@/routes/konachan/post.ts')`

## Description
| 最近 24 小时    | 最近一周     | 最近一月    | 最近一年     |
| ------- | -------- | ------- | -------- |
| 1d | 1w | 1m | 1y |

## Parameters
- `period`: {"default": "1d", "description": "展示时间", "options": [{"label": "最近 24 小时", "value": "1d"}, {"label": "最近一周", "value": "1w"}, {"label": "最近一月", "value": "1m"}, {"label": "最近一年", "value": "1y"}]}
- `safe_search`: {"default": "false", "description": "是否使用无r18的站点konachan.net，若是,则在路径前加上 `/sfw`，如`/konachan/sfw/post/popular_recent/1d`，若否则默认使用 konachan.com"}


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `konachan.com/post`
### Rule 2
- `source`:
  - `konachan.net/post`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "description": "| 最近 24 小时    | 最近一周     | 最近一月    | 最近一年     |\n| ------- | -------- | ------- | -------- |\n| 1d | 1w | 1m | 1y |",
  "example": "/konachan/post/popular_recent/1d",
  "features": {
    "nsfw": true
  },
  "location": "post.ts",
  "maintainers": [
    "magic-akari",
    "NekoAria",
    "sineeeee"
  ],
  "module": "() => import('@/routes/konachan/post.ts')",
  "name": "Popular Recent Posts",
  "parameters": {
    "period": {
      "default": "1d",
      "description": "展示时间",
      "options": [
        {
          "label": "最近 24 小时",
          "value": "1d"
        },
        {
          "label": "最近一周",
          "value": "1w"
        },
        {
          "label": "最近一月",
          "value": "1m"
        },
        {
          "label": "最近一年",
          "value": "1y"
        }
      ]
    },
    "safe_search": {
      "default": "false",
      "description": "是否使用无r18的站点konachan.net，若是,则在路径前加上 `/sfw`，如`/konachan/sfw/post/popular_recent/1d`，若否则默认使用 konachan.com"
    }
  },
  "path": [
    "/post/popular_recent/:period?",
    "/sfw/post/popular_recent/:period?"
  ],
  "radar": [
    {
      "source": [
        "konachan.com/post"
      ]
    },
    {
      "source": [
        "konachan.net/post"
      ]
    }
  ],
  "view": 2
}
```
