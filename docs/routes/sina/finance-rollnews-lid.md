# 新浪 - 财经－滚动新闻

## Coverage
`index-only`

## Route
- Namespace: `sina`
- Namespace Name: `新浪`
- Route Path: `/finance/rollnews/:lid?`
- Route Name: `财经－滚动新闻`
- Example: `/sina/finance/rollnews`
- URL: `finance.sina.com.cn/roll`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `betterandbetterii`
- Source Location: `finance/rollnews.ts`
- Source Module: `() => import('@/routes/sina/finance/rollnews.ts')`

## Description
| 财经 | 股市 | 美股 | 中国概念股 | 港股 | 研究报告 | 全球市场 | 外汇 |
| ---- | ---- | ---- | ---------- | ---- | -------- | -------- | ---- |
| 2519 | 2671 | 2672 | 2673       | 2674 | 2675     | 2676     | 2487 |

## Parameters
- `lid`: 分区 id，见下表，默认为 `2519`


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
  - `finance.sina.com.cn/roll`
  - `finance.sina.com.cn/`
- `target`: `/finance/rollnews`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 财经 | 股市 | 美股 | 中国概念股 | 港股 | 研究报告 | 全球市场 | 外汇 |\n| ---- | ---- | ---- | ---------- | ---- | -------- | -------- | ---- |\n| 2519 | 2671 | 2672 | 2673       | 2674 | 2675     | 2676     | 2487 |",
  "example": "/sina/finance/rollnews",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "finance/rollnews.ts",
  "maintainers": [
    "betterandbetterii"
  ],
  "module": "() => import('@/routes/sina/finance/rollnews.ts')",
  "name": "财经－滚动新闻",
  "parameters": {
    "lid": "分区 id，见下表，默认为 `2519`"
  },
  "path": "/finance/rollnews/:lid?",
  "radar": [
    {
      "source": [
        "finance.sina.com.cn/roll",
        "finance.sina.com.cn/"
      ],
      "target": "/finance/rollnews"
    }
  ],
  "url": "finance.sina.com.cn/roll"
}
```
