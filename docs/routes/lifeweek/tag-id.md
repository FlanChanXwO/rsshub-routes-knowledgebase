# 三联生活周刊 - Unknown

## Coverage
`index-only`

## Route
- Namespace: `lifeweek`
- Namespace Name: `三联生活周刊`
- Route Path: `/tag/:id`
- Route Name: `Unknown`
- Example: `_None_`
- URL: `lifeweek.com.cn`
- Language: `zh-CN`
- Categories: `None`
- Maintainers: `None`
- Source Location: `tag.ts`
- Source Module: `() => import('@/routes/lifeweek/tag.ts')`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `lifeweek.com.cn/articleList/:tag`
- `target`: `/tag/:tag`

## Raw JSON
```json
{
  "location": "tag.ts",
  "maintainers": [],
  "module": "() => import('@/routes/lifeweek/tag.ts')",
  "name": "Unknown",
  "path": "/tag/:id",
  "radar": [
    {
      "source": [
        "lifeweek.com.cn/articleList/:tag"
      ],
      "target": "/tag/:tag"
    }
  ]
}
```
