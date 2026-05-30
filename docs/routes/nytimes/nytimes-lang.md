# The New York Times - News

## Coverage
`index-only`

## Route
- Namespace: `nytimes`
- Namespace Name: `The New York Times`
- Route Path: `/nytimes/:lang?`
- Route Name: `News`
- Example: `/nytimes/dual`
- URL: `nytimes.com/`
- Language: `_None_`
- Categories: `traditional-media, popular`
- Maintainers: `HenryQW, pseudoyu`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
By extracting the full text of articles, we provide a better reading experience (full text articles) over the official one.

## Parameters
- `lang`: {"description": "language, default to Chinese", "options": [{"label": "Chinese-English", "value": "dual"}, {"label": "English", "value": "en"}, {"label": "Traditional Chinese", "value": "traditionalchinese"}, {"label": "Chinese-English (Traditional Chinese)", "value": "dual-traditionalchinese"}]}


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
  - `nytimes.com/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "traditional-media",
    "popular"
  ],
  "description": "By extracting the full text of articles, we provide a better reading experience (full text articles) over the official one.",
  "example": "/nytimes/dual",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8130,
  "location": "index.ts",
  "maintainers": [
    "HenryQW",
    "pseudoyu"
  ],
  "name": "News",
  "parameters": {
    "lang": {
      "description": "language, default to Chinese",
      "options": [
        {
          "label": "Chinese-English",
          "value": "dual"
        },
        {
          "label": "English",
          "value": "en"
        },
        {
          "label": "Traditional Chinese",
          "value": "traditionalchinese"
        },
        {
          "label": "Chinese-English (Traditional Chinese)",
          "value": "dual-traditionalchinese"
        }
      ]
    }
  },
  "path": "/:lang?",
  "radar": [
    {
      "source": [
        "nytimes.com/"
      ],
      "target": ""
    }
  ],
  "topFeeds": [
    {
      "description": "纽约时报中文网 - Powered by RSSHub",
      "errorAt": "2026-05-28T13:54:19.323Z",
      "errorMessage": "Failed to fetch\n403 Forbidden\nFailed to fetch\nCould not find Chrome (ver. 136.0.7103.49). This can occur if either\n 1. you did not perform an installation before running the script (e.g. `npx puppeteer browsers install chrome`) or\n 2. your cache path is incorrectly configured (which is: /app/node_modules/.cache/puppeteer).\nFor (2), check out our guide on configuring puppeteer at https://pptr.dev/guides/configuration.\nFailed to fetch\nAuthentication failed. Access denied.\n/nytimes\nCould not find Chrome (ver. 136.0.7103.49). This can occur if either\n 1. you did not perform an installation before running the script (e.g. `npx puppeteer browsers install chrome`) or\n 2. your cache path is incorrectly configured (which is: /app/node_modules/.cache/puppeteer).\nFor (2), check out our guide on configuring puppeteer at https://pptr.dev/guides/configuration.\nFailed to fetch\nbrowserType.launch: Executable doesn't exist at /home/sbx_user1051/.cache/ms-playwright/chromium_headless_shell-1223/chrome-headless-shell-linux64/chrome-headless-shell\n╔════════════════════════════════════════════════════════════╗\n║ Looks like Playwright was just installed or updated.       ║\n║ Please run the following command to download new browsers: ║\n║                                                            ║\n║     npx playwright install                                 ║\n║                                                            ║\n║ <3 Playwright Team                                         ║\n╚════════════════════════════════════════════════════════════╝\nFailed to fetch\nbrowserType.connect: WebSocket error: getaddrinfo ENOTFOUND browserless\nCall log:\n  - <ws connecting> ws://browserless:3000/\n  - <ws error> ws://browserless:3000/ error getaddrinfo ENOTFOUND browserless\n  - <ws connect error> ws://browserless:3000/ getaddrinfo ENOTFOUND browserless\n  - <ws disconnected> ws://browserless:3000/ code=1006 reason=\n\nFailed to fetch\nbrowserType.launch: Executable doesn't exist at /root/.cache/ms-playwright/chromium_headless_shell-1223/chrome-headless-shell-linux64/chrome-headless-shell\n╔════════════════════════════════════════════════════════════╗\n║ Looks like Playwright was just installed or updated.       ║\n║ Please run the following command to download new browsers: ║\n║                                                            ║\n║     npx playwright install                                 ║\n║                                                            ║\n║ <3 Playwright Team                                         ║\n╚════════════════════════════════════════════════════════════╝\nFailed to fetch\nbrowserType.connect: WebSocket error: wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.59                          ║\n║   - client version: v1.60                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\nCall log:\n  - <ws connecting> wss://cloudflare-patchright.rss3.workers.dev/playwright\n  - <ws unexpected response> wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.59                          ║\n║   - client version: v1.60                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\n  - <ws error> wss://cloudflare-patchright.rss3.workers.dev/playwright error WebSocket was closed before the connection was established\n  - <ws connect error> wss://cloudflare-patchright.rss3.workers.dev/playwright WebSocket was closed before the connection was established\n  - <ws disconnected> wss://cloudflare-patchright.rss3.workers.dev/playwright code=1006 reason=\n\n",
      "id": "41443203209057308",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cn.nytimes.com/",
      "title": "纽约时报中文网",
      "type": "feed",
      "url": "rsshub://nytimes"
    },
    {
      "description": "纽约时报中文网 - 中英对照版 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41572238273905693",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cn.nytimes.com/",
      "title": "纽约时报中文网 - 中英对照版",
      "type": "feed",
      "url": "rsshub://nytimes/dual"
    }
  ],
  "url": "nytimes.com/",
  "view": 0
}
```
