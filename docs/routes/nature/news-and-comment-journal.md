# Nature Journal - Unknown

## Coverage
`index-only`

## Route
- Namespace: `nature`
- Namespace Name: `Nature Journal`
- Route Path: `/news-and-comment/:journal?`
- Route Name: `Unknown`
- Example: `_None_`
- URL: `nature.com/latest-news`
- Language: `en`
- Categories: `None`
- Maintainers: `y9c, TonyRL`
- Source Location: `news-and-comment.ts`
- Source Module: `() => import('@/routes/nature/news-and-comment.ts')`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `nature.com/latest-news`
  - `nature.com/news`
  - `nature.com/`
- `target`: `/news`

## Raw JSON
```json
{
  "location": "news-and-comment.ts",
  "maintainers": [
    "y9c",
    "TonyRL"
  ],
  "module": "() => import('@/routes/nature/news-and-comment.ts')",
  "name": "Unknown",
  "path": "/news-and-comment/:journal?",
  "radar": [
    {
      "source": [
        "nature.com/latest-news",
        "nature.com/news",
        "nature.com/"
      ],
      "target": "/news"
    }
  ],
  "url": "nature.com/latest-news"
}
```
