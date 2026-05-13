# hashnode - 用户博客

## Coverage
`index-only`

## Route
- Namespace: `hashnode`
- Namespace Name: `hashnode`
- Route Path: `/blog/:username`
- Route Name: `用户博客`
- Example: `/hashnode/blog/inklings`
- URL: `hashnode.dev/`
- Language: `en`
- Categories: `blog`
- Maintainers: `hnrainll`
- Source Location: `blog.tsx`
- Source Module: `() => import('@/routes/hashnode/blog.tsx')`

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
  "description": "::: tip\n  username 为博主用户名，而非`xxx.hashnode.dev`中`xxx`所代表的 blog 地址。\n:::",
  "example": "/hashnode/blog/inklings",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "blog.tsx",
  "maintainers": [
    "hnrainll"
  ],
  "module": "() => import('@/routes/hashnode/blog.tsx')",
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
  "url": "hashnode.dev/"
}
```
