# 集思录 - 话题

## Coverage
`index-only`

## Route
- Namespace: `jisilu`
- Namespace Name: `集思录`
- Route Path: `/topic/:id`
- Route Name: `话题`
- Example: `/jisilu/topic/可转债`
- URL: `www.jisilu.cn`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `topic.ts`
- Source Module: `() => import('@/routes/jisilu/topic.ts')`

## Description
::: tip
若订阅 [可转债](https://www.jisilu.cn/topic/可转债)，网址为 `https://www.jisilu.cn/topic/可转债`，请截取 `https://www.jisilu.cn/topic/` 到末尾的部分 `可转债` 作为 `id` 参数填入，此时目标路由为 [`/jisilu/topic/可转债`](https://rsshub.app/jisilu/topic/可转债)。
:::

::: tip
前往 [话题广场](https://www.jisilu.cn/topic) 查看更多话题。
:::

## Parameters
- `id`: 话题 id，可在对应话题页 URL 中找到


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
  - `www.jisilu.cn/topic/:id`
- `target`: `/topic/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "::: tip\n若订阅 [可转债](https://www.jisilu.cn/topic/可转债)，网址为 `https://www.jisilu.cn/topic/可转债`，请截取 `https://www.jisilu.cn/topic/` 到末尾的部分 `可转债` 作为 `id` 参数填入，此时目标路由为 [`/jisilu/topic/可转债`](https://rsshub.app/jisilu/topic/可转债)。\n:::\n\n::: tip\n前往 [话题广场](https://www.jisilu.cn/topic) 查看更多话题。\n:::\n",
  "example": "/jisilu/topic/可转债",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "topic.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/jisilu/topic.ts')",
  "name": "话题",
  "parameters": {
    "id": "话题 id，可在对应话题页 URL 中找到"
  },
  "path": "/topic/:id",
  "radar": [
    {
      "source": [
        "www.jisilu.cn/topic/:id"
      ],
      "target": "/topic/:id"
    }
  ],
  "url": "www.jisilu.cn",
  "view": 0
}
```
