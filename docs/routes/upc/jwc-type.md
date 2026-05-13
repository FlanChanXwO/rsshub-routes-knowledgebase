# 中国石油大学（华东） - 教务处

## Coverage
`index-only`

## Route
- Namespace: `upc`
- Namespace Name: `中国石油大学（华东）`
- Route Path: `/jwc/:type?`
- Route Name: `教务处`
- Example: `/upc/jwc/tzgg`
- URL: `jwc.upc.edu.cn/tzgg/list.htm`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `sddzhyc`
- Source Location: `jwc.ts`
- Source Module: `() => import('@/routes/upc/jwc.ts')`

## Description
| 所有通知 | 教学·运行 | 学业·学籍 | 教学·研究 | 课程·教材 | 实践·教学 | 创新·创业 | 语言·文字 | 继续·教育 | 本科·招生 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| tzgg     | 18519    | 18520   | 18521    |    18522 |    18523 | 18524    |  yywwz   |  jxwjy   |   bkwzs  |

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
  "description": "| 所有通知 | 教学·运行 | 学业·学籍 | 教学·研究 | 课程·教材 | 实践·教学 | 创新·创业 | 语言·文字 | 继续·教育 | 本科·招生 |\n| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |\n| tzgg     | 18519    | 18520   | 18521    |    18522 |    18523 | 18524    |  yywwz   |  jxwjy   |   bkwzs  |",
  "example": "/upc/jwc/tzgg",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jwc.ts",
  "maintainers": [
    "sddzhyc"
  ],
  "module": "() => import('@/routes/upc/jwc.ts')",
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
  "url": "jwc.upc.edu.cn/tzgg/list.htm"
}
```
