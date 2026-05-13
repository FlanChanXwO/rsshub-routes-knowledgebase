# Esquire Hong Kong - Tag

## Coverage
`index-only`

## Route
- Namespace: `esquirehk`
- Namespace Name: `Esquire Hong Kong`
- Route Path: `/tag/:id?`
- Route Name: `Tag`
- Example: `/esquirehk/tag/Fashion`
- URL: `www.esquirehk.com`
- Language: `zh-HK`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `tag.tsx`
- Source Module: `() => import('@/routes/esquirehk/tag.tsx')`

## Description
_None_

## Parameters
- `id`: 标签，可在对应标签页 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.esquirehk.com/tag/:id`
  - `www.esquirehk.com/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/esquirehk/tag/Fashion",
  "location": "tag.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/esquirehk/tag.tsx')",
  "name": "Tag",
  "parameters": {
    "id": "标签，可在对应标签页 URL 中找到"
  },
  "path": "/tag/:id?",
  "radar": [
    {
      "source": [
        "www.esquirehk.com/tag/:id",
        "www.esquirehk.com/:id"
      ]
    }
  ]
}
```
