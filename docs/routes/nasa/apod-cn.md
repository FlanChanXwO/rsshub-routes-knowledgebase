# NASA - NASA 中文

## Coverage
`index-only`

## Route
- Namespace: `nasa`
- Namespace Name: `NASA`
- Route Path: `/apod-cn`
- Route Name: `NASA 中文`
- Example: `/nasa/apod-cn`
- URL: `apod.nasa.govundefined`
- Language: `en`
- Categories: `picture`
- Maintainers: `nczitzk, williamgateszhao`
- Source Location: `apod-cn.ts`
- Source Module: `() => import('@/routes/nasa/apod-cn.ts')`

## Description
::: tip
  [NASA 中文](https://www.nasachina.cn/) 提供了每日天文图的中英双语图文说明，但在更新上偶尔略有一两天的延迟。
:::

## Parameters
_None_


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
  - `apod.nasa.govundefined`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "description": "::: tip\n  [NASA 中文](https://www.nasachina.cn/) 提供了每日天文图的中英双语图文说明，但在更新上偶尔略有一两天的延迟。\n:::",
  "example": "/nasa/apod-cn",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "apod-cn.ts",
  "maintainers": [
    "nczitzk",
    "williamgateszhao"
  ],
  "module": "() => import('@/routes/nasa/apod-cn.ts')",
  "name": "NASA 中文",
  "parameters": {},
  "path": "/apod-cn",
  "radar": [
    {
      "source": [
        "apod.nasa.govundefined"
      ]
    }
  ],
  "url": "apod.nasa.govundefined"
}
```
