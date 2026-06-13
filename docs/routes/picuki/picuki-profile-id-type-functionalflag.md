# TikTok - User Profile - Picuki

## Coverage
`index-only`

## Route
- Namespace: `picuki`
- Namespace Name: `TikTok`
- Route Path: `/picuki/profile/:id/:type?/:functionalFlag?`
- Route Name: `User Profile - Picuki`
- Example: `/picuki/profile/linustech`
- URL: `tiktok.com`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `hoilc, Rongronggg9, devinmugen, NekoAria`
- Source Location: `profile.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Tiktok user id (without @)
- `type`: {"default": "profile", "description": "Type of profile page", "options": [{"label": "Profile Page", "value": "profile"}, {"label": "Story Page", "value": "story"}]}
- `functionalFlag`: {"default": "1", "description": "Functional flag for video embedding", "options": [{"label": "Off, only show video poster as an image", "value": "0"}, {"label": "On", "value": "1"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.picuki.com/profile/:id`
- `target`: `/profile/:id`
### Rule 2
- `source`:
  - `www.picuki.com/story/:id`
- `target`: `/profile/:id/story`

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "example": "/picuki/profile/linustech",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 10697,
  "location": "profile.ts",
  "maintainers": [
    "hoilc",
    "Rongronggg9",
    "devinmugen",
    "NekoAria"
  ],
  "name": "User Profile - Picuki",
  "parameters": {
    "functionalFlag": {
      "default": "1",
      "description": "Functional flag for video embedding",
      "options": [
        {
          "label": "Off, only show video poster as an image",
          "value": "0"
        },
        {
          "label": "On",
          "value": "1"
        }
      ]
    },
    "id": "Tiktok user id (without @)",
    "type": {
      "default": "profile",
      "description": "Type of profile page",
      "options": [
        {
          "label": "Profile Page",
          "value": "profile"
        },
        {
          "label": "Story Page",
          "value": "story"
        }
      ]
    }
  },
  "path": "/profile/:id/:type?/:functionalFlag?",
  "radar": [
    {
      "source": [
        "www.picuki.com/profile/:id"
      ],
      "target": "/profile/:id"
    },
    {
      "source": [
        "www.picuki.com/story/:id"
      ],
      "target": "/profile/:id/story"
    }
  ],
  "topFeeds": [
    {
      "description": "7 posts - Powered by RSSHub",
      "errorAt": "2025-12-01T11:31:13.832Z",
      "errorMessage": "Failed to fetch\nFailed to fetch\nWaiting for selector `.content` failed: waitForFunction failed: frame got detached.\nFailed to fetch\nContent does not exist.\n",
      "id": "68868134910057472",
      "image": "https://p16-sign-sg.tiktokcdn.com/tos-alisg-avt-0068/20f0f3b9dca2307c0d9e928f5a31e787~tplv-tiktokx-cropcenter:720:720.jpeg?dr=10399&refresh_token=c2635a64&x-expires=1763265600&x-signature=ZbrX%2BEgQnxUC4x4myuI%2FM5Za0xg%3D&t=4d5b0474&ps=13740610&shp=a5d48078&shcp=81f88b70&idc=no1a",
      "ownerUserId": null,
      "siteUrl": "https://www.picuki.com/profile/soyeemilk__",
      "title": "@soyeemilk__ 豆乳 view and download public TikTok videos and stories - Tikvib.com",
      "type": "feed",
      "url": "rsshub://picuki/profile/soyeemilk__"
    },
    {
      "description": "白银 (@baiyinn811) public posts - Picuki - Powered by RSSHub",
      "errorAt": "2024-12-09T13:19:26.547Z",
      "errorMessage": "Failed to fetch\nFailed to fetch\nFailed to fetch\nbrowserType.connect: WebSocket error: wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.59                          ║\n║   - client version: v1.60                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\nCall log:\n  - <ws connecting> wss://cloudflare-patchright.rss3.workers.dev/playwright\n  - <ws unexpected response> wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.59                          ║\n║   - client version: v1.60                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\n  - <ws error> wss://cloudflare-patchright.rss3.workers.dev/playwright error WebSocket was closed before the connection was established\n  - <ws connect error> wss://cloudflare-patchright.rss3.workers.dev/playwright WebSocket was closed before the connection was established\n  - <ws disconnected> wss://cloudflare-patchright.rss3.workers.dev/playwright code=1006 reason=\n\n",
      "id": "68562239082161152",
      "image": "https://cdn1.picuki.com/hosted-by-instagram/q/yep6IPkO1EBGZyPbcMUQzeBRjaJ4Rg1ONw==.jpeg",
      "ownerUserId": null,
      "siteUrl": "https://www.picuki.com/profile/baiyinn811",
      "title": "白银 (@baiyinn811) public posts - Picuki",
      "type": "feed",
      "url": "rsshub://picuki/profile/baiyinn811"
    }
  ]
}
```
