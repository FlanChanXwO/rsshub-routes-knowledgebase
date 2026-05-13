# 新浪 - 滚动新闻

## Coverage
`index-only`

## Route
- Namespace: `sina`
- Namespace Name: `新浪`
- Route Path: `/rollnews/:lid?`
- Route Name: `滚动新闻`
- Example: `/sina/rollnews`
- URL: `finance.sina.com.cn`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `xyqfer`
- Source Location: `rollnews.ts`
- Source Module: `() => import('@/routes/sina/rollnews.ts')`

## Description
| 全部 | 国内 | 国际 | 社会 | 体育 | 娱乐 | 军事 | 科技 | 财经 | 股市 | 美股 |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| 2509 | 2510 | 2511 | 2669 | 2512 | 2513 | 2514 | 2515 | 2516 | 2517 | 2518 |

## Parameters
- `lid`: 分区 id，可在 URL 中找到，默认为 `2509`


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
    "new-media"
  ],
  "description": "| 全部 | 国内 | 国际 | 社会 | 体育 | 娱乐 | 军事 | 科技 | 财经 | 股市 | 美股 |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |\n| 2509 | 2510 | 2511 | 2669 | 2512 | 2513 | 2514 | 2515 | 2516 | 2517 | 2518 |",
  "example": "/sina/rollnews",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "rollnews.ts",
  "maintainers": [
    "xyqfer"
  ],
  "module": "() => import('@/routes/sina/rollnews.ts')",
  "name": "滚动新闻",
  "parameters": {
    "lid": "分区 id，可在 URL 中找到，默认为 `2509`"
  },
  "path": "/rollnews/:lid?"
}
```
