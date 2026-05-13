# Deepin - BBS Home Page

## Coverage
`index-only`

## Route
- Namespace: `deepin`
- Namespace Name: `Deepin`
- Route Path: `/homepage/:user_id`
- Route Name: `BBS Home Page`
- Example: `/deepin/homepage/78326`
- URL: `bbs.deepin.org`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `tensor-tech`
- Source Location: `homepage.ts`
- Source Module: `() => import('@/routes/deepin/homepage.ts')`

## Description
_None_

## Parameters
- `user_id`: user id


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `bbs.deepin.org/user/:user_id`
- `target`: `/homepage/:user_id`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/deepin/homepage/78326",
  "location": "homepage.ts",
  "maintainers": [
    "tensor-tech"
  ],
  "module": "() => import('@/routes/deepin/homepage.ts')",
  "name": "BBS Home Page",
  "parameters": {
    "user_id": "user id"
  },
  "path": "/homepage/:user_id",
  "radar": [
    {
      "source": [
        "bbs.deepin.org/user/:user_id"
      ],
      "target": "/homepage/:user_id"
    }
  ]
}
```
