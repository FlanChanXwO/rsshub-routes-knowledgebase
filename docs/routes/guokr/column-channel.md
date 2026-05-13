# 果壳网 - 果壳网专栏

## Coverage
`index-only`

## Route
- Namespace: `guokr`
- Namespace Name: `果壳网`
- Route Path: `/column/:channel`
- Route Name: `果壳网专栏`
- Example: `/guokr/column/calendar`
- URL: `guokr.com/`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `DHPO, hoilc`
- Source Location: `channel.ts`
- Source Module: `() => import('@/routes/guokr/channel.ts')`

## Description
| 物种日历 | 吃货研究所 | 美丽也是技术活 |
| -------- | ---------- | -------------- |
| calendar | institute  | beauty         |

## Parameters
- `channel`: 专栏类别


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `guokr.com/:channel`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 物种日历 | 吃货研究所 | 美丽也是技术活 |\n| -------- | ---------- | -------------- |\n| calendar | institute  | beauty         |",
  "example": "/guokr/column/calendar",
  "location": "channel.ts",
  "maintainers": [
    "DHPO",
    "hoilc"
  ],
  "module": "() => import('@/routes/guokr/channel.ts')",
  "name": "果壳网专栏",
  "parameters": {
    "channel": "专栏类别"
  },
  "path": "/column/:channel",
  "radar": [
    {
      "source": [
        "guokr.com/:channel"
      ]
    }
  ],
  "url": "guokr.com/"
}
```
