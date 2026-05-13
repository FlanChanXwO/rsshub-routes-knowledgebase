# PSN 中文站 - 节点

## Coverage
`index-only`

## Route
- Namespace: `psnine`
- Namespace Name: `PSN 中文站`
- Route Path: `/node/:id?/:order?`
- Route Name: `节点`
- Example: `/psnine/node/news`
- URL: `psnine.com`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `betta-cyber, nczitzk`
- Source Location: `node.ts`
- Source Module: `() => import('@/routes/psnine/node.ts')`

## Description
_None_

## Parameters
- `id`: 节点 id，见下表，默认为 news
- `order`: 排序，`date` 即最新，默认为 `obdate` 即综合排序


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `psnine.com/node/:id`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/psnine/node/news",
  "location": "node.ts",
  "maintainers": [
    "betta-cyber",
    "nczitzk"
  ],
  "module": "() => import('@/routes/psnine/node.ts')",
  "name": "节点",
  "parameters": {
    "id": "节点 id，见下表，默认为 news",
    "order": "排序，`date` 即最新，默认为 `obdate` 即综合排序"
  },
  "path": "/node/:id?/:order?",
  "radar": [
    {
      "source": [
        "psnine.com/node/:id"
      ]
    }
  ]
}
```
