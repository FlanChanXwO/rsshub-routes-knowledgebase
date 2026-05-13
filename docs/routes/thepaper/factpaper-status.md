# 澎湃新闻 - 明查

## Coverage
`index-only`

## Route
- Namespace: `thepaper`
- Namespace Name: `澎湃新闻`
- Route Path: `/factpaper/:status?`
- Route Name: `明查`
- Example: `/thepaper/factpaper`
- URL: `factpaper.cn/`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `factpaper.tsx`
- Source Module: `() => import('@/routes/thepaper/factpaper.tsx')`

## Description
_None_

## Parameters
- `status`: 状态 id，可选 `1` 即 有定论 或 `0` 即 核查中，默认为 `1`


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
  - `factpaper.cn/`
- `target`: `/factpaper/:status`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/thepaper/factpaper",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "factpaper.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/thepaper/factpaper.tsx')",
  "name": "明查",
  "parameters": {
    "status": "状态 id，可选 `1` 即 有定论 或 `0` 即 核查中，默认为 `1`"
  },
  "path": "/factpaper/:status?",
  "radar": [
    {
      "source": [
        "factpaper.cn/"
      ],
      "target": "/factpaper/:status"
    }
  ],
  "url": "factpaper.cn/"
}
```
