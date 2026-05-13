# Apple - Security releases

## Coverage
`index-only`

## Route
- Namespace: `apple`
- Namespace Name: `Apple`
- Route Path: `/security-releases/:language?`
- Route Name: `Security releases`
- Example: `/apple/security-releases`
- URL: `support.apple.com`
- Language: `en`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `security-releases.ts`
- Source Module: `() => import('@/routes/apple/security-releases.ts')`

## Description
::: tip
To subscribe to [Apple security releases](https://support.apple.com/en-us/100100), where the source URL is `https://support.apple.com/en-us/100100`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/apple/security-releases/en-us`](https://rsshub.app/apple/security-releases/en-us).
:::

## Parameters
- `language`: {"description": "Language, `en-us` by default"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `support.apple.com/:language/100100`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "::: tip\nTo subscribe to [Apple security releases](https://support.apple.com/en-us/100100), where the source URL is `https://support.apple.com/en-us/100100`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/apple/security-releases/en-us`](https://rsshub.app/apple/security-releases/en-us).\n:::\n",
  "example": "/apple/security-releases",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "security-releases.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/apple/security-releases.ts')",
  "name": "Security releases",
  "parameters": {
    "language": {
      "description": "Language, `en-us` by default"
    }
  },
  "path": "/security-releases/:language?",
  "radar": [
    {
      "source": [
        "support.apple.com/:language/100100"
      ]
    }
  ],
  "url": "support.apple.com",
  "view": 0,
  "zh": {
    "description": "::: tip\n若订阅 [Apple 安全性发布](https://support.apple.com/zh-cn/100100)，网址为 `https://support.apple.com/zh-cn/100100`，请截取 `https://support.apple.com/` 到末尾 `/100100` 的部分 `zh-cn` 作为 `language` 参数填入，此时目标路由为 [`/apple/security-releases/zh-cn`](https://rsshub.app/apple/security-releases/zh-cn)。\n:::\n",
    "example": "/apple/security-releases",
    "maintainers": [
      "nczitzk"
    ],
    "name": "安全性发布",
    "parameters": {
      "language": {
        "description": "语言，默认为 `en-us`，可在对应页 URL 中找到"
      }
    },
    "path": "/security-releases/:language?",
    "url": "support.apple.com"
  }
}
```
