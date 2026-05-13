# yande.re - Popular Recent Posts

## Coverage
`index-only`

## Route
- Namespace: `yande`
- Namespace Name: `yande.re`
- Route Path: `/post/popular_recent/:period?`
- Route Name: `Popular Recent Posts`
- Example: `/yande/post/popular_recent/1d`
- URL: `yande.re`
- Language: `en`
- Categories: `picture`
- Maintainers: `magic-akari, SettingDust, fashioncj, NekoAria`
- Source Location: `post.ts`
- Source Module: `() => import('@/routes/yande/post.ts')`

## Description
| 最近 24 小时    | 最近一周     | 最近一月    | 最近一年     |
| ------- | -------- | ------- | -------- |
| 1d | 1w | 1m | 1y |

## Parameters
- `period`: {"default": "1d", "description": "展示时间", "options": [{"label": "最近 24 小时", "value": "1d"}, {"label": "最近一周", "value": "1w"}, {"label": "最近一月", "value": "1m"}, {"label": "最近一年", "value": "1y"}]}


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `yande.re/post`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "description": "| 最近 24 小时    | 最近一周     | 最近一月    | 最近一年     |\n| ------- | -------- | ------- | -------- |\n| 1d | 1w | 1m | 1y |",
  "example": "/yande/post/popular_recent/1d",
  "features": {
    "nsfw": true
  },
  "location": "post.ts",
  "maintainers": [
    "magic-akari",
    "SettingDust",
    "fashioncj",
    "NekoAria"
  ],
  "module": "() => import('@/routes/yande/post.ts')",
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
    }
  },
  "path": "/post/popular_recent/:period?",
  "radar": [
    {
      "source": [
        "yande.re/post"
      ]
    }
  ],
  "view": 2
}
```
