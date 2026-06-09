# JavDB - 片商

## Coverage
`index-only`

## Route
- Namespace: `javdb`
- Namespace Name: `JavDB`
- Route Path: `/javdb/makers/:id/:filter?`
- Route Name: `片商`
- Example: `/javdb/makers/7R`
- URL: `javdb.com/`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `makers.ts`
- Source Module: `_None_`

## Description
| 全部 | 可播放   | 單體作品 | 可下載   | 字幕  | 預覽圖  |
| ---- | -------- | -------- | -------- | ----- | ------- |
|      | playable | single   | download | cnsub | preview |

所有片商编号参见 [片商庫](https://javdb.com/makers)

## Parameters
- `id`: 编号，可在片商页 URL 中找到
- `filter`: 过滤，见下表，默认为 `全部`


## Features
- `requireConfig`: [{"description": "JavDB登陆后的session值，可在控制台的cookie下查找 `_jdb_session` 的值，即可获取", "name": "JAVDB_SESSION", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `javdb.com/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "| 全部 | 可播放   | 單體作品 | 可下載   | 字幕  | 預覽圖  |\n| ---- | -------- | -------- | -------- | ----- | ------- |\n|      | playable | single   | download | cnsub | preview |\n\n所有片商编号参见 [片商庫](https://javdb.com/makers)",
  "example": "/javdb/makers/7R",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "JavDB登陆后的session值，可在控制台的cookie下查找 `_jdb_session` 的值，即可获取",
        "name": "JAVDB_SESSION",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 383,
  "location": "makers.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "片商",
  "parameters": {
    "filter": "过滤，见下表，默认为 `全部`",
    "id": "编号，可在片商页 URL 中找到"
  },
  "path": "/makers/:id/:filter?",
  "radar": [
    {
      "source": [
        "javdb.com/"
      ],
      "target": ""
    }
  ],
  "topFeeds": [
    {
      "description": "S1 NO.1 STYLE - JavDB - Powered by RSSHub",
      "errorAt": "2026-05-22T21:31:08.082Z",
      "errorMessage": "Failed to fetch\n[GET] \"https://javdb.com/makers/7R\": 403 Forbidden\nbrowserType.connect: WebSocket error: wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.59                          ║\n║   - client version: v1.60                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\nCall log:\n  - <ws connecting> wss://cloudflare-patchright.rss3.workers.dev/playwright\n  - <ws unexpected response> wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.59                          ║\n║   - client version: v1.60                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\n  - <ws error> wss://cloudflare-patchright.rss3.workers.dev/playwright error WebSocket was closed before the connection was established\n  - <ws connect error> wss://cloudflare-patchright.rss3.workers.dev/playwright WebSocket was closed before the connection was established\n  - <ws disconnected> wss://cloudflare-patchright.rss3.workers.dev/playwright code=1006 reason=\n\n",
      "id": "41699114741173248",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://javdb.com/makers/7R",
      "title": "S1 NO.1 STYLE - JavDB",
      "type": "feed",
      "url": "rsshub://javdb/makers/7R"
    },
    {
      "description": "MOODYZ - JavDB - Powered by RSSHub",
      "errorAt": "2026-05-22T21:33:03.691Z",
      "errorMessage": "Failed to fetch\nbrowserType.connect: WebSocket error: wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.59                          ║\n║   - client version: v1.60                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\nCall log:\n  - <ws connecting> wss://cloudflare-patchright.rss3.workers.dev/playwright\n  - <ws unexpected response> wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.59                          ║\n║   - client version: v1.60                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\n  - <ws error> wss://cloudflare-patchright.rss3.workers.dev/playwright error WebSocket was closed before the connection was established\n  - <ws connect error> wss://cloudflare-patchright.rss3.workers.dev/playwright WebSocket was closed before the connection was established\n  - <ws disconnected> wss://cloudflare-patchright.rss3.workers.dev/playwright code=1006 reason=\n\n",
      "id": "73162555663082522",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://javdb.com/makers/zKW",
      "title": "MOODYZ - JavDB",
      "type": "feed",
      "url": "rsshub://javdb/makers/zKW"
    }
  ],
  "url": "javdb.com/"
}
```
