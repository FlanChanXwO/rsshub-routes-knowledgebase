# 机核网 - 分类

## Coverage
`index-only`

## Route
- Namespace: `gcores`
- Namespace Name: `机核网`
- Route Path: `/categories/:id/:tab?`
- Route Name: `分类`
- Example: `/gcores/categories/1/articles`
- URL: `www.gcores.com`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `MoguCloud, StevenRCE0, nczitzk`
- Source Location: `categories.ts`
- Source Module: `() => import('@/routes/gcores/categories.ts')`

## Description
::: tip
若订阅 [文章 - 文章](https://www.gcores.com/categories/1?tab=articles)，网址为 `https://www.gcores.com/categories/1?tab=articles`，请截取 `https://www.gcores.com/categories/` 到末尾的部分 `1` 作为 `id` 参数填入，截取 `articles` 作为 `tab` 参数填入，此时目标路由为 [`/gcores/categories/1/articles`](https://rsshub.app/gcores/categories/1/articles)。
:::

| 全部 | 播客   | 文章     | 资讯 | 视频   |
| ---- | ------ | -------- | ---- | ------ |
|      | radios | articles | news | videos |

## Parameters
- `id`: {"description": "分类 ID，可在对应分类页 URL 中找到"}
- `tab`: {"description": "类型，默认为空，即全部，可在对应分类页 URL 中找到", "options": [{"label": "全部", "value": ""}, {"label": "播客", "value": "radios"}, {"label": "文章", "value": "articles"}, {"label": "资讯", "value": "news"}, {"label": "视频", "value": "videos"}]}


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
  - `www.gcores.com/categories/:id`
### Rule 2
- `title`: `全部`
- `source`:
  - `www.gcores.com/categories/:id`
- `target`: `/gcores/categories/:id`
### Rule 3
- `title`: `播客`
- `source`:
  - `www.gcores.com/categories/:id`
- `target`: `/categories/:id/radios`
### Rule 4
- `title`: `文章`
- `source`:
  - `www.gcores.com/categories/:id`
- `target`: `/categories/:id/articles`
### Rule 5
- `title`: `资讯`
- `source`:
  - `www.gcores.com/categories/:id`
- `target`: `/categories/:id/news`
### Rule 6
- `title`: `视频`
- `source`:
  - `www.gcores.com/categories/:id`
- `target`: `/categories/:id/videos`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "::: tip\n若订阅 [文章 - 文章](https://www.gcores.com/categories/1?tab=articles)，网址为 `https://www.gcores.com/categories/1?tab=articles`，请截取 `https://www.gcores.com/categories/` 到末尾的部分 `1` 作为 `id` 参数填入，截取 `articles` 作为 `tab` 参数填入，此时目标路由为 [`/gcores/categories/1/articles`](https://rsshub.app/gcores/categories/1/articles)。\n:::\n\n| 全部 | 播客   | 文章     | 资讯 | 视频   |\n| ---- | ------ | -------- | ---- | ------ |\n|      | radios | articles | news | videos |\n",
  "example": "/gcores/categories/1/articles",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "categories.ts",
  "maintainers": [
    "MoguCloud",
    "StevenRCE0",
    "nczitzk"
  ],
  "module": "() => import('@/routes/gcores/categories.ts')",
  "name": "分类",
  "parameters": {
    "id": {
      "description": "分类 ID，可在对应分类页 URL 中找到"
    },
    "tab": {
      "description": "类型，默认为空，即全部，可在对应分类页 URL 中找到",
      "options": [
        {
          "label": "全部",
          "value": ""
        },
        {
          "label": "播客",
          "value": "radios"
        },
        {
          "label": "文章",
          "value": "articles"
        },
        {
          "label": "资讯",
          "value": "news"
        },
        {
          "label": "视频",
          "value": "videos"
        }
      ]
    }
  },
  "path": "/categories/:id/:tab?",
  "radar": [
    {
      "source": [
        "www.gcores.com/categories/:id"
      ]
    },
    {
      "source": [
        "www.gcores.com/categories/:id"
      ],
      "target": "/gcores/categories/:id",
      "title": "全部"
    },
    {
      "source": [
        "www.gcores.com/categories/:id"
      ],
      "target": "/categories/:id/radios",
      "title": "播客"
    },
    {
      "source": [
        "www.gcores.com/categories/:id"
      ],
      "target": "/categories/:id/articles",
      "title": "文章"
    },
    {
      "source": [
        "www.gcores.com/categories/:id"
      ],
      "target": "/categories/:id/news",
      "title": "资讯"
    },
    {
      "source": [
        "www.gcores.com/categories/:id"
      ],
      "target": "/categories/:id/videos",
      "title": "视频"
    }
  ],
  "url": "www.gcores.com",
  "view": 0
}
```
