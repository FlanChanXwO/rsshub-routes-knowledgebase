# ZAKER - 分类

## Coverage
`index-only`

## Route
- Namespace: `zaker`
- Namespace Name: `ZAKER`
- Route Path: `/channel/:id?`
- Route Name: `分类`
- Example: `/zaker/channel/13`
- URL: `myzaker.com`
- Language: `zh-CN`
- Categories: `None`
- Maintainers: `LogicJake, kt286, TonyRL`
- Source Location: `channel.ts`
- Source Module: `() => import('@/routes/zaker/channel.ts')`

## Description
_None_

## Parameters
- `id`: 分类 ID，可在 URL 中找到，默认为 `1`


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.myzaker.com/channel/:id`
- `target`: `/channel/:id`

## Raw JSON
```json
{
  "example": "/zaker/channel/13",
  "location": "channel.ts",
  "maintainers": [
    "LogicJake",
    "kt286",
    "TonyRL"
  ],
  "module": "() => import('@/routes/zaker/channel.ts')",
  "name": "分类",
  "parameters": {
    "id": "分类 ID，可在 URL 中找到，默认为 `1`"
  },
  "path": "/channel/:id?",
  "radar": [
    {
      "source": [
        "www.myzaker.com/channel/:id"
      ],
      "target": "/channel/:id"
    }
  ]
}
```
