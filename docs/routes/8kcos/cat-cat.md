# 8KCosplay - 分类

## Coverage
`index-only`

## Route
- Namespace: `8kcos`
- Namespace Name: `8KCosplay`
- Route Path: `/cat/:cat?`
- Route Name: `分类`
- Example: `/8kcos/cat/8kasianidol`
- URL: `8kcosplay.com/`
- Language: `zh-CN`
- Categories: `None`
- Maintainers: `KotoriK`
- Source Location: `cat.ts`
- Source Module: `() => import('@/routes/8kcos/cat.ts')`

## Description
_None_

## Parameters
- `cat`: 默认值为 `8kasianidol`，将目录页面url中 /category/ 后面的部分填入。如：https://www.8kcosplay.com/category/8kchineseidol/%e9%a3%8e%e4%b9%8b%e9%a2%86%e5%9f%9f/ 对应的RSS页面为 /8kcos/cat/%e9%a3%8e%e4%b9%8b%e9%a2%86%e5%9f%9f。


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `8kcosplay.com/category/:mainCategory/:cat/`
  - `8kcosplay.com/category/:cat/`
- `target`: `/cat/:cat`

## Raw JSON
```json
{
  "example": "/8kcos/cat/8kasianidol",
  "features": {
    "nsfw": true
  },
  "location": "cat.ts",
  "maintainers": [
    "KotoriK"
  ],
  "module": "() => import('@/routes/8kcos/cat.ts')",
  "name": "分类",
  "parameters": {
    "cat": "默认值为 `8kasianidol`，将目录页面url中 /category/ 后面的部分填入。如：https://www.8kcosplay.com/category/8kchineseidol/%e9%a3%8e%e4%b9%8b%e9%a2%86%e5%9f%9f/ 对应的RSS页面为 /8kcos/cat/%e9%a3%8e%e4%b9%8b%e9%a2%86%e5%9f%9f。"
  },
  "path": "/cat/:cat?",
  "radar": [
    {
      "source": [
        "8kcosplay.com/category/:mainCategory/:cat/",
        "8kcosplay.com/category/:cat/"
      ],
      "target": "/cat/:cat"
    }
  ],
  "url": "8kcosplay.com/"
}
```
