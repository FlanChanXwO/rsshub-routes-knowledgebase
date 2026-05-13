# Mashiro's Baumkuchen - Blog

## Coverage
`index-only`

## Route
- Namespace: `mashiro`
- Namespace Name: `Mashiro's Baumkuchen`
- Route Path: `/:lang`
- Route Name: `Blog`
- Example: `/mashiro/en`
- URL: `mashiro.best`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `MuenYu`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/mashiro/index.ts')`

## Description
_None_

## Parameters
- `lang`: the language of the site. Can be either `en` or `zh-cn`. Default: `en`


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `mashiro.best/`
  - `mashiro.best/:lang/`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/mashiro/en",
  "location": "index.ts",
  "maintainers": [
    "MuenYu"
  ],
  "module": "() => import('@/routes/mashiro/index.ts')",
  "name": "Blog",
  "parameters": {
    "lang": "the language of the site. Can be either `en` or `zh-cn`. Default: `en`"
  },
  "path": "/:lang",
  "radar": [
    {
      "source": [
        "mashiro.best/",
        "mashiro.best/:lang/"
      ]
    }
  ]
}
```
