# Link Research - Articles

## Coverage
`index-only`

## Route
- Namespace: `linkresearcher`
- Namespace Name: `Link Research`
- Route Path: `/:params`
- Route Name: `Articles`
- Example: `/linkresearcher/category=theses&columns=Nature%20导读&subject=生物`
- URL: `www.linkresearcher.com`
- Language: `zh-CN`
- Categories: `journal`
- Maintainers: `y9c, KarasuShin`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/linkresearcher/index.tsx')`

## Description
_None_

## Parameters
- `params`: {"description": "search parameters, support `category`, `subject`, `columns`, `query`"}


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
  "example": "/linkresearcher/category=theses&columns=Nature%20导读&subject=生物",
  "location": "index.tsx",
  "maintainers": [
    "y9c",
    "KarasuShin"
  ],
  "module": "() => import('@/routes/linkresearcher/index.tsx')",
  "name": "Articles",
  "parameters": {
    "params": {
      "description": "search parameters, support `category`, `subject`, `columns`, `query`"
    }
  },
  "path": "/:params",
  "view": 0,
  "zh": {
    "name": "文章"
  },
  "zh-TW": {
    "name": "文章"
  }
}
```
