# Alpine Linux - Packages

## Coverage
`index-only`

## Route
- Namespace: `alpinelinux`
- Namespace Name: `Alpine Linux`
- Route Path: `/pkgs/:name/:routeParams?`
- Route Name: `Packages`
- Example: `/alpinelinux/pkgs/nodejs`
- URL: `alpinelinux.org`
- Language: `en`
- Categories: `program-update`
- Maintainers: `CaoMeiYouRen`
- Source Location: `pkgs.ts`
- Source Module: `() => import('@/routes/alpinelinux/pkgs.ts')`

## Description
Alpine Linux packages update

## Parameters
- `name`: Packages name
- `routeParams`: Filters of packages type. E.g. branch=edge&repo=main&arch=armv7&maintainer=Jakub%20Jirutka


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `https://pkgs.alpinelinux.org/packages`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "Alpine Linux packages update",
  "example": "/alpinelinux/pkgs/nodejs",
  "location": "pkgs.ts",
  "maintainers": [
    "CaoMeiYouRen"
  ],
  "module": "() => import('@/routes/alpinelinux/pkgs.ts')",
  "name": "Packages",
  "parameters": {
    "name": "Packages name",
    "routeParams": "Filters of packages type. E.g. branch=edge&repo=main&arch=armv7&maintainer=Jakub%20Jirutka"
  },
  "path": "/pkgs/:name/:routeParams?",
  "radar": [
    {
      "source": [
        "https://pkgs.alpinelinux.org/packages"
      ]
    }
  ],
  "zh": {
    "description": "Alpine Linux 软件包更新",
    "name": "软件包"
  }
}
```
