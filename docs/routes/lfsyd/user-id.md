# 旅法师营地 - Unknown

## Coverage
`index-only`

## Route
- Namespace: `lfsyd`
- Namespace Name: `旅法师营地`
- Route Path: `/user/:id?`
- Route Name: `Unknown`
- Example: `_None_`
- URL: `www.iyingdi.com`
- Language: `zh-CN`
- Categories: `None`
- Maintainers: `auto-bot-ty`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/lfsyd/user.ts')`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.iyingdi.com/tz/people/:id`
  - `www.iyingdi.com/tz/people/:id/*`
- `target`: `/user/:id`

## Raw JSON
```json
{
  "location": "user.ts",
  "maintainers": [
    "auto-bot-ty"
  ],
  "module": "() => import('@/routes/lfsyd/user.ts')",
  "name": "Unknown",
  "path": "/user/:id?",
  "radar": [
    {
      "source": [
        "www.iyingdi.com/tz/people/:id",
        "www.iyingdi.com/tz/people/:id/*"
      ],
      "target": "/user/:id"
    }
  ]
}
```
