# Huggingface - Community Articles

## Coverage
`index-only`

## Route
- Namespace: `huggingface`
- Namespace Name: `Huggingface`
- Route Path: `/blog-community/:sort?`
- Route Name: `Community Articles`
- Example: `/huggingface/blog-community`
- URL: `huggingface.co/blog/community`
- Language: `en`
- Categories: `programming`
- Maintainers: `yuguorui`
- Source Location: `blog-community.ts`
- Source Module: `() => import('@/routes/huggingface/blog-community.ts')`

## Description
_None_

## Parameters
- `sort`: {"default": "trending", "description": "Sort by trending or recent", "options": [{"label": "Trending", "value": "trending"}, {"label": "Recent", "value": "recent"}]}


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
  - `huggingface.co/blog/community`
  - `huggingface.co/`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/huggingface/blog-community",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "blog-community.ts",
  "maintainers": [
    "yuguorui"
  ],
  "module": "() => import('@/routes/huggingface/blog-community.ts')",
  "name": "Community Articles",
  "parameters": {
    "sort": {
      "default": "trending",
      "description": "Sort by trending or recent",
      "options": [
        {
          "label": "Trending",
          "value": "trending"
        },
        {
          "label": "Recent",
          "value": "recent"
        }
      ]
    }
  },
  "path": "/blog-community/:sort?",
  "radar": [
    {
      "source": [
        "huggingface.co/blog/community",
        "huggingface.co/"
      ]
    }
  ],
  "url": "huggingface.co/blog/community"
}
```
