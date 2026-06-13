# 雪球 - 股票信息

## Coverage
`index-only`

## Route
- Namespace: `xueqiu`
- Namespace Name: `雪球`
- Route Path: `/xueqiu/stock_info/:id/:type?`
- Route Name: `股票信息`
- Example: `/xueqiu/stock_info/SZ000002`
- URL: `danjuanapp.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `YuYang`
- Source Location: `stock-info.ts`
- Source Module: `_None_`

## Description
| 公告         | 新闻 | 研报     |
| ------------ | ---- | -------- |
| announcement | news | research |

## Parameters
- `id`: 股票代码（需要带上交易所）
- `type`: 动态的类型, 不填则为股票公告


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
  - `xueqiu.com/S/:id`
  - `xueqiu.com/s/:id`
- `target`: `/stock_info/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| 公告         | 新闻 | 研报     |\n| ------------ | ---- | -------- |\n| announcement | news | research |",
  "example": "/xueqiu/stock_info/SZ000002",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 29,
  "location": "stock-info.ts",
  "maintainers": [
    "YuYang"
  ],
  "name": "股票信息",
  "parameters": {
    "id": "股票代码（需要带上交易所）",
    "type": "动态的类型, 不填则为股票公告"
  },
  "path": "/stock_info/:id/:type?",
  "radar": [
    {
      "source": [
        "xueqiu.com/S/:id",
        "xueqiu.com/s/:id"
      ],
      "target": "/stock_info/:id"
    }
  ],
  "topFeeds": [
    {
      "description": "兆易创新 - 自选股新闻 - Powered by RSSHub",
      "errorAt": "2024-11-22T14:04:03.723Z",
      "errorMessage": "Cannot read properties of undefined (reading 'map')\n",
      "id": "64923928046286858",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xueqiu.com/S/SH603986",
      "title": "SH603986 兆易创新 - 自选股新闻",
      "type": "feed",
      "url": "rsshub://xueqiu/stock_info/SH603986/news"
    },
    {
      "description": "豪威集团 - 公告 - Powered by RSSHub",
      "errorAt": "2026-05-22T21:11:53.408Z",
      "errorMessage": "browserType.connect: WebSocket error: wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.59                          ║\n║   - client version: v1.60                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\nCall log:\n  - <ws connecting> wss://cloudflare-patchright.rss3.workers.dev/playwright\n  - <ws unexpected response> wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.59                          ║\n║   - client version: v1.60                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\n  - <ws error> wss://cloudflare-patchright.rss3.workers.dev/playwright error WebSocket was closed before the connection was established\n  - <ws connect error> wss://cloudflare-patchright.rss3.workers.dev/playwright WebSocket was closed before the connection was established\n  - <ws disconnected> wss://cloudflare-patchright.rss3.workers.dev/playwright code=1006 reason=\n\n",
      "id": "64923928046286863",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xueqiu.com/S/SH603501",
      "title": "SH603501 豪威集团 - 公告",
      "type": "feed",
      "url": "rsshub://xueqiu/stock_info/SH603501"
    }
  ]
}
```
