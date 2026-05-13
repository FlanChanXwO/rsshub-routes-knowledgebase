# JavDB - 主页

## Coverage
`index-only`

## Route
- Namespace: `javdb`
- Namespace Name: `JavDB`
- Route Path: `/home/:category?/:sort?/:filter?`
- Route Name: `主页`
- Example: `/javdb/home`
- URL: `javdb.com/`
- Language: `zh-CN`
- Categories: `None`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/javdb/index.ts')`

## Description
分类

| 有碼     | 無碼       | 歐美    |
| -------- | ---------- | ------- |
| censored | uncensored | western |

  排序

| 发布日期排序 | 磁鏈更新排序 |
| ------------ | ------------ |
| 1            | 2            |

  过滤

| 全部 | 可下载 | 含字幕 | 含短評 |
| ---- | ------ | ------ | ------ |
| 0    | 1      | 2      | 3      |

## Parameters
- `category`: 分类，见下表，默认为 `有碼`
- `sort`: 排序，见下表，默认为 `磁鏈更新排序`
- `filter`: 过滤，见下表，默认为 `可下载`


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `javdb.com/`

## Raw JSON
```json
{
  "description": "分类\n\n| 有碼     | 無碼       | 歐美    |\n| -------- | ---------- | ------- |\n| censored | uncensored | western |\n\n  排序\n\n| 发布日期排序 | 磁鏈更新排序 |\n| ------------ | ------------ |\n| 1            | 2            |\n\n  过滤\n\n| 全部 | 可下载 | 含字幕 | 含短評 |\n| ---- | ------ | ------ | ------ |\n| 0    | 1      | 2      | 3      |",
  "example": "/javdb/home",
  "features": {
    "nsfw": true
  },
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/javdb/index.ts')",
  "name": "主页",
  "parameters": {
    "category": "分类，见下表，默认为 `有碼`",
    "filter": "过滤，见下表，默认为 `可下载`",
    "sort": "排序，见下表，默认为 `磁鏈更新排序`"
  },
  "path": "/home/:category?/:sort?/:filter?",
  "radar": [
    {
      "source": [
        "javdb.com/"
      ]
    }
  ],
  "url": "javdb.com/"
}
```
