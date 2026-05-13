# 共产党员网 - 最新发布

## Coverage
`index-only`

## Route
- Namespace: `12371`
- Namespace Name: `共产党员网`
- Route Path: `/:category?`
- Route Name: `最新发布`
- Example: `/12371/zxfb`
- URL: `www.12371.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `zvrr`
- Source Location: `zxfb.ts`
- Source Module: `() => import('@/routes/12371/zxfb.ts')`

## Description
| 最新发布 |
| :------: |
|   zxfb   |

## Parameters
- `category`: 新闻分类名，预设 `zxfb`


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.12371.cn/:category`

## Raw JSON
```json
{
  "description": "| 最新发布 |\n| :------: |\n|   zxfb   |",
  "example": "/12371/zxfb",
  "location": "zxfb.ts",
  "maintainers": [
    "zvrr"
  ],
  "module": "() => import('@/routes/12371/zxfb.ts')",
  "name": "最新发布",
  "parameters": {
    "category": "新闻分类名，预设 `zxfb`"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "www.12371.cn/:category"
      ]
    }
  ],
  "url": "www.12371.cn"
}
```
