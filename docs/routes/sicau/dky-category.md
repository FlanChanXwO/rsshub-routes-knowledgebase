# 四川农业大学 - 动物科技学院

## Coverage
`index-only`

## Route
- Namespace: `sicau`
- Namespace Name: `四川农业大学`
- Route Path: `/dky/:category?`
- Route Name: `动物科技学院`
- Example: `/sicau/dky/tzgg`
- URL: `dky.sicau.edu.cn/`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `nczitzk`
- Source Location: `dky.ts`
- Source Module: `() => import('@/routes/sicau/dky.ts')`

## Description
| 通知公告 | 学院动态 | 教学管理 | 动科大讲堂 | 就业信息 |
| -------- | -------- | -------- | ---------- | -------- |
| tzgg     | xydt     | jxgl     | dkdjt      | zpxx     |

## Parameters
- `category`: 分类，见下表，默认为通知公告


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
  - `dky.sicau.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告 | 学院动态 | 教学管理 | 动科大讲堂 | 就业信息 |\n| -------- | -------- | -------- | ---------- | -------- |\n| tzgg     | xydt     | jxgl     | dkdjt      | zpxx     |",
  "example": "/sicau/dky/tzgg",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "dky.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/sicau/dky.ts')",
  "name": "动物科技学院",
  "parameters": {
    "category": "分类，见下表，默认为通知公告"
  },
  "path": "/dky/:category?",
  "radar": [
    {
      "source": [
        "dky.sicau.edu.cn/"
      ]
    }
  ],
  "url": "dky.sicau.edu.cn/"
}
```
