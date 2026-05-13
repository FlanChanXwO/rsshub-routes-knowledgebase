# finviz - News

## Coverage
`index-only`

## Route
- Namespace: `finviz`
- Namespace Name: `finviz`
- Route Path: `/:category?`
- Route Name: `News`
- Example: `/finviz`
- URL: `finviz.com/news.ashx`
- Language: `en`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/finviz/news.ts')`

## Description
| News | Blogs |
| ---- | ---- |
| news | blogs |

## Parameters
- `category`: {"description": "Category, see below, News by default", "options": [{"label": "news", "value": "news"}, {"label": "blogs", "value": "blogs"}]}


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
  - `finviz.com/news.ashx`
  - `finviz.com/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| News | Blogs |\n| ---- | ---- |\n| news | blogs |",
  "example": "/finviz",
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
    "nczitzk"
  ],
  "module": "() => import('@/routes/finviz/news.ts')",
  "name": "News",
  "parameters": {
    "category": {
      "description": "Category, see below, News by default",
      "options": [
        {
          "label": "news",
          "value": "news"
        },
        {
          "label": "blogs",
          "value": "blogs"
        }
      ]
    }
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "finviz.com/news.ashx",
        "finviz.com/"
      ]
    }
  ],
  "url": "finviz.com/news.ashx",
  "view": 0
}
```
