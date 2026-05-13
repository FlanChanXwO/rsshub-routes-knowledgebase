# 共同网 - 最新报道

## Coverage
`index-only`

## Route
- Namespace: `kyodonews`
- Namespace Name: `共同网`
- Route Path: `/:language?/:keyword?`
- Route Name: `最新报道`
- Example: `/kyodonews`
- URL: `china.kyodonews.net`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `Rongronggg9`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/kyodonews/index.tsx')`

## Description
`keyword` 为关键词，由于共同网有许多关键词并不在主页列出，此处不一一列举，可从关键词页的 URL 的最后一级路径中提取。如 `日中关系` 的关键词页 URL 为 `https://china.kyodonews.net/news/japan-china_relationship`, 则将 `japan-china_relationship` 填入 `keyword`。特别地，当填入 `rss` 时，将从共同网官方 RSS 中抓取文章；略去时，将从首页抓取最新报道 (注意：首页更新可能比官方 RSS 稍慢)。

## Parameters
- `language`: 语言: `china` = 简体中文 (默认), `tchina` = 繁體中文
- `keyword`: 关键词


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
  - `china.kyodonews.net/news/:keyword`
  - `china.kyodonews.net/`
- `target`: `/china/:keyword?`
### Rule 2
- `source`:
  - `tchina.kyodonews.net/news/:keyword`
  - `tchina.kyodonews.net/`
- `target`: `/tchina/:keyword?`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "`keyword` 为关键词，由于共同网有许多关键词并不在主页列出，此处不一一列举，可从关键词页的 URL 的最后一级路径中提取。如 `日中关系` 的关键词页 URL 为 `https://china.kyodonews.net/news/japan-china_relationship`, 则将 `japan-china_relationship` 填入 `keyword`。特别地，当填入 `rss` 时，将从共同网官方 RSS 中抓取文章；略去时，将从首页抓取最新报道 (注意：首页更新可能比官方 RSS 稍慢)。",
  "example": "/kyodonews",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.tsx",
  "maintainers": [
    "Rongronggg9"
  ],
  "module": "() => import('@/routes/kyodonews/index.tsx')",
  "name": "最新报道",
  "parameters": {
    "keyword": "关键词",
    "language": "语言: `china` = 简体中文 (默认), `tchina` = 繁體中文"
  },
  "path": "/:language?/:keyword?",
  "radar": [
    {
      "source": [
        "china.kyodonews.net/news/:keyword",
        "china.kyodonews.net/"
      ],
      "target": "/china/:keyword?"
    },
    {
      "source": [
        "tchina.kyodonews.net/news/:keyword",
        "tchina.kyodonews.net/"
      ],
      "target": "/tchina/:keyword?"
    }
  ]
}
```
