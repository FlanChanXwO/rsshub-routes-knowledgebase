# 南开大学 - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `nankai`
- Namespace Name: `南开大学`
- Route Path: `/graduate/:type?`
- Route Name: `研究生院`
- Example: `/nankai/graduate/zxdt`
- URL: `graduate.nankai.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `ladeng07`
- Source Location: `graduate-notice.ts`
- Source Module: `() => import('@/routes/nankai/graduate-notice.ts')`

## Description
| 最新动态 | 综合信息 | 招生工作 | 培养管理 | 国际交流 | 学科建设 | 学位管理 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| zxdt     | 82       | 83       | 84       | 85       | 86       | 87       |

## Parameters
- `type`: 栏目编号（若为空则默认为"zxdt"）


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
  - `graduate.nankai.edu.cn`
  - `graduate.nankai.edu.cn/:type/list.htm`
- `target`: `/graduate/:type?`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 最新动态 | 综合信息 | 招生工作 | 培养管理 | 国际交流 | 学科建设 | 学位管理 |\n| -------- | -------- | -------- | -------- | -------- | -------- | -------- |\n| zxdt     | 82       | 83       | 84       | 85       | 86       | 87       |",
  "example": "/nankai/graduate/zxdt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "graduate-notice.ts",
  "maintainers": [
    "ladeng07"
  ],
  "module": "() => import('@/routes/nankai/graduate-notice.ts')",
  "name": "研究生院",
  "parameters": {
    "type": "栏目编号（若为空则默认为\"zxdt\"）"
  },
  "path": "/graduate/:type?",
  "radar": [
    {
      "source": [
        "graduate.nankai.edu.cn",
        "graduate.nankai.edu.cn/:type/list.htm"
      ],
      "target": "/graduate/:type?"
    }
  ],
  "url": "graduate.nankai.edu.cn"
}
```
