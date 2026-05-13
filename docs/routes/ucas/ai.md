# 中国科学院大学 - 人工智能学院

## Coverage
`index-only`

## Route
- Namespace: `ucas`
- Namespace Name: `中国科学院大学`
- Route Path: `/ai`
- Route Name: `人工智能学院`
- Example: `/ucas/ai`
- URL: `ai.ucas.ac.cn/index.php/zh-cn/tzgg`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `shengmaosu`
- Source Location: `ai.ts`
- Source Module: `() => import('@/routes/ucas/ai.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `ai.ucas.ac.cn/index.php/zh-cn/tzgg`
  - `ai.ucas.ac.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/ucas/ai",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "ai.ts",
  "maintainers": [
    "shengmaosu"
  ],
  "module": "() => import('@/routes/ucas/ai.ts')",
  "name": "人工智能学院",
  "parameters": {},
  "path": "/ai",
  "radar": [
    {
      "source": [
        "ai.ucas.ac.cn/index.php/zh-cn/tzgg",
        "ai.ucas.ac.cn/"
      ]
    }
  ],
  "url": "ai.ucas.ac.cn/index.php/zh-cn/tzgg"
}
```
