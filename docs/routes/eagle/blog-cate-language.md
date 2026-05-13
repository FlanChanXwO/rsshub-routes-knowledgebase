# Eagle - Blog

## Coverage
`index-only`

## Route
- Namespace: `eagle`
- Namespace Name: `Eagle`
- Route Path: `/blog/:cate?/:language?`
- Route Name: `Blog`
- Example: `/eagle/blog/en`
- URL: `cn.eagle.cool/blog`
- Language: `zh-CN`
- Categories: `blog`
- Maintainers: `Fatpandac`
- Source Location: `blog.ts`
- Source Module: `() => import('@/routes/eagle/blog.ts')`

## Description
_None_

## Parameters
- `cate`: Category, get by URL, `all` by default
- `language`: {"default": "en", "description": "Language", "options": [{"label": "cn", "value": "cn"}, {"label": "tw", "value": "tw"}, {"label": "en", "value": "en"}]}


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
  - `cn.eagle.cool/blog`
- `target`: `/blog`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/eagle/blog/en",
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
    "Fatpandac"
  ],
  "module": "() => import('@/routes/eagle/blog.ts')",
  "name": "Blog",
  "parameters": {
    "cate": "Category, get by URL, `all` by default",
    "language": {
      "default": "en",
      "description": "Language",
      "options": [
        {
          "label": "cn",
          "value": "cn"
        },
        {
          "label": "tw",
          "value": "tw"
        },
        {
          "label": "en",
          "value": "en"
        }
      ]
    }
  },
  "path": "/blog/:cate?/:language?",
  "radar": [
    {
      "source": [
        "cn.eagle.cool/blog"
      ],
      "target": "/blog"
    }
  ],
  "url": "cn.eagle.cool/blog"
}
```
