# 丁香园 - 板块

## Coverage
`index-only`

## Route
- Namespace: `dxy`
- Namespace Name: `丁香园`
- Route Path: `/bbs/board/:boardId`
- Route Name: `板块`
- Example: `/dxy/bbs/board/46`
- URL: `dxy.cn`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `TonyRL`
- Source Location: `board.ts`
- Source Module: `() => import('@/routes/dxy/board.ts')`

## Description
_None_

## Parameters
- `specialId`: 板块 ID，可在对应板块页 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.dxy.cn/bbs/newweb/pc/category/:boardIdId`
- `target`: `/bbs/board/:boardIdId`
### Rule 2
- `source`:
  - `3g.dxy.cn/bbs/board/:boardIdId`
- `target`: `/bbs/board/:boardIdId`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/dxy/bbs/board/46",
  "location": "board.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/dxy/board.ts')",
  "name": "板块",
  "parameters": {
    "specialId": "板块 ID，可在对应板块页 URL 中找到"
  },
  "path": "/bbs/board/:boardId",
  "radar": [
    {
      "source": [
        "www.dxy.cn/bbs/newweb/pc/category/:boardIdId"
      ],
      "target": "/bbs/board/:boardIdId"
    },
    {
      "source": [
        "3g.dxy.cn/bbs/board/:boardIdId"
      ],
      "target": "/bbs/board/:boardIdId"
    }
  ]
}
```
