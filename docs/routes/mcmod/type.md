# MC百科 - 最新MOD

## Coverage
`index-only`

## Route
- Namespace: `mcmod`
- Namespace Name: `MC百科`
- Route Path: `/:type`
- Route Name: `最新MOD`
- Example: `/mcmod/new`
- URL: `www.mcmod.cn`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `hualiong`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/mcmod/index.tsx')`

## Description
`:type` 类型可选如下

| 随机显示MOD | 最新收录MOD | 最近编辑MOD |
| ------ | --- | ---- |
| random | new | edit |

## Parameters
- `type`: 查询类型，详见下表


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
    "game"
  ],
  "description": "`:type` 类型可选如下\n\n| 随机显示MOD | 最新收录MOD | 最近编辑MOD |\n| ------ | --- | ---- |\n| random | new | edit |",
  "example": "/mcmod/new",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.tsx",
  "maintainers": [
    "hualiong"
  ],
  "module": "() => import('@/routes/mcmod/index.tsx')",
  "name": "最新MOD",
  "parameters": {
    "type": "查询类型，详见下表"
  },
  "path": "/:type"
}
```
