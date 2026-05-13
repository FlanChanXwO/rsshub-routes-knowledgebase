# 机核网 - 标签

## Coverage
`index-only`

## Route
- Namespace: `gcores`
- Namespace Name: `机核网`
- Route Path: `/tags/:id/:tab?`
- Route Name: `标签`
- Example: `/gcores/tags/1/articles`
- URL: `www.gcores.com`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `StevenRCE0, nczitzk`
- Source Location: `tags.ts`
- Source Module: `() => import('@/routes/gcores/tags.ts')`

## Description
::: tip
若订阅 [美国 - 文章](https://www.gcores.com/tags/1/originals?tab=articles)，网址为 `https://www.gcores.com/tags/1/originals?tab=articles`，请截取 `https://www.gcores.com/tags/` 到末尾 `/originals` 的部分 `1` 作为 `id` 参数填入，截取 `articles` 作为 `tab` 参数填入，此时目标路由为 [`/gcores/tags/1/articles`](https://rsshub.app/gcores/tags/1/articles)。
:::

| 全部 | 播客   | 文章     | 资讯 | 视频   |
| ---- | ------ | -------- | ---- | ------ |
|      | radios | articles | news | videos |

## Parameters
- `id`: {"description": "标签 ID，可在对应标签页 URL 中找到"}
- `tab`: {"description": "类型，默认为空，即全部，可在对应标签页 URL 中找到", "options": [{"label": "全部", "value": ""}, {"label": "播客", "value": "radios"}, {"label": "文章", "value": "articles"}, {"label": "资讯", "value": "news"}, {"label": "视频", "value": "videos"}]}


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
  - `www.gcores.com/tags/:id/originals`
### Rule 2
- `title`: `全部`
- `source`:
  - `www.gcores.com/tags/:id/originals`
- `target`: `/gcores/tags/:id`
### Rule 3
- `title`: `播客`
- `source`:
  - `www.gcores.com/tags/:id/originals`
- `target`: `/gcores/tags/:id/radios`
### Rule 4
- `title`: `文章`
- `source`:
  - `www.gcores.com/tags/:id/originals`
- `target`: `/gcores/tags/:id/articles`
### Rule 5
- `title`: `资讯`
- `source`:
  - `www.gcores.com/tags/:id/originals`
- `target`: `/gcores/tags/:id/news`
### Rule 6
- `title`: `视频`
- `source`:
  - `www.gcores.com/tags/:id/originals`
- `target`: `/gcores/tags/:id/videos`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "::: tip\n若订阅 [美国 - 文章](https://www.gcores.com/tags/1/originals?tab=articles)，网址为 `https://www.gcores.com/tags/1/originals?tab=articles`，请截取 `https://www.gcores.com/tags/` 到末尾 `/originals` 的部分 `1` 作为 `id` 参数填入，截取 `articles` 作为 `tab` 参数填入，此时目标路由为 [`/gcores/tags/1/articles`](https://rsshub.app/gcores/tags/1/articles)。\n:::\n\n| 全部 | 播客   | 文章     | 资讯 | 视频   |\n| ---- | ------ | -------- | ---- | ------ |\n|      | radios | articles | news | videos |\n",
  "example": "/gcores/tags/1/articles",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "tags.ts",
  "maintainers": [
    "StevenRCE0",
    "nczitzk"
  ],
  "module": "() => import('@/routes/gcores/tags.ts')",
  "name": "标签",
  "parameters": {
    "id": {
      "description": "标签 ID，可在对应标签页 URL 中找到"
    },
    "tab": {
      "description": "类型，默认为空，即全部，可在对应标签页 URL 中找到",
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
  "path": "/tags/:id/:tab?",
  "radar": [
    {
      "source": [
        "www.gcores.com/tags/:id/originals"
      ]
    },
    {
      "source": [
        "www.gcores.com/tags/:id/originals"
      ],
      "target": "/gcores/tags/:id",
      "title": "全部"
    },
    {
      "source": [
        "www.gcores.com/tags/:id/originals"
      ],
      "target": "/gcores/tags/:id/radios",
      "title": "播客"
    },
    {
      "source": [
        "www.gcores.com/tags/:id/originals"
      ],
      "target": "/gcores/tags/:id/articles",
      "title": "文章"
    },
    {
      "source": [
        "www.gcores.com/tags/:id/originals"
      ],
      "target": "/gcores/tags/:id/news",
      "title": "资讯"
    },
    {
      "source": [
        "www.gcores.com/tags/:id/originals"
      ],
      "target": "/gcores/tags/:id/videos",
      "title": "视频"
    }
  ],
  "url": "www.gcores.com",
  "view": 0
}
```
