# 国家能源局 - 宁波市人力资源和社会保障局-公告

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/zj/ningborsjnotice/:colId?`
- Route Name: `宁波市人力资源和社会保障局-公告`
- Example: `/gov/zj/ningborsjnotice/1229676740`
- URL: `rsj.ningbo.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `HaoyuLee`
- Source Location: `zj/ningborsjnotice.ts`
- Source Module: `() => import('@/routes/gov/zj/ningborsjnotice.ts')`

## Description
| 公告类别         | colId |
| ------------ | -- |
| 事业单位进人公告     | 1229676740  |

## Parameters
- `colId`: 公告分类id、详细信息点击源网站http://rsj.ningbo.gov.cn/请求中寻找


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `rsj.ningbo.gov.cn/col/col1229676740/index.html`
- `target`: `/zj/ningborsjnotice/:colId?`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "\n| 公告类别         | colId |\n| ------------ | -- |\n| 事业单位进人公告     | 1229676740  |\n    ",
  "example": "/gov/zj/ningborsjnotice/1229676740",
  "location": "zj/ningborsjnotice.ts",
  "maintainers": [
    "HaoyuLee"
  ],
  "module": "() => import('@/routes/gov/zj/ningborsjnotice.ts')",
  "name": "宁波市人力资源和社会保障局-公告",
  "parameters": {
    "colId": "公告分类id、详细信息点击源网站http://rsj.ningbo.gov.cn/请求中寻找"
  },
  "path": "/zj/ningborsjnotice/:colId?",
  "radar": [
    {
      "source": [
        "rsj.ningbo.gov.cn/col/col1229676740/index.html"
      ],
      "target": "/zj/ningborsjnotice/:colId?"
    }
  ],
  "url": "rsj.ningbo.gov.cn"
}
```
