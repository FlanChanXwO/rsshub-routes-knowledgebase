# Hong Kong Department of Health 香港卫生署 - Press Release

## Coverage
`index-only`

## Route
- Namespace: `hongkong`
- Namespace Name: `Hong Kong Department of Health 香港卫生署`
- Route Path: `/dh/:language?`
- Route Name: `Press Release`
- Example: `/hongkong/dh`
- URL: `dh.gov.hk/`
- Language: `zh-HK`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `dh.ts`
- Source Module: `() => import('@/routes/hongkong/dh.ts')`

## Description
Language

| English | 中文简体 | 中文繁體 |
| ------- | -------- | -------- |
| english | chs      | tc_chi  |

## Parameters
- `language`: Language, see below, tc_chi by default


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
  - `dh.gov.hk/`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "Language\n\n| English | 中文简体 | 中文繁體 |\n| ------- | -------- | -------- |\n| english | chs      | tc_chi  |",
  "example": "/hongkong/dh",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "dh.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/hongkong/dh.ts')",
  "name": "Press Release",
  "parameters": {
    "language": "Language, see below, tc_chi by default"
  },
  "path": "/dh/:language?",
  "radar": [
    {
      "source": [
        "dh.gov.hk/"
      ]
    }
  ],
  "url": "dh.gov.hk/"
}
```
