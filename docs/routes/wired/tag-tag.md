# WIRED - Tags

## Coverage
`index-only`

## Route
- Namespace: `wired`
- Namespace Name: `WIRED`
- Route Path: `/tag/:tag`
- Route Name: `Tags`
- Example: `/wired/tag/facebook`
- URL: `www.wired.com`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `Naiqus`
- Source Location: `tag.ts`
- Source Module: `() => import('@/routes/wired/tag.ts')`

## Description
_None_

## Parameters
- `tag`: Tag name


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.wired.com/tag/:tag/`

## Raw JSON
```json
{
  "example": "/wired/tag/facebook",
  "location": "tag.ts",
  "maintainers": [
    "Naiqus"
  ],
  "module": "() => import('@/routes/wired/tag.ts')",
  "name": "Tags",
  "parameters": {
    "tag": "Tag name"
  },
  "path": "/tag/:tag",
  "radar": [
    {
      "source": [
        "www.wired.com/tag/:tag/"
      ]
    }
  ]
}
```
