# Qwen Blog - Blog

## Coverage
`index-only`

## Route
- Namespace: `qwenlm`
- Namespace Name: `Qwen Blog`
- Route Path: `/blog/:lang?`
- Route Name: `Blog`
- Example: `/qwenlm/blog/zh`
- URL: `qwenlm.github.io`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `Kjasn`
- Source Location: `blog.ts`
- Source Module: `() => import('@/routes/qwenlm/blog.ts')`

## Description
_None_

## Parameters
- `lang`: Blog language


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
  - `qwenlm.github.io/blog/`
  - `qwenlm.github.io/:lang/blog/`
- `target`: `/qwenlm/blog/:lang`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/qwenlm/blog/zh",
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
    "Kjasn"
  ],
  "module": "() => import('@/routes/qwenlm/blog.ts')",
  "name": "Blog",
  "parameters": {
    "lang": "Blog language"
  },
  "path": "/blog/:lang?",
  "radar": [
    {
      "source": [
        "qwenlm.github.io/blog/",
        "qwenlm.github.io/:lang/blog/"
      ],
      "target": "/qwenlm/blog/:lang"
    }
  ]
}
```
