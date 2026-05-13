# JavDB - 分類

## Coverage
`index-only`

## Route
- Namespace: `javdb`
- Namespace Name: `JavDB`
- Route Path: `/tags/:query?/:category?`
- Route Name: `分類`
- Example: `/javdb/tags/c2=5&c10=1`
- URL: `javdb.com/`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `tags.ts`
- Source Module: `() => import('@/routes/javdb/tags.ts')`

## Description
::: tip
  在 [分類](https://javdb.com/tags) 中选定分类后，URL 中 `tags?` 后的字段即为筛选参数。

  如 `https://javdb.com/tags?c2=5&c10=1` 中 `c2=5&c10=1` 为筛选参数。
:::

  分类

| 有碼     | 無碼       | 歐美    |
| -------- | ---------- | ------- |
| censored | uncensored | western |

## Parameters
- `query`: 筛选，默认为 `c10=1`
- `category`: 分类，见下表，默认为 `有碼`


## Features
- `requireConfig`: [{"description": "JavDB登陆后的session值，可在控制台的cookie下查找 `_jdb_session` 的值，即可获取", "name": "JAVDB_SESSION", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `javdb.com/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "::: tip\n  在 [分類](https://javdb.com/tags) 中选定分类后，URL 中 `tags?` 后的字段即为筛选参数。\n\n  如 `https://javdb.com/tags?c2=5&c10=1` 中 `c2=5&c10=1` 为筛选参数。\n:::\n\n  分类\n\n| 有碼     | 無碼       | 歐美    |\n| -------- | ---------- | ------- |\n| censored | uncensored | western |",
  "example": "/javdb/tags/c2=5&c10=1",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "JavDB登陆后的session值，可在控制台的cookie下查找 `_jdb_session` 的值，即可获取",
        "name": "JAVDB_SESSION",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "tags.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/javdb/tags.ts')",
  "name": "分類",
  "parameters": {
    "category": "分类，见下表，默认为 `有碼`",
    "query": "筛选，默认为 `c10=1`"
  },
  "path": "/tags/:query?/:category?",
  "radar": [
    {
      "source": [
        "javdb.com/"
      ],
      "target": ""
    }
  ],
  "url": "javdb.com/"
}
```
