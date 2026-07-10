# 广州市人民政府 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `gov/gz`
- Namespace Name: `广州市人民政府`
- Route Path: `/gov/gz/xw/:category`
- Route Name: `新闻`
- Example: `/gov/gz/xw/gzyw`
- URL: `www.gz.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `drgnchan`
- Source Location: `xw.ts`
- Source Module: `_None_`

## Description
| 广州要闻 | 今日头条 | 通知公告 |
| -------- | -------- | -------- |
| gzyw     | jrtt     | tzgg     |

## Parameters
- `category`: 新闻分类


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.gz.gov.cn/xw/:category`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 广州要闻 | 今日头条 | 通知公告 |\n| -------- | -------- | -------- |\n| gzyw     | jrtt     | tzgg     |",
  "example": "/gov/gz/xw/gzyw",
  "heat": 0,
  "location": "xw.ts",
  "maintainers": [
    "drgnchan"
  ],
  "name": "新闻",
  "parameters": {
    "category": "新闻分类"
  },
  "path": "/xw/:category",
  "radar": [
    {
      "source": [
        "www.gz.gov.cn/xw/:category"
      ]
    }
  ],
  "topFeeds": []
}
```
