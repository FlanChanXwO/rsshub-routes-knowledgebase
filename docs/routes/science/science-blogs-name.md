# Science Magazine - Blogs

## Coverage
`index-only`

## Route
- Namespace: `science`
- Namespace Name: `Science Magazine`
- Route Path: `/science/blogs/:name?`
- Route Name: `Blogs`
- Example: `/science/blogs/pipeline`
- URL: `science.org`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `TomHodson`
- Source Location: `blogs.ts`
- Source Module: `_None_`

## Description
To subscribe to [IN THE PIPELINE by Derek Lowe’s](https://science.org/blogs/pipeline) or the [science editor's blog](https://science.org/blogs/editors-blog), use the name parameter `pipeline` or `editors-blog`.

## Parameters
- `name`: Short name for the blog, get this from the url. Defaults to pipeline


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
  - `science.org/blogs/:name`
- `target`: `/blogs/:name`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "To subscribe to [IN THE PIPELINE by Derek Lowe’s](https://science.org/blogs/pipeline) or the [science editor's blog](https://science.org/blogs/editors-blog), use the name parameter `pipeline` or `editors-blog`.",
  "example": "/science/blogs/pipeline",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 257,
  "location": "blogs.ts",
  "maintainers": [
    "TomHodson"
  ],
  "name": "Blogs",
  "parameters": {
    "name": "Short name for the blog, get this from the url. Defaults to pipeline"
  },
  "path": "/blogs/:name?",
  "radar": [
    {
      "source": [
        "science.org/blogs/:name"
      ],
      "target": "/blogs/:name"
    }
  ],
  "topFeeds": [
    {
      "description": "A Science.org blog called In the Pipeline - Powered by RSSHub",
      "errorAt": "2026-05-28T16:26:34.447Z",
      "errorMessage": "net::ERR_TIMED_OUT at https://www.science.org/blogs/pipeline/feed\nbrowserType.connect: WebSocket error: wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.59                          ║\n║   - client version: v1.60                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\nCall log:\n  - <ws connecting> wss://cloudflare-patchright.rss3.workers.dev/playwright\n  - <ws unexpected response> wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.59                          ║\n║   - client version: v1.60                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\n  - <ws error> wss://cloudflare-patchright.rss3.workers.dev/playwright error WebSocket was closed before the connection was established\n  - <ws connect error> wss://cloudflare-patchright.rss3.workers.dev/playwright WebSocket was closed before the connection was established\n  - <ws disconnected> wss://cloudflare-patchright.rss3.workers.dev/playwright code=1006 reason=\n\n",
      "id": "94573901566286848",
      "image": "https://www.science.org/apple-touch-icon.png",
      "ownerUserId": null,
      "siteUrl": "https://www.science.org/blogs/pipeline",
      "title": "Science Blogs: In the Pipeline",
      "type": "feed",
      "url": "rsshub://science/blogs"
    },
    {
      "description": "A Science.org blog called In the Pipeline - Powered by RSSHub",
      "errorAt": "2026-05-22T20:36:55.159Z",
      "errorMessage": "browserType.connect: WebSocket error: wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.59                          ║\n║   - client version: v1.60                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\nCall log:\n  - <ws connecting> wss://cloudflare-patchright.rss3.workers.dev/playwright\n  - <ws unexpected response> wss://cloudflare-patchright.rss3.workers.dev/playwright 428 Precondition Required\n╔════════════════════════════════════════════════════╗\n║ Playwright version mismatch:                       ║\n║   - server version: v1.59                          ║\n║   - client version: v1.60                          ║\n║                                                    ║\n║ If you are using VSCode extension, restart VSCode. ║\n║                                                    ║\n║ If you are connecting to a remote service,         ║\n║ keep your local Playwright version in sync         ║\n║ with the remote service version.                   ║\n║                                                    ║\n║ <3 Playwright Team                                 ║\n╚════════════════════════════════════════════════════╝\n  - <ws error> wss://cloudflare-patchright.rss3.workers.dev/playwright error WebSocket was closed before the connection was established\n  - <ws connect error> wss://cloudflare-patchright.rss3.workers.dev/playwright WebSocket was closed before the connection was established\n  - <ws disconnected> wss://cloudflare-patchright.rss3.workers.dev/playwright code=1006 reason=\n\n",
      "id": "65419023785781248",
      "image": "https://www.science.org/apple-touch-icon.png",
      "ownerUserId": null,
      "siteUrl": "https://www.science.org/blogs/pipeline",
      "title": "Science Blogs: In the Pipeline",
      "type": "feed",
      "url": "rsshub://science/blogs/pipeline"
    }
  ]
}
```
