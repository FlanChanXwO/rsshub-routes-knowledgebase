# 漫小肆韓漫 - 漫画更新

## Coverage
`index-only`

## Route
- Namespace: `freexcomic`
- Namespace Name: `漫小肆韓漫`
- Route Path: `/book/:id`
- Route Name: `漫画更新`
- Example: `/freexcomic/book/90`
- URL: `www.jjmhw.cc`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `junfengP`
- Source Location: `book.ts`
- Source Module: `() => import('@/routes/freexcomic/book.ts')`

## Description
_None_

## Parameters
- `id`: 漫画id，漫画主页的地址栏中


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `www.jjmhw.cc/book/:id`

## Raw JSON
```json
{
  "example": "/freexcomic/book/90",
  "features": {
    "nsfw": true
  },
  "location": "book.ts",
  "maintainers": [
    "junfengP"
  ],
  "module": "() => import('@/routes/freexcomic/book.ts')",
  "name": "漫画更新",
  "parameters": {
    "id": "漫画id，漫画主页的地址栏中"
  },
  "path": "/book/:id",
  "radar": [
    {
      "source": [
        "www.jjmhw.cc/book/:id"
      ]
    }
  ],
  "url": "www.jjmhw.cc"
}
```
