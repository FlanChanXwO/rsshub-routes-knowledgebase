# 数字尾巴 - 鲸闻

## Coverage
`index-only`

## Route
- Namespace: `dgtle`
- Namespace Name: `数字尾巴`
- Route Path: `/news/:id?`
- Route Name: `鲸闻`
- Example: `/dgtle/news/0`
- URL: `www.dgtle.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/dgtle/news.ts')`

## Description
:::tip
订阅 [最新](https://www.dgtle.com/news)，其对应分类 ID 为 `0`，此时路由为 [`/dgtle/news/0`](https://rsshub.app/dgtle/news/0)。
:::

| 最新 | 直播 | 资讯 | 每日一言 |
| ---- | ---- | ---- | -------- |
| 0    | 395  | 396  | 388      |

## Parameters
- `id`: {"description": "分类，默认为 `0`，即最新，可在下表中找到", "options": [{"label": "最新", "value": "0"}, {"label": "直播", "value": "395"}, {"label": "资讯", "value": "396"}, {"label": "每日一言", "value": "388"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.dgtle.com/news`
- `target`: `/news`
### Rule 2
- `title`: `最新`
- `source`:
  - `www.dgtle.com/news`
- `target`: `/news/0`
### Rule 3
- `title`: `直播`
- `source`:
  - `www.dgtle.com/news`
- `target`: `/news/395`
### Rule 4
- `title`: `资讯`
- `source`:
  - `www.dgtle.com/news`
- `target`: `/news/396`
### Rule 5
- `title`: `每日一言`
- `source`:
  - `www.dgtle.com/news`
- `target`: `/news/388`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": ":::tip\n订阅 [最新](https://www.dgtle.com/news)，其对应分类 ID 为 `0`，此时路由为 [`/dgtle/news/0`](https://rsshub.app/dgtle/news/0)。\n:::\n\n| 最新 | 直播 | 资讯 | 每日一言 |\n| ---- | ---- | ---- | -------- |\n| 0    | 395  | 396  | 388      |\n",
  "example": "/dgtle/news/0",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/dgtle/news.ts')",
  "name": "鲸闻",
  "parameters": {
    "id": {
      "description": "分类，默认为 `0`，即最新，可在下表中找到",
      "options": [
        {
          "label": "最新",
          "value": "0"
        },
        {
          "label": "直播",
          "value": "395"
        },
        {
          "label": "资讯",
          "value": "396"
        },
        {
          "label": "每日一言",
          "value": "388"
        }
      ]
    }
  },
  "path": "/news/:id?",
  "radar": [
    {
      "source": [
        "www.dgtle.com/news"
      ],
      "target": "/news"
    },
    {
      "source": [
        "www.dgtle.com/news"
      ],
      "target": "/news/0",
      "title": "最新"
    },
    {
      "source": [
        "www.dgtle.com/news"
      ],
      "target": "/news/395",
      "title": "直播"
    },
    {
      "source": [
        "www.dgtle.com/news"
      ],
      "target": "/news/396",
      "title": "资讯"
    },
    {
      "source": [
        "www.dgtle.com/news"
      ],
      "target": "/news/388",
      "title": "每日一言"
    }
  ],
  "url": "www.dgtle.com",
  "view": 0
}
```
