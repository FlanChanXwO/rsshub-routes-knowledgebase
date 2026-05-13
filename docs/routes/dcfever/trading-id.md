# DCFever - 二手市集

## Coverage
`index-only`

## Route
- Namespace: `dcfever`
- Namespace Name: `DCFever`
- Route Path: `/trading/:id`
- Route Name: `二手市集`
- Example: `/dcfever/trading/1`
- URL: `dcfever.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `trading.ts`
- Source Module: `() => import('@/routes/dcfever/trading.ts')`

## Description
[所有物品分類](https://www.dcfever.com/trading/index.php#all_cats)

| 攝影產品 | 電腦 | 手機通訊 | 影音產品 | 遊戲機、模型 | 電器傢俱 | 潮流服飾 | 手錶 | 單車及運動 | 其它 |
| -------- | ---- | -------- | -------- | ------------ | -------- | -------- | ---- | ---------- | ---- |
| 1        | 2    | 3        | 44       | 43           | 104      | 45       | 99   | 109        | 4    |

## Parameters
- `id`: 分類 ID，見下表


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "[所有物品分類](https://www.dcfever.com/trading/index.php#all_cats)\n\n| 攝影產品 | 電腦 | 手機通訊 | 影音產品 | 遊戲機、模型 | 電器傢俱 | 潮流服飾 | 手錶 | 單車及運動 | 其它 |\n| -------- | ---- | -------- | -------- | ------------ | -------- | -------- | ---- | ---------- | ---- |\n| 1        | 2    | 3        | 44       | 43           | 104      | 45       | 99   | 109        | 4    |",
  "example": "/dcfever/trading/1",
  "location": "trading.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/dcfever/trading.ts')",
  "name": "二手市集",
  "parameters": {
    "id": "分類 ID，見下表"
  },
  "path": "/trading/:id"
}
```
