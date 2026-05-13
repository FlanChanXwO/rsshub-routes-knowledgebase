# 创业邦 - Unknown

## Coverage
`index-only`

## Route
- Namespace: `cyzone`
- Namespace Name: `创业邦`
- Route Path: `/channel/:id?`
- Route Name: `Unknown`
- Example: `_None_`
- URL: `cyzone.cn`
- Language: `zh-CN`
- Categories: `None`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/cyzone/index.ts')`

## Description
| 最新 | 快鲤鱼 | 创投 | 科创板 | 汽车 |
| ---- | ------ | ---- | ------ | ---- |
| news | 5      | 14   | 13     | 8    |

| 海外 | 消费 | 科技 | 医疗 | 文娱 |
| ---- | ---- | ---- | ---- | ---- |
| 10   | 9    | 7    | 27   | 11   |

| 城市 | 政策 | 特写 | 干货 | 科技股 |
| ---- | ---- | ---- | ---- | ------ |
| 16   | 15   | 6    | 12   | 33     |

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `cyzone.cn/channel/:id`
  - `cyzone.cn/`
- `target`: `/:id`

## Raw JSON
```json
{
  "description": "| 最新 | 快鲤鱼 | 创投 | 科创板 | 汽车 |\n| ---- | ------ | ---- | ------ | ---- |\n| news | 5      | 14   | 13     | 8    |\n\n| 海外 | 消费 | 科技 | 医疗 | 文娱 |\n| ---- | ---- | ---- | ---- | ---- |\n| 10   | 9    | 7    | 27   | 11   |\n\n| 城市 | 政策 | 特写 | 干货 | 科技股 |\n| ---- | ---- | ---- | ---- | ------ |\n| 16   | 15   | 6    | 12   | 33     |",
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/cyzone/index.ts')",
  "name": "Unknown",
  "path": [
    "/channel/:id?",
    "/:id?"
  ],
  "radar": [
    {
      "source": [
        "cyzone.cn/channel/:id",
        "cyzone.cn/"
      ],
      "target": "/:id"
    }
  ]
}
```
