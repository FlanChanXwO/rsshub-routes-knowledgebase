# 新浪 - 财经－国內

## Coverage
`index-only`

## Route
- Namespace: `sina`
- Namespace Name: `新浪`
- Route Path: `/finance/china/:lid?`
- Route Name: `财经－国內`
- Example: `/sina/finance/china`
- URL: `finance.sina.com.cn/china`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `yubinbai`
- Source Location: `finance/china.ts`
- Source Module: `() => import('@/routes/sina/finance/china.ts')`

## Description
| 国内滚动 | 宏观经济 | 金融新闻 | 地方经济 | 部委动态 | 今日财经 TOP10 |
| -------- | -------- | -------- | -------- | -------- | -------------- |
| 1686     | 1687     | 1690     | 1688     | 1689     | 3231           |

## Parameters
- `lid`: 分区 id，见下表，默认为 `1686`


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
  - `finance.sina.com.cn/china`
  - `finance.sina.com.cn/`
- `target`: `/finance/china`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 国内滚动 | 宏观经济 | 金融新闻 | 地方经济 | 部委动态 | 今日财经 TOP10 |\n| -------- | -------- | -------- | -------- | -------- | -------------- |\n| 1686     | 1687     | 1690     | 1688     | 1689     | 3231           |",
  "example": "/sina/finance/china",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "finance/china.ts",
  "maintainers": [
    "yubinbai"
  ],
  "module": "() => import('@/routes/sina/finance/china.ts')",
  "name": "财经－国內",
  "parameters": {
    "lid": "分区 id，见下表，默认为 `1686`"
  },
  "path": "/finance/china/:lid?",
  "radar": [
    {
      "source": [
        "finance.sina.com.cn/china",
        "finance.sina.com.cn/"
      ],
      "target": "/finance/china"
    }
  ],
  "url": "finance.sina.com.cn/china"
}
```
