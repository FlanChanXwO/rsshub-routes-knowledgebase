# Matters - Author

## Coverage
`index-only`

## Route
- Namespace: `matters`
- Namespace Name: `Matters`
- Route Path: `/author/:uid`
- Route Name: `Author`
- Example: `/matters/author/robertu`
- URL: `matters.town`
- Language: `en`
- Categories: `new-media`
- Maintainers: `Cerebrater, xosdy`
- Source Location: `author.ts`
- Source Module: `() => import('@/routes/matters/author.ts')`

## Description
_None_

## Parameters
- `uid`: Author id, can be found at author's homepage url


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `matters.town/:uid`

## Raw JSON
```json
{
  "example": "/matters/author/robertu",
  "location": "author.ts",
  "maintainers": [
    "Cerebrater",
    "xosdy"
  ],
  "module": "() => import('@/routes/matters/author.ts')",
  "name": "Author",
  "parameters": {
    "uid": "Author id, can be found at author's homepage url"
  },
  "path": "/author/:uid",
  "radar": [
    {
      "source": [
        "matters.town/:uid"
      ]
    }
  ]
}
```
