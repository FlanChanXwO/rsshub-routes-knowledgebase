# IEEE Xplore - IEEE Journal Articles

## Coverage
`index-only`

## Route
- Namespace: `ieee`
- Namespace Name: `IEEE Xplore`
- Route Path: `/journal/:punumber/:earlyAccess?`
- Route Name: `IEEE Journal Articles`
- Example: `/ieee/journal/6287639/preprint`
- URL: `www.ieee.org`
- Language: `en`
- Categories: `journal`
- Maintainers: `HenryQW`
- Source Location: `journal.ts`
- Source Module: `() => import('@/routes/ieee/journal.ts')`

## Description
_None_

## Parameters
- `punumber`: Publication Number, look for `punumber` in the URL
- `earlyAccess`: Optional, set any value to get early access articles


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/ieee/journal/6287639/preprint",
  "location": "journal.ts",
  "maintainers": [
    "HenryQW"
  ],
  "module": "() => import('@/routes/ieee/journal.ts')",
  "name": "IEEE Journal Articles",
  "parameters": {
    "earlyAccess": "Optional, set any value to get early access articles",
    "punumber": "Publication Number, look for `punumber` in the URL"
  },
  "path": "/journal/:punumber/:earlyAccess?"
}
```
