# 懂球帝 - 专题

## Coverage
`index-only`

## Route
- Namespace: `dongqiudi`
- Namespace Name: `懂球帝`
- Route Path: `/special/:id`
- Route Name: `专题`
- Example: `/dongqiudi/special/41`
- URL: `m.dongqiudi.com`
- Language: `zh-CN`
- Categories: `sport`
- Maintainers: `dxmpalb`
- Source Location: `special.ts`
- Source Module: `() => import('@/routes/dongqiudi/special.ts')`

## Description
| 新闻大爆炸 | 懂球帝十佳球 | 懂球帝本周 MVP |
| ---------- | ------------ | -------------- |
| 41         | 52           | 53             |

## Parameters
- `id`: 专题 id, 可自行通过 https://www.dongqiudi.com/special/+数字匹配


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.dongqiudi.com/special/:id`

## Raw JSON
```json
{
  "categories": [
    "sport"
  ],
  "description": "| 新闻大爆炸 | 懂球帝十佳球 | 懂球帝本周 MVP |\n| ---------- | ------------ | -------------- |\n| 41         | 52           | 53             |",
  "example": "/dongqiudi/special/41",
  "location": "special.ts",
  "maintainers": [
    "dxmpalb"
  ],
  "module": "() => import('@/routes/dongqiudi/special.ts')",
  "name": "专题",
  "parameters": {
    "id": "专题 id, 可自行通过 https://www.dongqiudi.com/special/+数字匹配"
  },
  "path": "/special/:id",
  "radar": [
    {
      "source": [
        "www.dongqiudi.com/special/:id"
      ]
    }
  ]
}
```
