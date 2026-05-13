# Chiphell - 分类

## Coverage
`index-only`

## Route
- Namespace: `chiphell`
- Namespace Name: `Chiphell`
- Route Path: `/portal/:catId?`
- Route Name: `分类`
- Example: `/chiphell/portal/1`
- URL: `www.chiphell.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `tylinux`
- Source Location: `portal.ts`
- Source Module: `() => import('@/routes/chiphell/portal.ts')`

## Description
_None_

## Parameters
- `catId`: 分类 ID，可在 URL 中找到，默认为 1


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/chiphell/portal/1",
  "location": "portal.ts",
  "maintainers": [
    "tylinux"
  ],
  "module": "() => import('@/routes/chiphell/portal.ts')",
  "name": "分类",
  "parameters": {
    "catId": "分类 ID，可在 URL 中找到，默认为 1"
  },
  "path": "/portal/:catId?"
}
```
