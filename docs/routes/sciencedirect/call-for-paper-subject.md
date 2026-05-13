# ScienceDirect - Call for Papers

## Coverage
`index-only`

## Route
- Namespace: `sciencedirect`
- Namespace Name: `ScienceDirect`
- Route Path: `/call-for-paper/:subject`
- Route Name: `Call for Papers`
- Example: `/sciencedirect/call-for-paper/education`
- URL: `sciencedirect.com/browse/calls-for-papers`
- Language: `en`
- Categories: `journal`
- Maintainers: `etShaw-zh`
- Source Location: `call-for-paper.tsx`
- Source Module: `() => import('@/routes/sciencedirect/call-for-paper.tsx')`

## Description
`sciencedirect.com/browse/calls-for-papers?subject=education` -> `/sciencedirect/call-for-paper/education`

## Parameters
- `subject`: 学科分类，例如“education”


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `sciencedirect.com`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "`sciencedirect.com/browse/calls-for-papers?subject=education` -> `/sciencedirect/call-for-paper/education`",
  "example": "/sciencedirect/call-for-paper/education",
  "location": "call-for-paper.tsx",
  "maintainers": [
    "etShaw-zh"
  ],
  "module": "() => import('@/routes/sciencedirect/call-for-paper.tsx')",
  "name": "Call for Papers",
  "parameters": {
    "subject": "学科分类，例如“education”"
  },
  "path": "/call-for-paper/:subject",
  "radar": [
    {
      "source": [
        "sciencedirect.com"
      ]
    }
  ],
  "url": "sciencedirect.com/browse/calls-for-papers"
}
```
