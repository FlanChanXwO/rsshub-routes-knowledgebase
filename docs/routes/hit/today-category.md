# 哈尔滨工业大学 - 今日哈工大

## Coverage
`index-only`

## Route
- Namespace: `hit`
- Namespace Name: `哈尔滨工业大学`
- Route Path: `/today/:category`
- Route Name: `今日哈工大`
- Example: `/hit/today/10`
- URL: `www.hit.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `ranpox`
- Source Location: `today.ts`
- Source Module: `() => import('@/routes/hit/today.ts')`

## Description
::: tip
  今日哈工大的文章分为公告公示和新闻快讯，每个页面右侧列出了更详细的分类，其编号为每个 URL 路径的最后一个数字。
  例如会议讲座的路径为`/taxonomy/term/10/25`，则可以通过 [`/hit/today/25`](https://rsshub.app/hit/today/25) 订阅该详细类别。
:::

::: warning
  部分文章需要经过统一身份认证后才能阅读全文。
:::

## Parameters
- `category`: 分类编号，`10`为公告公示，`11`为新闻快讯，同时支持详细分类，使用方法见下


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
  - `today.hit.edu.cn/category/:category`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "::: tip\n  今日哈工大的文章分为公告公示和新闻快讯，每个页面右侧列出了更详细的分类，其编号为每个 URL 路径的最后一个数字。\n  例如会议讲座的路径为`/taxonomy/term/10/25`，则可以通过 [`/hit/today/25`](https://rsshub.app/hit/today/25) 订阅该详细类别。\n:::\n\n::: warning\n  部分文章需要经过统一身份认证后才能阅读全文。\n:::",
  "example": "/hit/today/10",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "today.ts",
  "maintainers": [
    "ranpox"
  ],
  "module": "() => import('@/routes/hit/today.ts')",
  "name": "今日哈工大",
  "parameters": {
    "category": "分类编号，`10`为公告公示，`11`为新闻快讯，同时支持详细分类，使用方法见下"
  },
  "path": "/today/:category",
  "radar": [
    {
      "source": [
        "today.hit.edu.cn/category/:category"
      ]
    }
  ]
}
```
