# Wellcee 唯心所寓 - 租房信息

## Coverage
`index-only`

## Route
- Namespace: `wellcee`
- Namespace Name: `Wellcee 唯心所寓`
- Route Path: `/rent/:city/:district?`
- Route Name: `租房信息`
- Example: `/wellcee/rent/北京`
- URL: `www.wellcee.com`
- Language: `zh-CN`
- Categories: `other`
- Maintainers: `TonyRL`
- Source Location: `rent.tsx`
- Source Module: `() => import('@/routes/wellcee/rent.tsx')`

## Description
支持的城市可以通过 [/wellcee/support-city](https://rsshub.app/wellcee/support-city) 获取

## Parameters
- `city`: 城市
- `district`: 地区


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "description": "支持的城市可以通过 [/wellcee/support-city](https://rsshub.app/wellcee/support-city) 获取",
  "example": "/wellcee/rent/北京",
  "location": "rent.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/wellcee/rent.tsx')",
  "name": "租房信息",
  "parameters": {
    "city": "城市",
    "district": "地区"
  },
  "path": "/rent/:city/:district?",
  "url": "www.wellcee.com"
}
```
