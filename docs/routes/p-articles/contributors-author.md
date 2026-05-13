# 虚词 - 虛詞作者

## Coverage
`index-only`

## Route
- Namespace: `p-articles`
- Namespace Name: `虚词`
- Route Path: `/contributors/:author`
- Route Name: `虛詞作者`
- Example: `/p-articles/contributors/黃衍仁`
- URL: `p-articles.com`
- Language: `en`
- Categories: `reading`
- Maintainers: `Insomnia1437`
- Source Location: `contributors.ts`
- Source Module: `() => import('@/routes/p-articles/contributors.ts')`

## Description
_None_

## Parameters
- `author`: 虛詞作者, 可在作者页面 URL 找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `p-articles.com/contributors/:author`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/p-articles/contributors/黃衍仁",
  "location": "contributors.ts",
  "maintainers": [
    "Insomnia1437"
  ],
  "module": "() => import('@/routes/p-articles/contributors.ts')",
  "name": "虛詞作者",
  "parameters": {
    "author": "虛詞作者, 可在作者页面 URL 找到"
  },
  "path": "/contributors/:author",
  "radar": [
    {
      "source": [
        "p-articles.com/contributors/:author"
      ]
    }
  ]
}
```
