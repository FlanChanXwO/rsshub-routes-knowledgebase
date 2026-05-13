# 4k 世界 - 分类

## Coverage
`index-only`

## Route
- Namespace: `4ksj`
- Namespace Name: `4k 世界`
- Route Path: `/:id?`
- Route Name: `分类`
- Example: `/4ksj/4k-uhd-1`
- URL: `4ksj.com`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `forum.tsx`
- Source Module: `() => import('@/routes/4ksj/forum.tsx')`

## Description
::: tip
  若订阅 [最新 4K 电影](https://www.4ksj.com/4k-uhd-1.html)，网址为 `https://www.4ksj.com/4k-uhd-1.html`。截取 `https://www.4ksj.com/` 到末尾 `.html` 的部分 `4k-uhd-1` 作为参数，此时路由为 [`/4ksj/4k-uhd-1`](https://rsshub.app/4ksj/4k-uhd-1)。

  若订阅子分类 [Dolby Vision 动作 4K 电影](https://www.4ksj.com/4k-uhd-s7-display-3-dytypes-1-1.html)，网址为 `https://www.4ksj.com/4k-uhd-s7-display-3-dytypes-1-1.html`。截取 `https://www.4ksj.com/forum-` 到末尾 `.html` 的部分 `4kdianying-s7-dianyingbiaozhun-3-dytypes-9-1` 作为参数，此时路由为 [`/4ksj/4k-uhd-s7-display-3-dytypes-1-1`](https://rsshub.app/4ksj/4k-uhd-s7-display-3-dytypes-1-1)。
:::

## Parameters
- `id`: 分类 id，默认为最新4K电影


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "::: tip\n  若订阅 [最新 4K 电影](https://www.4ksj.com/4k-uhd-1.html)，网址为 `https://www.4ksj.com/4k-uhd-1.html`。截取 `https://www.4ksj.com/` 到末尾 `.html` 的部分 `4k-uhd-1` 作为参数，此时路由为 [`/4ksj/4k-uhd-1`](https://rsshub.app/4ksj/4k-uhd-1)。\n\n  若订阅子分类 [Dolby Vision 动作 4K 电影](https://www.4ksj.com/4k-uhd-s7-display-3-dytypes-1-1.html)，网址为 `https://www.4ksj.com/4k-uhd-s7-display-3-dytypes-1-1.html`。截取 `https://www.4ksj.com/forum-` 到末尾 `.html` 的部分 `4kdianying-s7-dianyingbiaozhun-3-dytypes-9-1` 作为参数，此时路由为 [`/4ksj/4k-uhd-s7-display-3-dytypes-1-1`](https://rsshub.app/4ksj/4k-uhd-s7-display-3-dytypes-1-1)。\n:::",
  "example": "/4ksj/4k-uhd-1",
  "location": "forum.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/4ksj/forum.tsx')",
  "name": "分类",
  "parameters": {
    "id": "分类 id，默认为最新4K电影"
  },
  "path": "/:id?",
  "url": "4ksj.com"
}
```
