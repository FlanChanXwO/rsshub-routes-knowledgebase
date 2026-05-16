# Hangzhou People's Government - 关税政策文件

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `Hangzhou People's Government`
- Route Path: `/gov/mof/gss/:category?`
- Route Name: `关税政策文件`
- Example: `/gov/mof/gss`
- URL: `hangzhou.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `la3rence`
- Source Location: `mof/gss.ts`
- Source Module: `_None_`

## Description
#### 关税文件发布

| 政策发布    | 政策解读     |
| ----------- | ------------ |
| zhengcefabu | zhengcejiedu |

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
  "description": "#### 关税文件发布\n\n| 政策发布    | 政策解读     |\n| ----------- | ------------ |\n| zhengcefabu | zhengcejiedu |",
  "example": "/gov/mof/gss",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 71,
  "location": "mof/gss.ts",
  "maintainers": [
    "la3rence"
  ],
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
  ],
  "topFeeds": [
    {
      "description": "政策文件 - 中华人民共和国财政部 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "133069318957962240",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gss.mof.gov.cn/gzdt/zhengcefabu/",
      "title": "政策文件",
      "type": "feed",
      "url": "rsshub://gov/mof/gss"
    },
    {
      "description": "政策解读 - 中华人民共和国财政部 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "145117484898967552",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gss.mof.gov.cn/gzdt/zhengcejiedu/",
      "title": "政策解读",
      "type": "feed",
      "url": "rsshub://gov/mof/gss/zhengcejiedu"
    }
  ]
}
```
