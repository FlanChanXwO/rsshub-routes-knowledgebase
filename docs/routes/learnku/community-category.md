# LearnKu - 社区

## Coverage
`index-only`

## Route
- Namespace: `learnku`
- Namespace Name: `LearnKu`
- Route Path: `/:community/:category?`
- Route Name: `社区`
- Example: `/learnku/laravel/qa`
- URL: `learnku.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `kayw-geek`
- Source Location: `topic.tsx`
- Source Module: `() => import('@/routes/learnku/topic.tsx')`

## Description
| 招聘 | 翻译         | 问答 | 链接  |
| ---- | ------------ | ---- | ----- |
| jobs | translations | qa   | links |

## Parameters
- `community`: 社区 标识，可在 <https://learnku.com/communities> 找到
- `category`: 分类，如果不传 `category` 则获取全部分类


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
  - `learnku.com/:community`
- `target`: `/:community`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "| 招聘 | 翻译         | 问答 | 链接  |\n| ---- | ------------ | ---- | ----- |\n| jobs | translations | qa   | links |",
  "example": "/learnku/laravel/qa",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "topic.tsx",
  "maintainers": [
    "kayw-geek"
  ],
  "module": "() => import('@/routes/learnku/topic.tsx')",
  "name": "社区",
  "parameters": {
    "category": "分类，如果不传 `category` 则获取全部分类",
    "community": "社区 标识，可在 <https://learnku.com/communities> 找到"
  },
  "path": "/:community/:category?",
  "radar": [
    {
      "source": [
        "learnku.com/:community"
      ],
      "target": "/:community"
    }
  ]
}
```
