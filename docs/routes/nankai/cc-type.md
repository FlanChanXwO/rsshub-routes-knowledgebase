# 南开大学 - 计算机学院

## Coverage
`index-only`

## Route
- Namespace: `nankai`
- Namespace Name: `南开大学`
- Route Path: `/cc/:type?`
- Route Name: `计算机学院`
- Example: `/nankai/cc/13291`
- URL: `cc.nankai.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `vicguo0724`
- Source Location: `cc-notice.ts`
- Source Module: `() => import('@/routes/nankai/cc-notice.ts')`

## Description
| 最新动态 | 学院公告 | 学生工作通知 | 科研信息 | 本科生教学 | 党团园地 | 研究生招生 | 研究生教学 | 境外交流 |
| -------- | -------- | ---------- | -------- | ---------- | -------- | ---------- | ---------- | -------- |
| 13291    | 13292    | 13293      | 13294    | 13295      | 13296    | 13297      | 13298      | 13299    |

## Parameters
- `type`: 栏目编号（若为空则默认为"最新动态"）


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
  - `cc.nankai.edu.cn`
  - `cc.nankai.edu.cn/:type/list.htm`
- `target`: `/cc/:type?`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 最新动态 | 学院公告 | 学生工作通知 | 科研信息 | 本科生教学 | 党团园地 | 研究生招生 | 研究生教学 | 境外交流 |\n| -------- | -------- | ---------- | -------- | ---------- | -------- | ---------- | ---------- | -------- |\n| 13291    | 13292    | 13293      | 13294    | 13295      | 13296    | 13297      | 13298      | 13299    |",
  "example": "/nankai/cc/13291",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "cc-notice.ts",
  "maintainers": [
    "vicguo0724"
  ],
  "module": "() => import('@/routes/nankai/cc-notice.ts')",
  "name": "计算机学院",
  "parameters": {
    "type": "栏目编号（若为空则默认为\"最新动态\"）"
  },
  "path": "/cc/:type?",
  "radar": [
    {
      "source": [
        "cc.nankai.edu.cn",
        "cc.nankai.edu.cn/:type/list.htm"
      ],
      "target": "/cc/:type?"
    }
  ],
  "url": "cc.nankai.edu.cn"
}
```
