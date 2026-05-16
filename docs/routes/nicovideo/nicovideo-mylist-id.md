# Niconico - Mylist

## Coverage
`index-only`

## Route
- Namespace: `nicovideo`
- Namespace Name: `Niconico`
- Route Path: `/nicovideo/mylist/:id`
- Route Name: `Mylist`
- Example: `/nicovideo/mylist/2973737`
- URL: `www.nicovideo.jp`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `esperecyan`
- Source Location: `mylist.ts`
- Source Module: `_None_`

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
  "categories": [
    "multimedia"
  ],
  "example": "/nicovideo/mylist/2973737",
  "heat": 0,
  "location": "mylist.ts",
  "maintainers": [
    "esperecyan"
  ],
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
  ],
  "topFeeds": []
}
```
