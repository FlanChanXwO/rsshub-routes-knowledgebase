# Niconico - Mylist

## Coverage
`index-only`

## Route
- Namespace: `nicovideo`
- Namespace Name: `Niconico`
- Route Path: `/mylist/:id`
- Route Name: `Mylist`
- Example: `/nicovideo/mylist/2973737`
- URL: `www.nicovideo.jp`
- Language: `ja`
- Categories: `multimedia`
- Maintainers: `esperecyan`
- Source Location: `mylist.ts`
- Source Module: `() => import('@/routes/nicovideo/mylist.ts')`

## Description
_None_

## Parameters
- `id`: Mylist ID


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.nicovideo.jp/user/:user/mylist/:id`
- `target`: `/mylist/:id`

## Raw JSON
```json
{
  "example": "/nicovideo/mylist/2973737",
  "location": "mylist.ts",
  "maintainers": [
    "esperecyan"
  ],
  "module": "() => import('@/routes/nicovideo/mylist.ts')",
  "name": "Mylist",
  "parameters": {
    "id": "Mylist ID"
  },
  "path": "/mylist/:id",
  "radar": [
    {
      "source": [
        "www.nicovideo.jp/user/:user/mylist/:id"
      ],
      "target": "/mylist/:id"
    }
  ]
}
```
