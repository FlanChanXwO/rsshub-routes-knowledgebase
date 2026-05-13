# Hacking8 - 信息流

## Coverage
`index-only`

## Route
- Namespace: `hacking8`
- Namespace Name: `Hacking8`
- Route Path: `/:category?`
- Route Name: `信息流`
- Example: `/hacking8`
- URL: `hacking8.com`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/hacking8/index.ts')`

## Description
| 推荐  | 最近更新 | 漏洞 / PoC 监控 | PDF |
| ----- | -------- | --------------- | --- |
| likes | index    | vul-poc         | pdf |

## Parameters
- `category`: 分类，见下表，默认为最近更新


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
  - `hacking8.com/index/:category`
  - `hacking8.com/`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "| 推荐  | 最近更新 | 漏洞 / PoC 监控 | PDF |\n| ----- | -------- | --------------- | --- |\n| likes | index    | vul-poc         | pdf |",
  "example": "/hacking8",
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
  "module": "() => import('@/routes/hacking8/index.ts')",
  "name": "信息流",
  "parameters": {
    "category": "分类，见下表，默认为最近更新"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "hacking8.com/index/:category",
        "hacking8.com/"
      ]
    }
  ]
}
```
