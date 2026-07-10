# 浙江省人民政府 - 宁波市人力资源和社会保障局-公告

## Coverage
`index-only`

## Route
- Namespace: `gov/zj`
- Namespace Name: `浙江省人民政府`
- Route Path: `/gov/zj/ningborsjnotice/:colId?`
- Route Name: `宁波市人力资源和社会保障局-公告`
- Example: `/gov/zj/ningborsjnotice/1229676740`
- URL: `rsj.ningbo.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `HaoyuLee`
- Source Location: `ningborsjnotice.ts`
- Source Module: `_None_`

## Description
| 公告类别         | colId      |
| ---------------- | ---------- |
| 事业单位进人公告 | 1229676740 |

## Parameters
- `colId`: 公告分类id、详细信息点击源网站http://rsj.ningbo.gov.cn/请求中寻找


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `rsj.ningbo.gov.cn/col/col1229676740/index.html`
- `target`: `/ningborsjnotice/:colId?`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 公告类别         | colId      |\n| ---------------- | ---------- |\n| 事业单位进人公告 | 1229676740 |",
  "example": "/gov/zj/ningborsjnotice/1229676740",
  "heat": 0,
  "location": "ningborsjnotice.ts",
  "maintainers": [
    "HaoyuLee"
  ],
  "name": "宁波市人力资源和社会保障局-公告",
  "parameters": {
    "colId": "公告分类id、详细信息点击源网站http://rsj.ningbo.gov.cn/请求中寻找"
  },
  "path": "/ningborsjnotice/:colId?",
  "radar": [
    {
      "source": [
        "rsj.ningbo.gov.cn/col/col1229676740/index.html"
      ],
      "target": "/ningborsjnotice/:colId?"
    }
  ],
  "topFeeds": [],
  "url": "rsj.ningbo.gov.cn"
}
```
