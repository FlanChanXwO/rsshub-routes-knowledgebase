# 山东省教育招生考试院 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `sdzk`
- Namespace Name: `山东省教育招生考试院`
- Route Path: `/:bcid?/:cid?`
- Route Name: `新闻`
- Example: `/sdzk`
- URL: `sdzk.cn`
- Language: `zh-CN`
- Categories: `study`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/sdzk/index.ts')`

## Description
::: tip
  若订阅 [信息与政策](https://www.sdzk.cn/NewsList.aspx?BCID=1)，网址为 `https://www.sdzk.cn/NewsList.aspx?BCID=1`。截取 `BCID=1` 作为参数，此时路由为 [`/sdzk/1`](https://rsshub.app/sdzk/1)。

  若订阅 [通知公告](https://www.sdzk.cn/NewsList.aspx?BCID=1&CID=16)，网址为 `https://www.sdzk.cn/NewsList.aspx?BCID=1&CID=16`。截取 `BCID=1` 与 `CID=16` 作为参数，此时路由为 [`/sdzk/1/16`](https://rsshub.app/sdzk/1/16)。
:::

## Parameters
- `bcid`: 板块 id，可在对应板块页 URL 中找到，默认为 `1`，即信息与政策
- `cid`: 栏目 id，可在对应板块页 URL 中找到，默认为 `16`，即通知公告


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
    "study"
  ],
  "description": "::: tip\n  若订阅 [信息与政策](https://www.sdzk.cn/NewsList.aspx?BCID=1)，网址为 `https://www.sdzk.cn/NewsList.aspx?BCID=1`。截取 `BCID=1` 作为参数，此时路由为 [`/sdzk/1`](https://rsshub.app/sdzk/1)。\n\n  若订阅 [通知公告](https://www.sdzk.cn/NewsList.aspx?BCID=1&CID=16)，网址为 `https://www.sdzk.cn/NewsList.aspx?BCID=1&CID=16`。截取 `BCID=1` 与 `CID=16` 作为参数，此时路由为 [`/sdzk/1/16`](https://rsshub.app/sdzk/1/16)。\n:::",
  "example": "/sdzk",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/sdzk/index.ts')",
  "name": "新闻",
  "parameters": {
    "bcid": "板块 id，可在对应板块页 URL 中找到，默认为 `1`，即信息与政策",
    "cid": "栏目 id，可在对应板块页 URL 中找到，默认为 `16`，即通知公告"
  },
  "path": "/:bcid?/:cid?"
}
```
