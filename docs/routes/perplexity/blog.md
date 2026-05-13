# Perplexity - Blog

## Coverage
`index-only`

## Route
- Namespace: `perplexity`
- Namespace Name: `Perplexity`
- Route Path: `/blog`
- Route Name: `Blog`
- Example: `/perplexity/blog`
- URL: `www.perplexity.ai`
- Language: `en`
- Categories: `blog`
- Maintainers: `seeyangzhi`
- Source Location: `blog.ts`
- Source Module: `() => import('@/routes/perplexity/blog.ts')`

## Description
Perplexity Blog - Explore Perplexity's blog for articles, announcements, product updates, and tips to optimize your experience. Stay informed and make the most of Perplexity.

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.perplexity.ai/hub`
- `target`: `/blog`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "description": "Perplexity Blog - Explore Perplexity's blog for articles, announcements, product updates, and tips to optimize your experience. Stay informed and make the most of Perplexity.",
  "example": "/perplexity/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "blog.ts",
  "maintainers": [
    "seeyangzhi"
  ],
  "module": "() => import('@/routes/perplexity/blog.ts')",
  "name": "Blog",
  "parameters": {},
  "path": "/blog",
  "radar": [
    {
      "source": [
        "www.perplexity.ai/hub"
      ],
      "target": "/blog"
    }
  ],
  "url": "www.perplexity.ai",
  "view": 5
}
```
