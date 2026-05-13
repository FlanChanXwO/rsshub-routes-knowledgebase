# MM 范 - 分类

## Coverage
`index-only`

## Route
- Namespace: `95mm`
- Namespace Name: `MM 范`
- Route Path: `/tab/:tab?`
- Route Name: `分类`
- Example: `/95mm/tab/热门`
- URL: `95mm.org/`
- Language: `zh-CN`
- Categories: `picture`
- Maintainers: `nczitzk`
- Source Location: `tab.ts`
- Source Module: `() => import('@/routes/95mm/tab.ts')`

## Description
| 最新 | 热门 | 校花 | 森系 | 清纯 | 童颜 | 嫩模 | 少女 |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |

## Parameters
- `tab`: 分类，见下表，默认为最新


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `95mm.org/`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "description": "| 最新 | 热门 | 校花 | 森系 | 清纯 | 童颜 | 嫩模 | 少女 |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |",
  "example": "/95mm/tab/热门",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "tab.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/95mm/tab.ts')",
  "name": "分类",
  "parameters": {
    "tab": "分类，见下表，默认为最新"
  },
  "path": "/tab/:tab?",
  "radar": [
    {
      "source": [
        "95mm.org/"
      ]
    }
  ],
  "url": "95mm.org/"
}
```
