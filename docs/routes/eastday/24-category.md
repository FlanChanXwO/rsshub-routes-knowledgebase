# 东方网 - 24 小时热闻

## Coverage
`index-only`

## Route
- Namespace: `eastday`
- Namespace Name: `东方网`
- Route Path: `/24/:category?`
- Route Name: `24 小时热闻`
- Example: `/eastday/24`
- URL: `mini.eastday.com/`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `24.ts`
- Source Module: `() => import('@/routes/eastday/24.ts')`

## Description
| 推荐 | 社会 | 娱乐 | 国际 | 军事 |
| ---- | ---- | ---- | ---- | ---- |

| 养生 | 汽车 | 体育 | 财经 | 游戏 |
| ---- | ---- | ---- | ---- | ---- |

| 科技 | 国内 | 宠物 | 情感 | 人文 | 教育 |
| ---- | ---- | ---- | ---- | ---- | ---- |

## Parameters
- `category`: 分类，见下表，默认为社会


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
  - `mini.eastday.com/`
- `target`: `/24`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 推荐 | 社会 | 娱乐 | 国际 | 军事 |\n| ---- | ---- | ---- | ---- | ---- |\n\n| 养生 | 汽车 | 体育 | 财经 | 游戏 |\n| ---- | ---- | ---- | ---- | ---- |\n\n| 科技 | 国内 | 宠物 | 情感 | 人文 | 教育 |\n| ---- | ---- | ---- | ---- | ---- | ---- |",
  "example": "/eastday/24",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "24.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/eastday/24.ts')",
  "name": "24 小时热闻",
  "parameters": {
    "category": "分类，见下表，默认为社会"
  },
  "path": "/24/:category?",
  "radar": [
    {
      "source": [
        "mini.eastday.com/"
      ],
      "target": "/24"
    }
  ],
  "url": "mini.eastday.com/"
}
```
