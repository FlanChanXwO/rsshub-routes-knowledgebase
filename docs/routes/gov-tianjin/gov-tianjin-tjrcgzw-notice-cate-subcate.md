# 天津市人民政府 - 人才工作网-公告

## Coverage
`index-only`

## Route
- Namespace: `gov/tianjin`
- Namespace Name: `天津市人民政府`
- Route Path: `/gov/tianjin/tjrcgzw-notice/:cate/:subCate`
- Route Name: `人才工作网-公告`
- Example: `/gov/tianjin/tjrcgzw-notice/rczc/sjrczc/`
- URL: `hrss.tj.gov.cn/ztzl/ztzl1/tjrcgzw/`
- Language: `_None_`
- Categories: `government`
- Maintainers: `HaoyuLee`
- Source Location: `tjrcgzw.ts`
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
- `target`: `/tjrcgzw-notice/:cate/:subCate`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gov/tianjin/tjrcgzw-notice/rczc/sjrczc/",
  "heat": 0,
  "location": "tjrcgzw.ts",
  "maintainers": [
    "HaoyuLee"
  ],
  "name": "人才工作网-公告",
  "parameters": {
    "channelId": "公告分类id、详细信息点击源网站https://hrss.tj.gov.cn/ztzl/ztzl1/tjrcgzw/请求中寻找"
  },
  "path": "/tjrcgzw-notice/:cate/:subCate",
  "radar": [
    {
      "source": [
        "hrss.tj.gov.cn/ztzl/ztzl1/tjrcgzw/"
      ],
      "target": "/tjrcgzw-notice/:cate/:subCate"
    }
  ],
  "topFeeds": [],
  "url": "hrss.tj.gov.cn/ztzl/ztzl1/tjrcgzw/"
}
```
