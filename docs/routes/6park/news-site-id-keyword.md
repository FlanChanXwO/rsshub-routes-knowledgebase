# 留园网 - 新闻栏目

## Coverage
`index-only`

## Route
- Namespace: `6park`
- Namespace Name: `留园网`
- Route Path: `/news/:site?/:id?/:keyword?`
- Route Name: `新闻栏目`
- Example: `_None_`
- URL: `club.6parkbbs.com`
- Language: `zh-CN`
- Categories: `None`
- Maintainers: `nczitzk, cscnk52`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/6park/news.ts')`

## Description
::: tip 提示
若订阅 [时政](https://www.6parknews.com/newspark/index.php?type=1)，其网址为 <https://www.6parknews.com/newspark/index.php?type=1>，其中 `newspark` 为分站，`1` 为栏目 id。
若订阅 [美国](https://local.6parknews.com/index.php?type_id=1)，其网址为 <https://local.6parknews.com/index.php?type_id=1>，其中 `local` 为分站，`1` 为栏目 id。
:::

## Parameters
- `site`: 分站，可选newspark、local，默认为 newspark
- `id`: 栏目 id，可选，默认为空
- `keyword`: 关键词，可选，默认为空


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `club.6parkbbs.com/:id/index.php`
  - `club.6parkbbs.com/`
- `target`: `/:id?`

## Raw JSON
```json
{
  "description": "::: tip 提示\n若订阅 [时政](https://www.6parknews.com/newspark/index.php?type=1)，其网址为 <https://www.6parknews.com/newspark/index.php?type=1>，其中 `newspark` 为分站，`1` 为栏目 id。\n若订阅 [美国](https://local.6parknews.com/index.php?type_id=1)，其网址为 <https://local.6parknews.com/index.php?type_id=1>，其中 `local` 为分站，`1` 为栏目 id。\n:::",
  "location": "news.ts",
  "maintainers": [
    "nczitzk",
    "cscnk52"
  ],
  "module": "() => import('@/routes/6park/news.ts')",
  "name": "新闻栏目",
  "parameters": {
    "id": "栏目 id，可选，默认为空",
    "keyword": "关键词，可选，默认为空",
    "site": "分站，可选newspark、local，默认为 newspark"
  },
  "path": "/news/:site?/:id?/:keyword?",
  "radar": [
    {
      "source": [
        "club.6parkbbs.com/:id/index.php",
        "club.6parkbbs.com/"
      ],
      "target": "/:id?"
    }
  ]
}
```
