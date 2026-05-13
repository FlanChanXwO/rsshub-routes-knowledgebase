# 豆瓣 - 即将播出的剧集

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/tv/coming/:sortBy?/:count?`
- Route Name: `即将播出的剧集`
- Example: `/douban/tv/coming`
- URL: `www.douban.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `honue`
- Source Location: `tv/coming.ts`
- Source Module: `() => import('@/routes/douban/tv/coming.ts')`

## Description
| 路径参数 | 含义             | 接受的值 | 默认值 |
| -------- | ---------------- | -------- | ------ |
| sortBy   | 排序方式         | hot/time | hot    |
| count    | 请求上游返回数量 | 正整数   | 10     |

  用例：`/douban/tv/coming/hot/10`

::: tip
  服务端请求固定使用 `sortby=hot` 拉取数据，再按 `sortBy` 参数在本地重排；条目数量可通过 `count` 调整，仍可叠加 RSSHub 通用参数 `limit`。
:::

## Parameters
- `sortBy`: 排序方式，可选，支持 `hot` 或 `time`，默认 `hot`
- `count`: 请求上游返回数量，可选，正整数，默认 `10`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "| 路径参数 | 含义             | 接受的值 | 默认值 |\n| -------- | ---------------- | -------- | ------ |\n| sortBy   | 排序方式         | hot/time | hot    |\n| count    | 请求上游返回数量 | 正整数   | 10     |\n\n  用例：`/douban/tv/coming/hot/10`\n\n::: tip\n  服务端请求固定使用 `sortby=hot` 拉取数据，再按 `sortBy` 参数在本地重排；条目数量可通过 `count` 调整，仍可叠加 RSSHub 通用参数 `limit`。\n:::",
  "example": "/douban/tv/coming",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "tv/coming.ts",
  "maintainers": [
    "honue"
  ],
  "module": "() => import('@/routes/douban/tv/coming.ts')",
  "name": "即将播出的剧集",
  "parameters": {
    "count": "请求上游返回数量，可选，正整数，默认 `10`",
    "sortBy": "排序方式，可选，支持 `hot` 或 `time`，默认 `hot`"
  },
  "path": "/tv/coming/:sortBy?/:count?"
}
```
