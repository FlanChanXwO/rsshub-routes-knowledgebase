# CaiCai - Blog

## Coverage
`index-only`

## Route
- Namespace: `caicai`
- Namespace Name: `CaiCai`
- Route Path: `/caicai/blog/:lang?`
- Route Name: `Blog`
- Example: `/caicai/blog`
- URL: `www.caicai.me/blogs`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `TonyRL`
- Source Location: `blog.ts`
- Source Module: `_None_`

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
  "heat": 0,
  "location": "blog.ts",
  "maintainers": [
    "TonyRL"
  ],
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
  "test": {
    "code": 1,
    "message": "AssertionError: expected 376017575510 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:38:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:63:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.caicai.me/blogs"
}
```
