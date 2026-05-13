# NPM - Package

## Coverage
`index-only`

## Route
- Namespace: `npm`
- Namespace Name: `NPM`
- Route Path: `/package/:name{(@[a-z0-9-~][a-z0-9-._~]*/)?[a-z0-9-~][a-z0-9-._~]*}`
- Route Name: `Package`
- Example: `/npm/package/rsshub`
- URL: `npmjs.com`
- Language: `en`
- Categories: `program-update`
- Maintainers: `Fatpandac`
- Source Location: `package.tsx`
- Source Module: `() => import('@/routes/npm/package.tsx')`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.npmjs.com/package/:name`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/npm/package/rsshub",
  "location": "package.tsx",
  "maintainers": [
    "Fatpandac"
  ],
  "module": "() => import('@/routes/npm/package.tsx')",
  "name": "Package",
  "path": "/package/:name{(@[a-z0-9-~][a-z0-9-._~]*/)?[a-z0-9-~][a-z0-9-._~]*}",
  "radar": [
    {
      "source": [
        "www.npmjs.com/package/:name"
      ]
    }
  ]
}
```
