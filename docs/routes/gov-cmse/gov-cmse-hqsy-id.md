# 中国载人航天工程 - 环球视野

## Coverage
`index-only`

## Route
- Namespace: `gov/cmse`
- Namespace Name: `中国载人航天工程`
- Route Path: `/gov/cmse/hqsy/:id`
- Route Name: `环球视野`
- Example: `/gov/cmse/hqsy/zxdta`
- URL: `www.cmse.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `hqsy.ts`
- Source Module: `_None_`

## Description
| 最新动态 | 美国 | 俄罗斯 | 欧洲 | 日本 | 印度 | 领域动态 |
| -------- | ---- | ------ | ---- | ---- | ---- | -------- |
| zxdta    | mg   | els    | oz   | rb   | yd   | lydt     |

## Parameters
- `id`: 分类 id，见下表，可在对应分类页 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.cmse.gov.cn/hqsy/:id`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 最新动态 | 美国 | 俄罗斯 | 欧洲 | 日本 | 印度 | 领域动态 |\n| -------- | ---- | ------ | ---- | ---- | ---- | -------- |\n| zxdta    | mg   | els    | oz   | rb   | yd   | lydt     |",
  "example": "/gov/cmse/hqsy/zxdta",
  "heat": 0,
  "location": "hqsy.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "环球视野",
  "parameters": {
    "id": "分类 id，见下表，可在对应分类页 URL 中找到"
  },
  "path": "/hqsy/:id",
  "radar": [
    {
      "source": [
        "www.cmse.gov.cn/hqsy/:id"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
