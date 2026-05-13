# 集思录 - 用户

## Coverage
`index-only`

## Route
- Namespace: `jisilu`
- Namespace Name: `集思录`
- Route Path: `/people/:id/:type?`
- Route Name: `用户`
- Example: `/jisilu/people/天书`
- URL: `www.jisilu.cn`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `people.ts`
- Source Module: `() => import('@/routes/jisilu/people.ts')`

## Description
::: tip
若订阅 [天书的主题](https://www.jisilu.cn/people/天书)，网址为 `https://www.jisilu.cn/people/天书`，请截取 `https://www.jisilu.cn/people/` 到末尾的部分 `天书` 作为 `id` 参数填入，此时目标路由为 [`/jisilu/people/天书`](https://rsshub.app/jisilu/people/天书)。
:::

::: tip
前往 [用户排名](https://www.jisilu.cn/users/) 查看更多用户。
:::

## Parameters
- `id`: 用户 id，可在对应用户页 URL 中找到
- `type`: 类型，可选值为 `questions` 即 `主题` 或 `answer` 即 `回复`，默认为 `questions` 即 `主题`


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
  - `www.jisilu.cn/people/:id`
- `target`: `/people/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "::: tip\n若订阅 [天书的主题](https://www.jisilu.cn/people/天书)，网址为 `https://www.jisilu.cn/people/天书`，请截取 `https://www.jisilu.cn/people/` 到末尾的部分 `天书` 作为 `id` 参数填入，此时目标路由为 [`/jisilu/people/天书`](https://rsshub.app/jisilu/people/天书)。\n:::\n\n::: tip\n前往 [用户排名](https://www.jisilu.cn/users/) 查看更多用户。\n:::\n",
  "example": "/jisilu/people/天书",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "people.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/jisilu/people.ts')",
  "name": "用户",
  "parameters": {
    "id": "用户 id，可在对应用户页 URL 中找到",
    "type": "类型，可选值为 `questions` 即 `主题` 或 `answer` 即 `回复`，默认为 `questions` 即 `主题`"
  },
  "path": "/people/:id/:type?",
  "radar": [
    {
      "source": [
        "www.jisilu.cn/people/:id"
      ],
      "target": "/people/:id"
    }
  ],
  "url": "www.jisilu.cn",
  "view": 0
}
```
