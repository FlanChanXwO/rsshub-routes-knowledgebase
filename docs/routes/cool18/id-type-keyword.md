# 禁忌书屋 - 禁忌书屋

## Coverage
`index-only`

## Route
- Namespace: `cool18`
- Namespace Name: `禁忌书屋`
- Route Path: `/:id?/:type?/:keyword?`
- Route Name: `禁忌书屋`
- Example: `/cool18/bbs4`
- URL: `cool18.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `nczitzk, Gabrlie`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/cool18/index.ts')`

## Description
_None_

## Parameters
- `id`: the name of the bbs, use `global` for site-wide search
- `type`: the type of the post. Can be `home`, `gold`, `threadsearch`. Default: `home`
- `keyword`: the keyword to search.


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `cool18.com/:id/`
- `target`: `/:id/:type?/:keyword?`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/cool18/bbs4",
  "features": {
    "nsfw": true
  },
  "location": "index.ts",
  "maintainers": [
    "nczitzk",
    "Gabrlie"
  ],
  "module": "() => import('@/routes/cool18/index.ts')",
  "name": "禁忌书屋",
  "parameters": {
    "id": "the name of the bbs, use `global` for site-wide search",
    "keyword": "the keyword to search.",
    "type": "the type of the post. Can be `home`, `gold`, `threadsearch`. Default: `home`"
  },
  "path": "/:id?/:type?/:keyword?",
  "radar": [
    {
      "source": [
        "cool18.com/:id/"
      ],
      "target": "/:id/:type?/:keyword?"
    }
  ],
  "url": "cool18.com"
}
```
