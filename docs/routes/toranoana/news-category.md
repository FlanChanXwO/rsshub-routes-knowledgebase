# とらのあな - Category

## Coverage
`index-only`

## Route
- Namespace: `toranoana`
- Namespace Name: `とらのあな`
- Route Path: `/news/:category?`
- Route Name: `Category`
- Example: `/toranoana/news/toragen`
- URL: `toranoana.jp`
- Language: `ja`
- Categories: `anime`
- Maintainers: `Tsuyumi25`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/toranoana/news.ts')`

## Description
::: warning TIP
[総合新着記事](https://news.toranoana.jp)→`/toranoana/news`  
[女性向け](https://news.toranoana.jp/joshi)→`/toranoana/news/joshi`  
[イラスト展](https://news.toranoana.jp/exhibitions)→`/toranoana/news/exhibition`  
[`https://news.toranoana.jp/category/media`](https://news.toranoana.jp/category/media)→`/toranoana/news/media`
:::

## Parameters
- `category`: category


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `title`: `総合新着記事`
- `source`:
  - `news.toranoana.jp`
- `target`: `/news`
### Rule 2
- `title`: `女性向け`
- `source`:
  - `news.toranoana.jp/joshi`
- `target`: `/news/joshi`
### Rule 3
- `title`: `イラスト展`
- `source`:
  - `news.toranoana.jp/exhibitions`
- `target`: `/news/exhibition`
### Rule 4
- `source`:
  - `news.toranoana.jp/category/:category`
- `target`: `/news/:category`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "\n::: warning TIP\n[総合新着記事](https://news.toranoana.jp)→`/toranoana/news`  \n[女性向け](https://news.toranoana.jp/joshi)→`/toranoana/news/joshi`  \n[イラスト展](https://news.toranoana.jp/exhibitions)→`/toranoana/news/exhibition`  \n[`https://news.toranoana.jp/category/media`](https://news.toranoana.jp/category/media)→`/toranoana/news/media`\n:::",
  "example": "/toranoana/news/toragen",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "Tsuyumi25"
  ],
  "module": "() => import('@/routes/toranoana/news.ts')",
  "name": "Category",
  "parameters": {
    "category": "category"
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "news.toranoana.jp"
      ],
      "target": "/news",
      "title": "総合新着記事"
    },
    {
      "source": [
        "news.toranoana.jp/joshi"
      ],
      "target": "/news/joshi",
      "title": "女性向け"
    },
    {
      "source": [
        "news.toranoana.jp/exhibitions"
      ],
      "target": "/news/exhibition",
      "title": "イラスト展"
    },
    {
      "source": [
        "news.toranoana.jp/category/:category"
      ],
      "target": "/news/:category"
    }
  ]
}
```
