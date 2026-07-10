# hashnode - 用户博客

## Coverage
`index-only`

## Route
- Namespace: `hashnode`
- Namespace Name: `hashnode`
- Route Path: `/hashnode/blog/:username`
- Route Name: `用户博客`
- Example: `/hashnode/blog/inklings`
- URL: `hashnode.dev/`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `hnrainll`
- Source Location: `blog.tsx`
- Source Module: `_None_`

## Description
::: tip
username 为博主用户名，而非`xxx.hashnode.dev`中`xxx`所代表的 blog 地址。
:::

## Parameters
- `username`: 博主名称，用户头像 URL 中找到


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
  - `hashnode.dev/`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "description": "::: tip\nusername 为博主用户名，而非`xxx.hashnode.dev`中`xxx`所代表的 blog 地址。\n:::",
  "example": "/hashnode/blog/inklings",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "blog.tsx",
  "maintainers": [
    "hnrainll"
  ],
  "name": "用户博客",
  "parameters": {
    "username": "博主名称，用户头像 URL 中找到"
  },
  "path": "/blog/:username",
  "radar": [
    {
      "source": [
        "hashnode.dev/"
      ]
    }
  ],
  "topFeeds": [],
  "url": "hashnode.dev/"
}
```
