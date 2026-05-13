# 中国教育考试网 - 日本语能力测试 JLPT 通知

## Coverage
`index-only`

## Route
- Namespace: `neea`
- Namespace Name: `中国教育考试网`
- Route Path: `/jlpt`
- Route Name: `日本语能力测试 JLPT 通知`
- Example: `/neea/jlpt`
- URL: `jlpt.neea.cn`
- Language: `zh-CN`
- Categories: `study`
- Maintainers: `nczitzk`
- Source Location: `jlpt.ts`
- Source Module: `() => import('@/routes/neea/jlpt.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `jlpt.neea.cn`
- `target`: `/jlpt`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "example": "/neea/jlpt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "jlpt.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/neea/jlpt.ts')",
  "name": "日本语能力测试 JLPT 通知",
  "path": "/jlpt",
  "radar": [
    {
      "source": [
        "jlpt.neea.cn"
      ],
      "target": "/jlpt"
    }
  ],
  "url": "jlpt.neea.cn",
  "view": 0
}
```
