# 南方网 - 南方 +（按栏目 ID）

## Coverage
`index-only`

## Route
- Namespace: `southcn`
- Namespace Name: `南方网`
- Route Path: `/nfapp/column/:column?`
- Route Name: `南方 +（按栏目 ID）`
- Example: `/southcn/nfapp/column/38`
- URL: `nfapp.southcn.com`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `TimWu007`
- Source Location: `nfapp/column.ts`
- Source Module: `() => import('@/routes/southcn/nfapp/column.ts')`

## Description
::: tip
  若此处输入的是栏目 ID（而非南方号 ID），则该接口会返回与输入栏目相关联栏目的文章。例如，输入栏目 ID `38`（广州），则返回的结果还会包含 ID 为 `3547`（市长报道集）的文章。
:::

  1.  `pc.nfapp.southcn.com` 下的文章页面，可通过 url 查看，例：`http://pc.nfapp.southcn.com/13707/7491109.html` 的栏目 ID 为 `13707`。
  2.  `static.nfapp.southcn.com` 下的文章页面，可查看网页源代码，搜索 `columnid`。
  3.  [https://m.nfapp.southcn.com/column/all](https://m.nfapp.southcn.com/column/all) 列出了部分栏目，`id` 即为栏目 ID。

## Parameters
- `column`: 栏目或南方号 ID


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
    "traditional-media"
  ],
  "description": "::: tip\n  若此处输入的是栏目 ID（而非南方号 ID），则该接口会返回与输入栏目相关联栏目的文章。例如，输入栏目 ID `38`（广州），则返回的结果还会包含 ID 为 `3547`（市长报道集）的文章。\n:::\n\n  1.  `pc.nfapp.southcn.com` 下的文章页面，可通过 url 查看，例：`http://pc.nfapp.southcn.com/13707/7491109.html` 的栏目 ID 为 `13707`。\n  2.  `static.nfapp.southcn.com` 下的文章页面，可查看网页源代码，搜索 `columnid`。\n  3.  [https://m.nfapp.southcn.com/column/all](https://m.nfapp.southcn.com/column/all) 列出了部分栏目，`id` 即为栏目 ID。",
  "example": "/southcn/nfapp/column/38",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "nfapp/column.ts",
  "maintainers": [
    "TimWu007"
  ],
  "module": "() => import('@/routes/southcn/nfapp/column.ts')",
  "name": "南方 +（按栏目 ID）",
  "parameters": {
    "column": "栏目或南方号 ID"
  },
  "path": "/nfapp/column/:column?"
}
```
