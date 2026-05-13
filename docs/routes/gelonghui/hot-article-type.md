# 格隆汇 - 最热文章

## Coverage
`index-only`

## Route
- Namespace: `gelonghui`
- Namespace Name: `格隆汇`
- Route Path: `/hot-article/:type?`
- Route Name: `最热文章`
- Example: `/gelonghui/hot-article`
- URL: `gelonghui.com/`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `hot-article.ts`
- Source Module: `() => import('@/routes/gelonghui/hot-article.ts')`

## Description
_None_

## Parameters
- `type`: {"description": "`day` 为日排行，`week` 为周排行，默认为 `day`", "options": [{"label": "日排行", "value": "day"}, {"label": "周排行", "value": "week"}]}


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
  - `gelonghui.com/`
- `target`: `/hot-article`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/gelonghui/hot-article",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "hot-article.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/gelonghui/hot-article.ts')",
  "name": "最热文章",
  "parameters": {
    "type": {
      "description": "`day` 为日排行，`week` 为周排行，默认为 `day`",
      "options": [
        {
          "label": "日排行",
          "value": "day"
        },
        {
          "label": "周排行",
          "value": "week"
        }
      ]
    }
  },
  "path": "/hot-article/:type?",
  "radar": [
    {
      "source": [
        "gelonghui.com/"
      ],
      "target": "/hot-article"
    }
  ],
  "url": "gelonghui.com/",
  "view": 0
}
```
