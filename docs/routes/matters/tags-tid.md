# Matters - Tags

## Coverage
`index-only`

## Route
- Namespace: `matters`
- Namespace Name: `Matters`
- Route Path: `/tags/:tid`
- Route Name: `Tags`
- Example: `/matters/tags/972-哲學`
- URL: `matters.town`
- Language: `en`
- Categories: `new-media`
- Maintainers: `Cerebrater`
- Source Location: `tags.ts`
- Source Module: `() => import('@/routes/matters/tags.ts')`

## Description
_None_

## Parameters
- `tid`: Tag id, can be found in the url of the tag page


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `matters.town/tags/:tid`

## Raw JSON
```json
{
  "example": "/matters/tags/972-哲學",
  "location": "tags.ts",
  "maintainers": [
    "Cerebrater"
  ],
  "module": "() => import('@/routes/matters/tags.ts')",
  "name": "Tags",
  "parameters": {
    "tid": "Tag id, can be found in the url of the tag page"
  },
  "path": "/tags/:tid",
  "radar": [
    {
      "source": [
        "matters.town/tags/:tid"
      ]
    }
  ]
}
```
