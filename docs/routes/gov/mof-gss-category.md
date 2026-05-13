# 国家能源局 - 关税政策文件

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/mof/gss/:category?`
- Route Name: `关税政策文件`
- Example: `/gov/mof/gss`
- URL: `www.nea.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `la3rence`
- Source Location: `mof/gss.ts`
- Source Module: `() => import('@/routes/gov/mof/gss.ts')`

## Description
#### 关税文件发布

| 政策发布 | 政策解读 |
| ------------- | -------------- |
| zhengcefabu   | zhengcejiedu   |

## Parameters
- `category`: 列表标签，默认为政策发布


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
  - `gss.mof.gov.cn/gzdt/:category/`
- `target`: `/mof/gss/:category`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "#### 关税文件发布\n\n| 政策发布 | 政策解读 |\n| ------------- | -------------- |\n| zhengcefabu   | zhengcejiedu   |",
  "example": "/gov/mof/gss",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "mof/gss.ts",
  "maintainers": [
    "la3rence"
  ],
  "module": "() => import('@/routes/gov/mof/gss.ts')",
  "name": "关税政策文件",
  "parameters": {
    "category": "列表标签，默认为政策发布"
  },
  "path": "/mof/gss/:category?",
  "radar": [
    {
      "source": [
        "gss.mof.gov.cn/gzdt/:category/"
      ],
      "target": "/mof/gss/:category"
    }
  ]
}
```
