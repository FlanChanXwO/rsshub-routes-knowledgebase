# NOSEC 安全讯息平台 - Posts

## Coverage
`index-only`

## Route
- Namespace: `nosec`
- Namespace Name: `NOSEC 安全讯息平台`
- Route Path: `/:keykind?`
- Route Name: `Posts`
- Example: `/nosec/hole`
- URL: `nosec.org`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `hellodword`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/nosec/index.ts')`

## Description
| 分类     | 标识       |
| :------- | :--------- |
| 威胁情报 | `threaten` |
| 安全动态 | `security` |
| 漏洞预警 | `hole`     |
| 数据泄露 | `leakage`  |
| 专题报告 | `speech`   |
| 技术分析 | `skill`    |
| 安全工具 | `tool`     |

## Parameters
- `keykind`: 对应文章分类


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `nosec.org/home/index/:keykind`
  - `nosec.org/home/index`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "| 分类     | 标识       |\n| :------- | :--------- |\n| 威胁情报 | `threaten` |\n| 安全动态 | `security` |\n| 漏洞预警 | `hole`     |\n| 数据泄露 | `leakage`  |\n| 专题报告 | `speech`   |\n| 技术分析 | `skill`    |\n| 安全工具 | `tool`     |",
  "example": "/nosec/hole",
  "location": "index.ts",
  "maintainers": [
    "hellodword"
  ],
  "module": "() => import('@/routes/nosec/index.ts')",
  "name": "Posts",
  "parameters": {
    "keykind": "对应文章分类"
  },
  "path": "/:keykind?",
  "radar": [
    {
      "source": [
        "nosec.org/home/index/:keykind",
        "nosec.org/home/index"
      ]
    }
  ]
}
```
