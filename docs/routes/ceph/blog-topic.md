# Ceph - Blog

## Coverage
`index-only`

## Route
- Namespace: `ceph`
- Namespace Name: `Ceph`
- Route Path: `/blog/:topic?`
- Route Name: `Blog`
- Example: `/ceph/blog/a11y`
- URL: `ceph.io`
- Language: `en`
- Categories: `blog`
- Maintainers: `pandada8`
- Source Location: `blog.ts`
- Source Module: `() => import('@/routes/ceph/blog.ts')`

## Description
_None_

## Parameters
- `category`: filter blog post by category, return all posts if not specified


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
  - `ceph.io/`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/ceph/blog/a11y",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "blog.ts",
  "maintainers": [
    "pandada8"
  ],
  "module": "() => import('@/routes/ceph/blog.ts')",
  "name": "Blog",
  "parameters": {
    "category": "filter blog post by category, return all posts if not specified"
  },
  "path": "/blog/:topic?",
  "radar": [
    {
      "source": [
        "ceph.io/"
      ]
    }
  ],
  "url": "ceph.io"
}
```
