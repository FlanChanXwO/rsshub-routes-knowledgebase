# MakerWorld - User Uploads

## Coverage
`index-only`

## Route
- Namespace: `makerworld`
- Namespace Name: `MakerWorld`
- Route Path: `/user/:handle/upload`
- Route Name: `User Uploads`
- Example: `/makerworld/user/@Wcad00/upload`
- URL: `makerworld.com`
- Language: `en`
- Categories: `design`
- Maintainers: `TonyRL`
- Source Location: `user-upload.ts`
- Source Module: `() => import('@/routes/makerworld/user-upload.ts')`

## Description
_None_

## Parameters
- `handle`: User handle


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `makerworld.com/:lang/:handle/upload`
  - `makerworld.com/:lang/:handle`

## Raw JSON
```json
{
  "categories": [
    "design"
  ],
  "example": "/makerworld/user/@Wcad00/upload",
  "location": "user-upload.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/makerworld/user-upload.ts')",
  "name": "User Uploads",
  "parameters": {
    "handle": "User handle"
  },
  "path": "/user/:handle/upload",
  "radar": [
    {
      "source": [
        "makerworld.com/:lang/:handle/upload",
        "makerworld.com/:lang/:handle"
      ]
    }
  ]
}
```
