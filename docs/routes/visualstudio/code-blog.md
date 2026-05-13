# Visual Studio - Code Blog

## Coverage
`index-only`

## Route
- Namespace: `visualstudio`
- Namespace Name: `Visual Studio`
- Route Path: `/code/blog`
- Route Name: `Code Blog`
- Example: `/visualstudio/code/blog`
- URL: `code.visualstudio.com`
- Language: `en`
- Categories: `programming`
- Maintainers: `cscnk52`
- Source Location: `code-blog.ts`
- Source Module: `() => import('@/routes/visualstudio/code-blog.ts')`

## Description
Provides a better reading experience (full articles) over the official ones.

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
  - `code.visualstudio.com/`
- `target`: `/code/blog`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "Provides a better reading experience (full articles) over the official ones.",
  "example": "/visualstudio/code/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "code-blog.ts",
  "maintainers": [
    "cscnk52"
  ],
  "module": "() => import('@/routes/visualstudio/code-blog.ts')",
  "name": "Code Blog",
  "parameters": {},
  "path": "/code/blog",
  "radar": [
    {
      "source": [
        "code.visualstudio.com/"
      ],
      "target": "/code/blog"
    }
  ],
  "url": "code.visualstudio.com",
  "view": 5
}
```
