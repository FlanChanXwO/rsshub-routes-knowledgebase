# 国家能源局 - 天津人才工作网-公告

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/tianjin/tjrcgzw-notice/:cate/:subCate`
- Route Name: `天津人才工作网-公告`
- Example: `/gov/tianjin/tjrcgzw-notice/rczc/sjrczc/`
- URL: `hrss.tj.gov.cn/ztzl/ztzl1/tjrcgzw/`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `HaoyuLee`
- Source Location: `tianjin/tjrcgzw.ts`
- Source Module: `() => import('@/routes/gov/tianjin/tjrcgzw.ts')`

## Description
_None_

## Parameters
- `channelId`: 公告分类id、详细信息点击源网站https://hrss.tj.gov.cn/ztzl/ztzl1/tjrcgzw/请求中寻找


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `hrss.tj.gov.cn/ztzl/ztzl1/tjrcgzw/`
- `target`: `/tianjin/tjrcgzw-notice/:cate/:subCate`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gov/tianjin/tjrcgzw-notice/rczc/sjrczc/",
  "location": "tianjin/tjrcgzw.ts",
  "maintainers": [
    "HaoyuLee"
  ],
  "module": "() => import('@/routes/gov/tianjin/tjrcgzw.ts')",
  "name": "天津人才工作网-公告",
  "parameters": {
    "channelId": "公告分类id、详细信息点击源网站https://hrss.tj.gov.cn/ztzl/ztzl1/tjrcgzw/请求中寻找"
  },
  "path": "/tianjin/tjrcgzw-notice/:cate/:subCate",
  "radar": [
    {
      "source": [
        "hrss.tj.gov.cn/ztzl/ztzl1/tjrcgzw/"
      ],
      "target": "/tianjin/tjrcgzw-notice/:cate/:subCate"
    }
  ],
  "url": "hrss.tj.gov.cn/ztzl/ztzl1/tjrcgzw/"
}
```
