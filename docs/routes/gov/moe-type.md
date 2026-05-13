# 国家能源局 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/moe/:type`
- Route Name: `新闻`
- Example: `/gov/moe/policy_anal`
- URL: `www.nea.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `Crawler995`
- Source Location: `moe/moe.ts`
- Source Module: `() => import('@/routes/gov/moe/moe.ts')`

## Description
|   政策解读   |   最新文件   | 公告公示 |      教育部简报     |     教育要闻     |
| :----------: | :----------: | :------: | :-----------------: | :--------------: |
| policy_anal | newest_file |  notice  | edu_ministry_news | edu_focus_news |

## Parameters
- `type`: 分类名


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "|   政策解读   |   最新文件   | 公告公示 |      教育部简报     |     教育要闻     |\n| :----------: | :----------: | :------: | :-----------------: | :--------------: |\n| policy_anal | newest_file |  notice  | edu_ministry_news | edu_focus_news |",
  "example": "/gov/moe/policy_anal",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "moe/moe.ts",
  "maintainers": [
    "Crawler995"
  ],
  "module": "() => import('@/routes/gov/moe/moe.ts')",
  "name": "新闻",
  "parameters": {
    "type": "分类名"
  },
  "path": "/moe/:type"
}
```
