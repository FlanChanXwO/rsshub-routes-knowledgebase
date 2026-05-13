# 国家能源局 - 浙江省人民政府-全省政府网站统一搜索

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/zj/search/:websiteid?/:word/:cateid?`
- Route Name: `浙江省人民政府-全省政府网站统一搜索`
- Example: `/gov/zj/search`
- URL: `search.zj.gov.cn/jsearchfront/search.do`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `HaoyuLee`
- Source Location: `zj/search.ts`
- Source Module: `() => import('@/routes/gov/zj/search.ts')`

## Description
| 行政区域         | websiteid |
| ------------ | -- |
| 宁波市本级     | 330201000000000  |

| 搜索关键词         | word    |

| 信息分类         | cateid    |

| 排序类型         | sortType    |
| ------------ | -- |
| 按相关度     | 1  |
| 按时间     | 2  |

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
  "description": "\n| 行政区域         | websiteid |\n| ------------ | -- |\n| 宁波市本级     | 330201000000000  |\n\n| 搜索关键词         | word    |\n\n| 信息分类         | cateid    |\n\n| 排序类型         | sortType    |\n| ------------ | -- |\n| 按相关度     | 1  |\n| 按时间     | 2  |\n    ",
  "example": "/gov/zj/search",
  "location": "zj/search.ts",
  "maintainers": [
    "HaoyuLee"
  ],
  "module": "() => import('@/routes/gov/zj/search.ts')",
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
  "url": "search.zj.gov.cn/jsearchfront/search.do"
}
```
