# 联合早报 - 即时新闻

## Coverage
`index-only`

## Route
- Namespace: `zaobao`
- Namespace Name: `联合早报`
- Route Path: `/realtime/:section?`
- Route Name: `即时新闻`
- Example: `/zaobao/realtime/china`
- URL: `www.zaobao.com`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `shunf4`
- Source Location: `realtime.ts`
- Source Module: `() => import('@/routes/zaobao/realtime.ts')`

## Description
| 中国  | 新加坡    | 国际  | 财经     |
| ----- | --------- | ----- | -------- |
| china | singapore | world | zfinance |

## Parameters
- `section`: 分类，缺省为 china


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 中国  | 新加坡    | 国际  | 财经     |\n| ----- | --------- | ----- | -------- |\n| china | singapore | world | zfinance |",
  "example": "/zaobao/realtime/china",
  "location": "realtime.ts",
  "maintainers": [
    "shunf4"
  ],
  "module": "() => import('@/routes/zaobao/realtime.ts')",
  "name": "即时新闻",
  "parameters": {
    "section": "分类，缺省为 china"
  },
  "path": "/realtime/:section?"
}
```
