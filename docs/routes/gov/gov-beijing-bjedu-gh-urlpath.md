# Hangzhou People's Government - 通用

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `Hangzhou People's Government`
- Route Path: `/gov/beijing/bjedu/gh/:urlPath?`
- Route Name: `通用`
- Example: `/gov/beijing/bjedu/gh`
- URL: `hangzhou.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `TonyRL`
- Source Location: `beijing/bjedu/gh.ts`
- Source Module: `_None_`

## Description
::: tip
路径处填写对应页面 URL 中 `https://gh.bjedu.cn/ghsite/` 和 `/index.html` 之间的字段。下面是一个例子。

若订阅 [通知公告](https://gh.bjedu.cn/ghsite/zxtzgg/index.html) 则将对应页面 URL `https://gh.bjedu.cn/ghsite/zxtzgg/index.html` 中 `https://gh.bjedu.cn/ghsite/` 和 `/index.html` 之间的字段 `zxtzgg` 作为路径填入。此时路由为 [`/gov/beijing/bjedu/gh/zxtzgg`](https://rsshub.app/gov/beijing/bjedu/gh/zxtzgg)
:::

## Parameters
- `urlPath`: 路径，默认为 `zxtzgg`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `gh.bjedu.gov.cn/ghsite/:urlPath/index.html`
  - `gh.bjedu.gov.cn/ghsite/:urlPath`
- `target`: `/beijing/bjedu/gh/:urlPath`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n路径处填写对应页面 URL 中 `https://gh.bjedu.cn/ghsite/` 和 `/index.html` 之间的字段。下面是一个例子。\n\n若订阅 [通知公告](https://gh.bjedu.cn/ghsite/zxtzgg/index.html) 则将对应页面 URL `https://gh.bjedu.cn/ghsite/zxtzgg/index.html` 中 `https://gh.bjedu.cn/ghsite/` 和 `/index.html` 之间的字段 `zxtzgg` 作为路径填入。此时路由为 [`/gov/beijing/bjedu/gh/zxtzgg`](https://rsshub.app/gov/beijing/bjedu/gh/zxtzgg)\n:::",
  "example": "/gov/beijing/bjedu/gh",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "beijing/bjedu/gh.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "通用",
  "parameters": {
    "urlPath": "路径，默认为 `zxtzgg`"
  },
  "path": "/beijing/bjedu/gh/:urlPath?",
  "radar": [
    {
      "source": [
        "gh.bjedu.gov.cn/ghsite/:urlPath/index.html",
        "gh.bjedu.gov.cn/ghsite/:urlPath"
      ],
      "target": "/beijing/bjedu/gh/:urlPath"
    }
  ],
  "topFeeds": []
}
```
