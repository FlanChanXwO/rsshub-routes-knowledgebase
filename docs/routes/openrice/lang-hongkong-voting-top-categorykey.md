# Openrice開飯喇 - OpenRice 開飯熱店 - 年度餐廳投票

## Coverage
`index-only`

## Route
- Namespace: `openrice`
- Namespace Name: `Openrice開飯喇`
- Route Path: `/:lang/hongkong/voting/top/:categoryKey`
- Route Name: `OpenRice 開飯熱店 - 年度餐廳投票`
- Example: `/openrice/zh/hongkong/voting/top/chinese`
- URL: `www.openrice.com`
- Language: `zh-HK`
- Categories: `shopping`
- Maintainers: `after9`
- Source Location: `voting.ts`
- Source Module: `() => import('@/routes/openrice/voting.ts')`

## Description
lang: 语言，见下方列表
| 简体 | 繁體 | EN |
| ----- | ------ | ----- |
| zh-cn | zh | en |

  categoryKey: 部分类别，见下方列表 (更多的类别可以在页面的link中对照获取)
| 中菜館 | 上海菜 | 粵菜 | 川菜 | 港式 | 粥粉麵店 | 廚師發辦 | 韓國菜 | 泰國菜 | 越南菜 |
| -------- | -------- | -------- |  -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| chinese | shanghainese | guangdong | sichuan | hkstyle | congee_noodles | omakase | korean | thai | vietnamese |

## Parameters
- `lang`: 语言，缺省为 zh
- `categoryKey`: 类别，缺省为 chinese


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "\n  lang: 语言，见下方列表\n| 简体 | 繁體 | EN |\n| ----- | ------ | ----- |\n| zh-cn | zh | en |\n\n  categoryKey: 部分类别，见下方列表 (更多的类别可以在页面的link中对照获取)\n| 中菜館 | 上海菜 | 粵菜 | 川菜 | 港式 | 粥粉麵店 | 廚師發辦 | 韓國菜 | 泰國菜 | 越南菜 |\n| -------- | -------- | -------- |  -------- | -------- | -------- | -------- | -------- | -------- | -------- |\n| chinese | shanghainese | guangdong | sichuan | hkstyle | congee_noodles | omakase | korean | thai | vietnamese |\n  ",
  "example": "/openrice/zh/hongkong/voting/top/chinese",
  "location": "voting.ts",
  "maintainers": [
    "after9"
  ],
  "module": "() => import('@/routes/openrice/voting.ts')",
  "name": "OpenRice 開飯熱店 - 年度餐廳投票",
  "parameters": {
    "categoryKey": "类别，缺省为 chinese",
    "lang": "语言，缺省为 zh"
  },
  "path": "/:lang/hongkong/voting/top/:categoryKey"
}
```
