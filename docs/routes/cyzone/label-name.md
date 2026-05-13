# 创业邦 - 标签

## Coverage
`index-only`

## Route
- Namespace: `cyzone`
- Namespace Name: `创业邦`
- Route Path: `/label/:name`
- Route Name: `标签`
- Example: `/cyzone/label/创业邦周报`
- URL: `cyzone.cn`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `label.ts`
- Source Module: `() => import('@/routes/cyzone/label.ts')`

## Description
_None_

## Parameters
- `name`: 标签名称，可在对应标签页 URL 中找到


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
  - `cyzone.cn/label/:name`
  - `cyzone.cn/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/cyzone/label/创业邦周报",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "label.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/cyzone/label.ts')",
  "name": "标签",
  "parameters": {
    "name": "标签名称，可在对应标签页 URL 中找到"
  },
  "path": "/label/:name",
  "radar": [
    {
      "source": [
        "cyzone.cn/label/:name",
        "cyzone.cn/"
      ]
    }
  ]
}
```
