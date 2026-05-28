# Hangzhou People's Government - 宁波市国资委-公告

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `Hangzhou People's Government`
- Route Path: `/gov/zj/ningbogzw-notice/:colId?`
- Route Name: `宁波市国资委-公告`
- Example: `/gov/zj/ningbogzw-notice/1229116730`
- URL: `gzw.ningbo.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `HaoyuLee`
- Source Location: `zj/ningbogzw-notice.ts`
- Source Module: `_None_`

## Description
| 公告类别                           | colId      |
| ---------------------------------- | ---------- |
| 首页 - 市属国企招聘信息 - 招聘公告 | 1229116730 |

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
  "description": "| 公告类别                           | colId      |\n| ---------------------------------- | ---------- |\n| 首页 - 市属国企招聘信息 - 招聘公告 | 1229116730 |",
  "example": "/gov/zj/ningbogzw-notice/1229116730",
  "heat": 2,
  "location": "zj/ningbogzw-notice.ts",
  "maintainers": [
    "HaoyuLee"
  ],
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
  "topFeeds": [
    {
      "description": "宁波市国资委 - Powered by RSSHub",
      "errorAt": "2025-10-11T09:02:36.785Z",
      "errorMessage": "Cannot read properties of null (reading 'map')\n",
      "id": "140564077109703680",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://gzw.ningbo.gov.cn/col/col1229116730/index.html",
      "title": "宁波市国资委",
      "type": "feed",
      "url": "rsshub://gov/zj/ningbogzw-notice"
    }
  ],
  "url": "gzw.ningbo.gov.cn"
}
```
