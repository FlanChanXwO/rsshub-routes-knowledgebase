# 国家能源局 - 浙江省人民政府-全省政府网站统一搜索

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/gov/zj/search/:websiteid?/:word/:cateid?`
- Route Name: `浙江省人民政府-全省政府网站统一搜索`
- Example: `/gov/zj/search`
- URL: `search.zj.gov.cn/jsearchfront/search.do`
- Language: `_None_`
- Categories: `government`
- Maintainers: `HaoyuLee`
- Source Location: `zj/search.ts`
- Source Module: `_None_`

## Description
| 行政区域   | websiteid       |
| ---------- | --------------- |
| 宁波市本级 | 330201000000000 |

\| 搜索关键词         | word    |

\| 信息分类         | cateid    |

| 排序类型 | sortType |
| -------- | -------- |
| 按相关度 | 1        |
| 按时间   | 2        |

## Parameters
- `websiteid`: 搜索范围-全省、各市各区、详细信息点击源网站https://www.zj.gov.cn/请求中寻找
- `word`: 搜索关键词-默认：人才
- `cateid`: 信息分类-默认：658（全部）
- `sortType`: 排序类型-默认：2（按时间）


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `search.zj.gov.cn/jsearchfront/search.do`
- `target`: `/zj/search/:websiteid?/:word/:cateid?`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 行政区域   | websiteid       |\n| ---------- | --------------- |\n| 宁波市本级 | 330201000000000 |\n\n\\| 搜索关键词         | word    |\n\n\\| 信息分类         | cateid    |\n\n| 排序类型 | sortType |\n| -------- | -------- |\n| 按相关度 | 1        |\n| 按时间   | 2        |",
  "example": "/gov/zj/search",
  "heat": 2,
  "location": "zj/search.ts",
  "maintainers": [
    "HaoyuLee"
  ],
  "name": "浙江省人民政府-全省政府网站统一搜索",
  "parameters": {
    "cateid": "信息分类-默认：658（全部）",
    "sortType": "排序类型-默认：2（按时间）",
    "websiteid": "搜索范围-全省、各市各区、详细信息点击源网站https://www.zj.gov.cn/请求中寻找",
    "word": "搜索关键词-默认：人才"
  },
  "path": "/zj/search/:websiteid?/:word/:cateid?",
  "radar": [
    {
      "source": [
        "search.zj.gov.cn/jsearchfront/search.do"
      ],
      "target": "/zj/search/:websiteid?/:word/:cateid?"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "浙江省人民政府-全省政府网站统一搜索 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "139849368771468288",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://search.zj.gov.cn/jsearchfront/search.do",
      "title": "浙江省人民政府-全省政府网站统一搜索",
      "type": "feed",
      "url": "rsshub://gov/zj/search"
    }
  ],
  "url": "search.zj.gov.cn/jsearchfront/search.do"
}
```
