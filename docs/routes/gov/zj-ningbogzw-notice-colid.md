# 国家能源局 - 宁波市国资委-公告

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/zj/ningbogzw-notice/:colId?`
- Route Name: `宁波市国资委-公告`
- Example: `/gov/zj/ningbogzw-notice/1229116730`
- URL: `gzw.ningbo.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `HaoyuLee`
- Source Location: `zj/ningbogzw-notice.ts`
- Source Module: `() => import('@/routes/gov/zj/ningbogzw-notice.ts')`

## Description
| 公告类别         | colId |
| ------------ | -- |
| 首页-市属国企招聘信息-招聘公告     | 1229116730  |

## Parameters
- `colId`: 公告分类id、详细信息点击源网站http://gzw.ningbo.gov.cn/请求中寻找


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `gzw.ningbo.gov.cn/col/col1229116730/index.html`
- `target`: `/zj/ningbogzw-notice/:colId?`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "\n| 公告类别         | colId |\n| ------------ | -- |\n| 首页-市属国企招聘信息-招聘公告     | 1229116730  |\n    ",
  "example": "/gov/zj/ningbogzw-notice/1229116730",
  "location": "zj/ningbogzw-notice.ts",
  "maintainers": [
    "HaoyuLee"
  ],
  "module": "() => import('@/routes/gov/zj/ningbogzw-notice.ts')",
  "name": "宁波市国资委-公告",
  "parameters": {
    "colId": "公告分类id、详细信息点击源网站http://gzw.ningbo.gov.cn/请求中寻找"
  },
  "path": "/zj/ningbogzw-notice/:colId?",
  "radar": [
    {
      "source": [
        "gzw.ningbo.gov.cn/col/col1229116730/index.html"
      ],
      "target": "/zj/ningbogzw-notice/:colId?"
    }
  ],
  "url": "gzw.ningbo.gov.cn"
}
```
