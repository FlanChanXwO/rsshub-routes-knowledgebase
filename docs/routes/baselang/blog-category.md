# BaseLang - Blog

## Coverage
`index-only`

## Route
- Namespace: `baselang`
- Namespace Name: `BaseLang`
- Route Path: `/blog/:category?`
- Route Name: `Blog`
- Example: `/baselang/blog`
- URL: `_None_`
- Language: `en`
- Categories: `blog`
- Maintainers: `johan456789`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/baselang/index.ts')`

## Description
_None_

## Parameters
- `category`: {"description": "Optional category filter", "options": [{"label": "advanced-grammar", "value": "advanced-grammar"}, {"label": "basic-grammar", "value": "basic-grammar"}, {"label": "company", "value": "company"}, {"label": "confidence", "value": "confidence"}, {"label": "french", "value": "french"}, {"label": "humor", "value": "humor"}, {"label": "medellin", "value": "medellin"}, {"label": "motivation", "value": "motivation"}, {"label": "pronunciation", "value": "pronunciation"}, {"label": "study-tips", "value": "study-tips"}, {"label": "success-stories", "value": "success-stories"}, {"label": "travel", "value": "travel"}, {"label": "uncategorized", "value": "uncategorized"}, {"label": "vocabulary", "value": "vocabulary"}]}


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
  - `baselang.com/blog`
  - `baselang.com/blog/:category`
- `target`: `/blog/:category`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/baselang/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "johan456789"
  ],
  "module": "() => import('@/routes/baselang/index.ts')",
  "name": "Blog",
  "parameters": {
    "category": {
      "description": "Optional category filter",
      "options": [
        {
          "label": "advanced-grammar",
          "value": "advanced-grammar"
        },
        {
          "label": "basic-grammar",
          "value": "basic-grammar"
        },
        {
          "label": "company",
          "value": "company"
        },
        {
          "label": "confidence",
          "value": "confidence"
        },
        {
          "label": "french",
          "value": "french"
        },
        {
          "label": "humor",
          "value": "humor"
        },
        {
          "label": "medellin",
          "value": "medellin"
        },
        {
          "label": "motivation",
          "value": "motivation"
        },
        {
          "label": "pronunciation",
          "value": "pronunciation"
        },
        {
          "label": "study-tips",
          "value": "study-tips"
        },
        {
          "label": "success-stories",
          "value": "success-stories"
        },
        {
          "label": "travel",
          "value": "travel"
        },
        {
          "label": "uncategorized",
          "value": "uncategorized"
        },
        {
          "label": "vocabulary",
          "value": "vocabulary"
        }
      ]
    }
  },
  "path": "/blog/:category?",
  "radar": [
    {
      "source": [
        "baselang.com/blog",
        "baselang.com/blog/:category"
      ],
      "target": "/blog/:category"
    }
  ]
}
```
