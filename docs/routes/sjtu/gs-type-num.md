# 上海交通大学 - 研究生通知公告

## Coverage
`index-only`

## Route
- Namespace: `sjtu`
- Namespace Name: `上海交通大学`
- Route Path: `/gs/:type/:num?`
- Route Name: `研究生通知公告`
- Example: `/sjtu/gs/enroll/59`
- URL: `www.sjtu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `dzx-dzx`
- Source Location: `gs.ts`
- Source Module: `() => import('@/routes/sjtu/gs.ts')`

## Description
| 工作信息 | 招生信息 | 培养信息 | 学位学科 | 国际交流 | 创新工程 |
| -------- | -------- | -------- | -------- | -------- | -------- |
| work     | enroll   | train    | degree   | exchange | xsjy     |

  当`type`为`enroll`, `num`可选字段:

| 58       | 59       | 60         | 61       | 62       |
| -------- | -------- | ---------- | -------- | -------- |
| 博士招生 | 硕士招生 | 港澳台招生 | 考点信息 | 院系动态 |

  当`type`为`exchange`, `num`可选字段:

| 67             | 68             | 69             | 70             | 71             |
| -------------- | -------------- | -------------- | -------------- | -------------- |
| 国家公派研究生 | 国际化培养资助 | 校际交换与联培 | 交流与合作项目 | 项目招募与宣讲 |

## Parameters
- `type`: 类别
- `num`: 细分类别, 仅对`type`为`enroll`或`exchange`有效


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
  - `gs.sjtu.edu.cn/announcement/:type`
- `target`: `/gs/:type`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 工作信息 | 招生信息 | 培养信息 | 学位学科 | 国际交流 | 创新工程 |\n| -------- | -------- | -------- | -------- | -------- | -------- |\n| work     | enroll   | train    | degree   | exchange | xsjy     |\n\n  当`type`为`enroll`, `num`可选字段:\n\n| 58       | 59       | 60         | 61       | 62       |\n| -------- | -------- | ---------- | -------- | -------- |\n| 博士招生 | 硕士招生 | 港澳台招生 | 考点信息 | 院系动态 |\n\n  当`type`为`exchange`, `num`可选字段:\n\n| 67             | 68             | 69             | 70             | 71             |\n| -------------- | -------------- | -------------- | -------------- | -------------- |\n| 国家公派研究生 | 国际化培养资助 | 校际交换与联培 | 交流与合作项目 | 项目招募与宣讲 |",
  "example": "/sjtu/gs/enroll/59",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "gs.ts",
  "maintainers": [
    "dzx-dzx"
  ],
  "module": "() => import('@/routes/sjtu/gs.ts')",
  "name": "研究生通知公告",
  "parameters": {
    "num": "细分类别, 仅对`type`为`enroll`或`exchange`有效",
    "type": "类别"
  },
  "path": "/gs/:type/:num?",
  "radar": [
    {
      "source": [
        "gs.sjtu.edu.cn/announcement/:type"
      ],
      "target": "/gs/:type"
    }
  ]
}
```
