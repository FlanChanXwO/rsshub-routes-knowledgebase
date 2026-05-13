# FreeBuf - 文章

## Coverage
`index-only`

## Route
- Namespace: `freebuf`
- Namespace Name: `FreeBuf`
- Route Path: `/articles/:type`
- Route Name: `文章`
- Example: `/freebuf/articles/web`
- URL: `freebuf.com`
- Language: `zh-CN`
- Categories: `blog`
- Maintainers: `trganda`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/freebuf/index.ts')`

## Description
::: tip
  Freebuf 的文章页面带有反爬虫机制，所以目前无法获取文章的完整内容。
:::

## Parameters
- `type`: 文章类别


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
  - `freebuf.com/articles/:type/*.html`
  - `freebuf.com/articles/:type`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "description": "::: tip\n  Freebuf 的文章页面带有反爬虫机制，所以目前无法获取文章的完整内容。\n:::",
  "example": "/freebuf/articles/web",
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
    "trganda"
  ],
  "module": "() => import('@/routes/freebuf/index.ts')",
  "name": "文章",
  "parameters": {
    "type": "文章类别"
  },
  "path": "/articles/:type",
  "radar": [
    {
      "source": [
        "freebuf.com/articles/:type/*.html",
        "freebuf.com/articles/:type"
      ]
    }
  ]
}
```
