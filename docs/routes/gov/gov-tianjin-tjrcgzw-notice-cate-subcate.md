# Hangzhou People's Government - 天津人才工作网-公告

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `Hangzhou People's Government`
- Route Path: `/gov/tianjin/tjrcgzw-notice/:cate/:subCate`
- Route Name: `天津人才工作网-公告`
- Example: `/gov/tianjin/tjrcgzw-notice/rczc/sjrczc/`
- URL: `hrss.tj.gov.cn/ztzl/ztzl1/tjrcgzw/`
- Language: `_None_`
- Categories: `government`
- Maintainers: `HaoyuLee`
- Source Location: `tianjin/tjrcgzw.ts`
- Source Module: `_None_`

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
  "heat": 0,
  "location": "tianjin/tjrcgzw.ts",
  "maintainers": [
    "HaoyuLee"
  ],
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
  "topFeeds": [],
  "url": "hrss.tj.gov.cn/ztzl/ztzl1/tjrcgzw/"
}
```
