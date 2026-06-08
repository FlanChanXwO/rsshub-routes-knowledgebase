# 快手 - Profile

## Coverage
`index-only`

## Route
- Namespace: `kuaishou`
- Namespace Name: `快手`
- Route Path: `/kuaishou/profile/:principalId`
- Route Name: `Profile`
- Example: `/kuaishou/profile/3xk46q9cdnvgife`
- URL: `kuaishou.com/profile/:principalId`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `GuoChen-thlg`
- Source Location: `profile.ts`
- Source Module: `_None_`

## Description
::: tip
The profile page of the user, which contains the user's information, videos, and other information.
:::

## Parameters
- `principalId`: 用户 id, 可在主页中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `kuaishou.com/profile/:principalId`
- `target`: `/profile/:principalId`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "::: tip\nThe profile page of the user, which contains the user's information, videos, and other information.\n:::",
  "example": "/kuaishou/profile/3xk46q9cdnvgife",
  "heat": 6,
  "location": "profile.ts",
  "maintainers": [
    "GuoChen-thlg"
  ],
  "name": "Profile",
  "parameters": {
    "principalId": "用户 id, 可在主页中找到"
  },
  "path": "/profile/:principalId",
  "radar": [
    {
      "source": [
        "kuaishou.com/profile/:principalId"
      ],
      "target": "/profile/:principalId"
    }
  ],
  "topFeeds": [
    {
      "description": "youbao5266的作品 - 快手 - Powered by RSSHub",
      "errorAt": "2026-05-15T02:17:36.166Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nFailed to fetch\nbrowserType.connect: WebSocket error: wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.59                          ║\n║   - client version: v1.60                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\nCall log:\n  - <ws connecting> wss://cloudflare-patchright.rss3.workers.dev/playwright\n  - <ws unexpected response> wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.59                          ║\n║   - client version: v1.60                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\n  - <ws error> wss://cloudflare-patchright.rss3.workers.dev/playwright error WebSocket was closed before the connection was established\n  - <ws connect error> wss://cloudflare-patchright.rss3.workers.dev/playwright WebSocket was closed before the connection was established\n  - <ws disconnected> wss://cloudflare-patchright.rss3.workers.dev/playwright code=1006 reason=\n\n",
      "id": "147602391664470016",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "youbao5266的作品 - 快手",
      "type": "feed",
      "url": "rsshub://kuaishou/profile/youbao5266"
    },
    {
      "description": "3xiijsed725wjfa的作品 - 快手 - Powered by RSSHub",
      "errorAt": "2025-05-27T16:58:13.637Z",
      "errorMessage": "502 Bad Gateway\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "129051882573463552",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "3xiijsed725wjfa的作品 - 快手",
      "type": "feed",
      "url": "rsshub://kuaishou/profile/3xiijsed725wjfa"
    }
  ],
  "url": "kuaishou.com/profile/:principalId"
}
```
