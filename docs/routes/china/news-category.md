# China.com 中华网 - News and current affairs 时事新闻

## Coverage
`index-only`

## Route
- Namespace: `china`
- Namespace Name: `China.com 中华网`
- Route Path: `/news/:category?`
- Route Name: `News and current affairs 时事新闻`
- Example: `/china/news`
- URL: `finance.china.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `jiaaoMario`
- Source Location: `news/highlights/news.ts`
- Source Module: `() => import('@/routes/china/news/highlights/news.ts')`

## Description
Category of news

| China News | International News | Social News | Breaking News |
| ---------- | ------------------ | ----------- | ------------- |
| domestic   | international      | social      | news100       |

## Parameters
- `category`: Category of news. See the form below for details, default is china news.


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
  - `news.china.com/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "Category of news\n\n| China News | International News | Social News | Breaking News |\n| ---------- | ------------------ | ----------- | ------------- |\n| domestic   | international      | social      | news100       |",
  "example": "/china/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news/highlights/news.ts",
  "maintainers": [
    "jiaaoMario"
  ],
  "module": "() => import('@/routes/china/news/highlights/news.ts')",
  "name": "News and current affairs 时事新闻",
  "parameters": {
    "category": "Category of news. See the form below for details, default is china news."
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "news.china.com/:category"
      ]
    }
  ]
}
```
