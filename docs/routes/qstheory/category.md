# 求是网 - 分类

## Coverage
`index-only`

## Route
- Namespace: `qstheory`
- Namespace Name: `求是网`
- Route Path: `/:category?`
- Route Name: `分类`
- Example: `/qstheory`
- URL: `www.qstheory.cn`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/qstheory/index.ts')`

## Description
| 头条    | 网评 | 视频 | 原创   | 经济    | 政治     | 文化    | 社会    | 党建 | 科教    | 生态    | 国防    | 国际          | 图书  | 学习笔记 | 理论文选 |
| ------- | ---- | ---- | ------ | ------- | -------- | ------- | ------- | ---- | ------- | ------- | ------- | ------------- | ----- | -------- | -------- |
| toutiao | qswp | qssp | qslgxd | economy | politics | culture | society | cpc  | science | zoology | defense | international | books | xxbj     | llwx     |

## Parameters
- `industry`: 分类，见下表


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.qstheory.cn/v9zhuanqu/:category/index.htm`
  - `www.qstheory.cn/qszq/:category/index.htm`
  - `www.qstheory.cn/:category/index.htm`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "\n| 头条    | 网评 | 视频 | 原创   | 经济    | 政治     | 文化    | 社会    | 党建 | 科教    | 生态    | 国防    | 国际          | 图书  | 学习笔记 | 理论文选 |\n| ------- | ---- | ---- | ------ | ------- | -------- | ------- | ------- | ---- | ------- | ------- | ------- | ------------- | ----- | -------- | -------- |\n| toutiao | qswp | qssp | qslgxd | economy | politics | culture | society | cpc  | science | zoology | defense | international | books | xxbj     | llwx     |",
  "example": "/qstheory",
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/qstheory/index.ts')",
  "name": "分类",
  "parameters": {
    "industry": "分类，见下表"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "www.qstheory.cn/v9zhuanqu/:category/index.htm",
        "www.qstheory.cn/qszq/:category/index.htm",
        "www.qstheory.cn/:category/index.htm"
      ]
    }
  ]
}
```
