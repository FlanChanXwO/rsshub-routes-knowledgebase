# Uber - Engineering

## Coverage
`index-only`

## Route
- Namespace: `uber`
- Namespace Name: `Uber`
- Route Path: `/blog/:compat?`
- Route Name: `Engineering`
- Example: `/uber/blog`
- URL: `www.uber.com/en-HK/blog/engineering`
- Language: `en`
- Categories: `blog`
- Maintainers: `hulb`
- Source Location: `blog.ts`
- Source Module: `() => import('@/routes/uber/blog.ts')`

## Description
The English blog on any of Uber's regional sites (e.g., www.uber.com/en-JP/blog) is the same engineering blog provided by this route, so language selection is not supported. This route is not for the public news blog on specific regional sites (e.g., www.uber.com/ja-JP/blog).

## Parameters
_None_


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
  - `www.uber.com/:language/blog/engineering`
- `target`: `/blog`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "description": "The English blog on any of Uber's regional sites (e.g., www.uber.com/en-JP/blog) is the same engineering blog provided by this route, so language selection is not supported. This route is not for the public news blog on specific regional sites (e.g., www.uber.com/ja-JP/blog).",
  "example": "/uber/blog",
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
    "hulb"
  ],
  "module": "() => import('@/routes/uber/blog.ts')",
  "name": "Engineering",
  "path": "/blog/:compat?",
  "radar": [
    {
      "source": [
        "www.uber.com/:language/blog/engineering"
      ],
      "target": "/blog"
    }
  ],
  "url": "www.uber.com/en-HK/blog/engineering",
  "zh": {
    "description": "uber的任何区域站点的英文blog（例如www.uber.com/en-JP/blog）都是相同的内容，正是本路由提供的engineering blog，因此本路由不提供语言选择；本路由不是uber在特定区域站点的公开新闻blog（例如www.uber.com/ja-JP/blog)"
  }
}
```
