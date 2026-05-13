# 三联生活周刊 - Unknown

## Coverage
`index-only`

## Route
- Namespace: `lifeweek`
- Namespace Name: `三联生活周刊`
- Route Path: `/channel/:id`
- Route Name: `Unknown`
- Example: `_None_`
- URL: `lifeweek.com.cn`
- Language: `zh-CN`
- Categories: `None`
- Maintainers: `None`
- Source Location: `channel.ts`
- Source Module: `() => import('@/routes/lifeweek/channel.ts')`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `lifeweek.com.cn/column/:channel`
- `target`: `/channel/:channel`

## Raw JSON
```json
{
  "location": "channel.ts",
  "maintainers": [],
  "module": "() => import('@/routes/lifeweek/channel.ts')",
  "name": "Unknown",
  "path": "/channel/:id",
  "radar": [
    {
      "source": [
        "lifeweek.com.cn/column/:channel"
      ],
      "target": "/channel/:channel"
    }
  ]
}
```
