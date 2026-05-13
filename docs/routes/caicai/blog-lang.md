# CaiCai - Blog

## Coverage
`index-only`

## Route
- Namespace: `caicai`
- Namespace Name: `CaiCai`
- Route Path: `/blog/:lang?`
- Route Name: `Blog`
- Example: `/caicai/blog`
- URL: `www.caicai.me/blogs`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `TonyRL`
- Source Location: `blog.ts`
- Source Module: `() => import('@/routes/caicai/blog.ts')`

## Description
_None_

## Parameters
- `lang`: {"default": "en", "description": "Language", "options": [{"label": "English", "value": "en"}, {"label": "中文", "value": "zh"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.caicai.me/blogs`
### Rule 2
- `source`:
  - `www.caicai.me/zh/blogs`
- `target`: `/blog/zh`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/caicai/blog",
  "location": "blog.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/caicai/blog.ts')",
  "name": "Blog",
  "parameters": {
    "lang": {
      "default": "en",
      "description": "Language",
      "options": [
        {
          "label": "English",
          "value": "en"
        },
        {
          "label": "中文",
          "value": "zh"
        }
      ]
    }
  },
  "path": "/blog/:lang?",
  "radar": [
    {
      "source": [
        "www.caicai.me/blogs"
      ]
    },
    {
      "source": [
        "www.caicai.me/zh/blogs"
      ],
      "target": "/blog/zh"
    }
  ],
  "url": "www.caicai.me/blogs"
}
```
