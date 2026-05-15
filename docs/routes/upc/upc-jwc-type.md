# 中国石油大学（华东） - 教务处

## Coverage
`index-only`

## Route
- Namespace: `upc`
- Namespace Name: `中国石油大学（华东）`
- Route Path: `/upc/jwc/:type?`
- Route Name: `教务处`
- Example: `/upc/jwc/tzgg`
- URL: `jwc.upc.edu.cn/tzgg/list.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `sddzhyc`
- Source Location: `jwc.ts`
- Source Module: `_None_`

## Description
| 所有通知 | 教学・运行 | 学业・学籍 | 教学・研究 | 课程・教材 | 实践・教学 | 创新・创业 | 语言・文字 | 继续・教育 | 本科・招生 |
| -------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- |
| tzgg     | 18519      | 18520      | 18521      | 18522      | 18523      | 18524      | yywwz      | jxwjy      | bkwzs      |

## Parameters
- `type`: 分类，见下表，其值与对应网页url路径参数一致，默认为所有通知


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `jwc.upc.edu.cn`
  - `jwc.upc.edu.cn/:type/list.htm`
- `target`: `/jwc/:type?`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 所有通知 | 教学・运行 | 学业・学籍 | 教学・研究 | 课程・教材 | 实践・教学 | 创新・创业 | 语言・文字 | 继续・教育 | 本科・招生 |\n| -------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- |\n| tzgg     | 18519      | 18520      | 18521      | 18522      | 18523      | 18524      | yywwz      | jxwjy      | bkwzs      |",
  "example": "/upc/jwc/tzgg",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "jwc.ts",
  "maintainers": [
    "sddzhyc"
  ],
  "name": "教务处",
  "parameters": {
    "type": "分类，见下表，其值与对应网页url路径参数一致，默认为所有通知"
  },
  "path": "/jwc/:type?",
  "radar": [
    {
      "source": [
        "jwc.upc.edu.cn",
        "jwc.upc.edu.cn/:type/list.htm"
      ],
      "target": "/jwc/:type?"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "通知公告-教务处通知-中国石油大学（华东） - Powered by RSSHub",
      "errorAt": "2026-01-03T09:41:43.595Z",
      "errorMessage": "[GET] \"https://jwc.upc.edu.cn/tzgg/list.htm\": <no response> fetch failed\n",
      "id": "150901151398739968",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jwc.upc.edu.cn/tzgg/list.htm",
      "title": "通知公告-教务处通知-中国石油大学（华东）",
      "type": "feed",
      "url": "rsshub://upc/jwc/tzgg"
    }
  ],
  "url": "jwc.upc.edu.cn/tzgg/list.htm"
}
```
