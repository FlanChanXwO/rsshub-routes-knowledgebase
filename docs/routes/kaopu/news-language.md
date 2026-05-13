# 靠谱新闻 - 全部

## Coverage
`index-only`

## Route
- Namespace: `kaopu`
- Namespace Name: `靠谱新闻`
- Route Path: `/news/:language?`
- Route Name: `全部`
- Example: `/kaopu/news/zh-hans`
- URL: `kaopu.news`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `fashioncj`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/kaopu/news.ts')`

## Description
| 简体中文    | 繁体中文     |
| ------- | -------- |
| zh-hans | zh-hant |

## Parameters
- `language`: 语言


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `kaopu.news/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 简体中文    | 繁体中文     |\n| ------- | -------- |\n| zh-hans | zh-hant | ",
  "example": "/kaopu/news/zh-hans",
  "location": "news.ts",
  "maintainers": [
    "fashioncj"
  ],
  "module": "() => import('@/routes/kaopu/news.ts')",
  "name": "全部",
  "parameters": {
    "language": "语言"
  },
  "path": "/news/:language?",
  "radar": [
    {
      "source": [
        "kaopu.news/"
      ]
    }
  ]
}
```
