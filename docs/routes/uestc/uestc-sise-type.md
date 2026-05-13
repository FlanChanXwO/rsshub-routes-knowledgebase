# 电子科技大学 - 信息与软件工程学院

## Coverage
`index-only`

## Route
- Namespace: `uestc`
- Namespace Name: `电子科技大学`
- Route Path: `/uestc/sise/:type?`
- Route Name: `信息与软件工程学院`
- Example: `/uestc/sise/1`
- URL: `sise.uestc.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Yadomin, mobyw`
- Source Location: `sise.ts`
- Source Module: `_None_`

## Description
| 最新 | 院办 | 学生科 | 教务科 | 研管科 | 组织 | 人事 | 实践教育中心 | Int'I |
| ---- | ---- | ------ | ------ | ------ | ---- | ---- | ------------ | ----- |
| 1    | 2    | 3      | 4      | 5      | 6    | 7    | 8            | 9     |

## Parameters
- `type`: 默认为 `1`


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `sise.uestc.edu.cn/`
- `target`: `/sise`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 最新 | 院办 | 学生科 | 教务科 | 研管科 | 组织 | 人事 | 实践教育中心 | Int'I |\n| ---- | ---- | ------ | ------ | ------ | ---- | ---- | ------------ | ----- |\n| 1    | 2    | 3      | 4      | 5      | 6    | 7    | 8            | 9     |",
  "example": "/uestc/sise/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "sise.ts",
  "maintainers": [
    "Yadomin",
    "mobyw"
  ],
  "name": "信息与软件工程学院",
  "parameters": {
    "type": "默认为 `1`"
  },
  "path": "/sise/:type?",
  "radar": [
    {
      "source": [
        "sise.uestc.edu.cn/"
      ],
      "target": "/sise"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "sise.uestc.edu.cn/"
}
```
