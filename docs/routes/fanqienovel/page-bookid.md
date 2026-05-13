# 番茄小说 - 小说更新

## Coverage
`index-only`

## Route
- Namespace: `fanqienovel`
- Namespace Name: `番茄小说`
- Route Path: `/page/:bookId`
- Route Name: `小说更新`
- Example: `/fanqienovel/page/6621052928482348040`
- URL: `fanqienovel.com`
- Language: `zh-CN`
- Categories: `reading`
- Maintainers: `TonyRL`
- Source Location: `page.ts`
- Source Module: `() => import('@/routes/fanqienovel/page.ts')`

## Description
_None_

## Parameters
- `bookId`: 小说 ID，可在 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `fanqienovel.com/page/:bookId`

## Raw JSON
```json
{
  "example": "/fanqienovel/page/6621052928482348040",
  "location": "page.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/fanqienovel/page.ts')",
  "name": "小说更新",
  "parameters": {
    "bookId": "小说 ID，可在 URL 中找到"
  },
  "path": "/page/:bookId",
  "radar": [
    {
      "source": [
        "fanqienovel.com/page/:bookId"
      ]
    }
  ]
}
```
