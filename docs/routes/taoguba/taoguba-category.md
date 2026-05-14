# 淘股吧 - 淘股论坛

## Coverage
`index-only`

## Route
- Namespace: `taoguba`
- Namespace Name: `淘股吧`
- Route Path: `/taoguba/:category?`
- Route Name: `淘股论坛`
- Example: `/taoguba`
- URL: `tgb.cn`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 淘股论坛 | 社区总版 | 精华加油 | 网友点赞 |
| -------- | -------- | -------- | -------- |
| bbs      | zongban  | jinghua  | dianzan  |

## Parameters
- `id`: 分类，见下表，默认为社区总版


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| 淘股论坛 | 社区总版 | 精华加油 | 网友点赞 |\n| -------- | -------- | -------- | -------- |\n| bbs      | zongban  | jinghua  | dianzan  |",
  "example": "/taoguba",
  "heat": 257,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "淘股论坛",
  "parameters": {
    "id": "分类，见下表，默认为社区总版"
  },
  "path": "/:category?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "淘股吧股票论坛总版 - Powered by RSSHub",
      "errorAt": "2026-05-13T00:12:10.348Z",
      "errorMessage": "Cannot read properties of null (reading '0')\nCannot read properties of null (reading '0')\nFailed to fetch\n",
      "id": "101439531051305984",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.tgb.cn/zongban/",
      "title": "淘股吧股票论坛总版",
      "type": "feed",
      "url": "rsshub://taoguba"
    },
    {
      "description": "淘股吧散户炒股交流点赞牛贴 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "115961018043937792",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.tgb.cn/dianzan/",
      "title": "淘股吧散户炒股交流点赞牛贴",
      "type": "feed",
      "url": "rsshub://taoguba/dianzan"
    }
  ]
}
```
