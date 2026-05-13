# Deepin - 首页主题列表

## Coverage
`index-only`

## Route
- Namespace: `deepin`
- Namespace Name: `Deepin`
- Route Path: `/threads/:type?`
- Route Name: `首页主题列表`
- Example: `/deepin/threads/latest`
- URL: `bbs.deepin.org`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `myml`
- Source Location: `thread.ts`
- Source Module: `() => import('@/routes/deepin/thread.ts')`

## Description
_None_

## Parameters
- `type`: {"description": "主题类型", "options": [{"label": "最热主题", "value": "hot"}, {"label": "最新主题", "value": "latest"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `bbs.deepin.org`
- `target`: `/threads/latest`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/deepin/threads/latest",
  "location": "thread.ts",
  "maintainers": [
    "myml"
  ],
  "module": "() => import('@/routes/deepin/thread.ts')",
  "name": "首页主题列表",
  "parameters": {
    "type": {
      "description": "主题类型",
      "options": [
        {
          "label": "最热主题",
          "value": "hot"
        },
        {
          "label": "最新主题",
          "value": "latest"
        }
      ]
    }
  },
  "path": "/threads/:type?",
  "radar": [
    {
      "source": [
        "bbs.deepin.org"
      ],
      "target": "/threads/latest"
    }
  ]
}
```
