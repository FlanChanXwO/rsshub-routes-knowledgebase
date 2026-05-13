# Cara - Portfolio

## Coverage
`index-only`

## Route
- Namespace: `cara`
- Namespace Name: `Cara`
- Route Path: `/portfolio/:user`
- Route Name: `Portfolio`
- Example: `/cara/portfolio/fengz`
- URL: `cara.app`
- Language: `en`
- Categories: `social-media`
- Maintainers: `KarasuShin`
- Source Location: `portfolio.ts`
- Source Module: `() => import('@/routes/cara/portfolio.ts')`

## Description
_None_

## Parameters
- `user`: username


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `cara.app/:user`
  - `cara.app/:user/*`
- `target`: `/portfolio/:user`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/cara/portfolio/fengz",
  "location": "portfolio.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "module": "() => import('@/routes/cara/portfolio.ts')",
  "name": "Portfolio",
  "parameters": {
    "user": "username"
  },
  "path": [
    "/portfolio/:user"
  ],
  "radar": [
    {
      "source": [
        "cara.app/:user",
        "cara.app/:user/*"
      ],
      "target": "/portfolio/:user"
    }
  ]
}
```
