# 观察者网 - Unknown

## Coverage
`index-only`

## Route
- Namespace: `guancha`
- Namespace Name: `观察者网`
- Route Path: `/topic/:id/:order?`
- Route Name: `Unknown`
- Example: `_None_`
- URL: `guancha.cn/`
- Language: `zh-CN`
- Categories: `None`
- Maintainers: `occupy5, nczitzk`
- Source Location: `topic.ts`
- Source Module: `() => import('@/routes/guancha/topic.ts')`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `guancha.cn/`
- `target`: `/:category?`

## Raw JSON
```json
{
  "location": "topic.ts",
  "maintainers": [
    "occupy5",
    "nczitzk"
  ],
  "module": "() => import('@/routes/guancha/topic.ts')",
  "name": "Unknown",
  "path": "/topic/:id/:order?",
  "radar": [
    {
      "source": [
        "guancha.cn/"
      ],
      "target": "/:category?"
    }
  ],
  "url": "guancha.cn/"
}
```
