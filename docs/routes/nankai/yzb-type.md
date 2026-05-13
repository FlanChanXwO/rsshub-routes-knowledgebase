# 南开大学 - 研究生招生网

## Coverage
`index-only`

## Route
- Namespace: `nankai`
- Namespace Name: `南开大学`
- Route Path: `/yzb/:type?`
- Route Name: `研究生招生网`
- Example: `/nankai/yzb/5509`
- URL: `yzb.nankai.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `sddzhyc`
- Source Location: `yzb.ts`
- Source Module: `() => import('@/routes/nankai/yzb.ts')`

## Description
| 硕士招生 | 博士招生 | 港澳台研究生最新信息 |
| -------- | -------- | -------- |
| 5509     | 2552    | 2562   |

## Parameters
- `type`: 栏目名（若为空则默认为“硕士招生”）


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `yzb.nankai.edu.cn`
  - `yzb.nankai.edu.cn/:type/list.htm`
- `target`: `/yzb/:type?`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 硕士招生 | 博士招生 | 港澳台研究生最新信息 |\n| -------- | -------- | -------- |\n| 5509     | 2552    | 2562   |",
  "example": "/nankai/yzb/5509",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "yzb.ts",
  "maintainers": [
    "sddzhyc"
  ],
  "module": "() => import('@/routes/nankai/yzb.ts')",
  "name": "研究生招生网",
  "parameters": {
    "type": "栏目名（若为空则默认为“硕士招生”）"
  },
  "path": "/yzb/:type?",
  "radar": [
    {
      "source": [
        "yzb.nankai.edu.cn",
        "yzb.nankai.edu.cn/:type/list.htm"
      ],
      "target": "/yzb/:type?"
    }
  ],
  "url": "yzb.nankai.edu.cn"
}
```
