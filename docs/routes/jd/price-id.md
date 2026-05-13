# 京东 - 商品价格

## Coverage
`index-only`

## Route
- Namespace: `jd`
- Namespace Name: `京东`
- Route Path: `/price/:id`
- Route Name: `商品价格`
- Example: `/jd/price/526835`
- URL: `item.jd.com`
- Language: `zh-CN`
- Categories: `shopping`
- Maintainers: `nczitzk`
- Source Location: `price.tsx`
- Source Module: `() => import('@/routes/jd/price.tsx')`

## Description
::: tip
  如商品 `https://item.jd.com/526835.html` 中的 id 为 `526835`，所以路由为 [`/jd/price/526835`](https://rsshub.app/jd/price/526835)
:::

## Parameters
- `id`: 商品 id，可在商品详情页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "::: tip\n  如商品 `https://item.jd.com/526835.html` 中的 id 为 `526835`，所以路由为 [`/jd/price/526835`](https://rsshub.app/jd/price/526835)\n:::",
  "example": "/jd/price/526835",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "price.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/jd/price.tsx')",
  "name": "商品价格",
  "parameters": {
    "id": "商品 id，可在商品详情页 URL 中找到"
  },
  "path": "/price/:id"
}
```
