# Radio France Internationale - Generic News

## Coverage
`index-only`

## Route
- Namespace: `rfi`
- Namespace Name: `Radio France Internationale`
- Route Path: `/rfi/:path{.+}?`
- Route Name: `Generic News`
- Example: `/rfi`
- URL: `rfi.fr`
- Language: `_None_`
- Categories: `other`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
::: tip

- To subscribe to [English News](https://www.rfi.fr/en/), which URL is `https://www.rfi.fr/en`, you can get the route as [`/rfi/en`](https://rsshub.app/rfi/en).
- To subscribe to [English Europe News](https://www.rfi.fr/en/europe/), which URL is `https://www.rfi.fr/en/europe`, you can get the route as [`/rfi/en/europe`](https://rsshub.app/rfi/en/europe).
- To subscribe to topic [Paris Olympics 2024](https://www.rfi.fr/en/tag/paris-olympics-2024/), which URL is `https://www.rfi.fr/en/tag/paris-olympics-2024`, you can get the route as [`/rfi/en/tag/paris-olympics-2024`](https://rsshub.app/rfi/en/tag/paris-olympics-2024).

:::

::: warning
This route does not support podcasts, please use the Offical RSS feed instead.
:::

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `rfi.fr/*path`
- `target`: `/:path`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "::: tip\n\n- To subscribe to [English News](https://www.rfi.fr/en/), which URL is `https://www.rfi.fr/en`, you can get the route as [`/rfi/en`](https://rsshub.app/rfi/en).\n- To subscribe to [English Europe News](https://www.rfi.fr/en/europe/), which URL is `https://www.rfi.fr/en/europe`, you can get the route as [`/rfi/en/europe`](https://rsshub.app/rfi/en/europe).\n- To subscribe to topic [Paris Olympics 2024](https://www.rfi.fr/en/tag/paris-olympics-2024/), which URL is `https://www.rfi.fr/en/tag/paris-olympics-2024`, you can get the route as [`/rfi/en/tag/paris-olympics-2024`](https://rsshub.app/rfi/en/tag/paris-olympics-2024).\n\n:::\n\n::: warning\nThis route does not support podcasts, please use the Offical RSS feed instead.\n:::",
  "example": "/rfi",
  "heat": 68,
  "location": "news.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "name": "Generic News",
  "path": "/:path{.+}?",
  "radar": [
    {
      "source": [
        "rfi.fr/*path"
      ],
      "target": "/:path"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "同步、随时跟踪法广政治、文化、体育新闻，了解法国、中国与世界各地大事 - Powered by RSSHub",
      "errorAt": "2026-05-12T20:56:34.467Z",
      "errorMessage": "[GET] \"https://www.rfi.fr/cn/%E9%9D%9E%E6%B4%B2/20260512-%E9%A9%AC%E5%85%8B%E9%BE%99-%E6%B3%95%E6%B1%89%E5%9D%A6%E7%97%85%E6%AF%92%E7%96%AB%E6%83%85-%E5%9C%A8%E6%8E%8C%E6%8E%A7%E4%B9%8B%E4%B8%AD\": 403 Forbidden\n",
      "id": "58701529235465216",
      "image": "https://s.rfi.fr/media/display/020b8dae-e6c1-11ee-a196-005056bfb2b6/w:1280/p:16x9/img-default-RFI.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.rfi.fr/cn/",
      "title": "法广 - 时事与新闻直播 - RFI - 法国国际广播电台",
      "type": "feed",
      "url": "rsshub://rfi/cn"
    },
    {
      "description": "最新中东与阿拉伯世界新闻 - Powered by RSSHub",
      "errorAt": "2025-12-14T10:53:13.777Z",
      "errorMessage": "[GET] \"https://www.rfi.fr/cn/中东/\": 403 Forbidden\nUnexpected non-whitespace character after JSON at position 3939 (line 4 column 13)\n",
      "id": "84066827566712832",
      "image": "https://s.rfi.fr/media/display/020b8dae-e6c1-11ee-a196-005056bfb2b6/w:1280/p:16x9/img-default-RFI.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.rfi.fr/cn/%E4%B8%AD%E4%B8%9C/",
      "title": "中东与阿拉伯世界时事 - 法广 - RFI",
      "type": "feed",
      "url": "rsshub://rfi/cn/%E4%B8%AD%E4%B8%9C"
    }
  ],
  "url": "rfi.fr"
}
```
