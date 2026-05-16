# 西安交通大学 - 研究生招生信息网

## Coverage
`index-only`

## Route
- Namespace: `xjtu`
- Namespace Name: `西安交通大学`
- Route Path: `/xjtu/yz/:category?`
- Route Name: `研究生招生信息网`
- Example: `/xjtu/yz/zsdt`
- URL: `2yuan.xjtu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `YoghurtGuy`
- Source Location: `yz.ts`
- Source Module: `_None_`

## Description
栏目类型

| 招生动态 | 通知公告 | 政策法规 | 招生统计 | 历年复试线 | 博士招生 | 硕士招生 | 推免生 | 其他招生 |
| -------- | -------- | -------- | -------- | ---------- | -------- | -------- | ------ | -------- |
| zsdt     | tzgg     | zcfg     | zstj     | lnfsx      | bszs     | sszs     | tms    | qtzs     |

## Parameters
- `category`: 栏目类型，默认请求`zsdt`，详见下方表格


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
  - `yz.xjtu.edu.cn/index/:category.htm`
- `target`: `/yz/:category`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "栏目类型\n\n| 招生动态 | 通知公告 | 政策法规 | 招生统计 | 历年复试线 | 博士招生 | 硕士招生 | 推免生 | 其他招生 |\n| -------- | -------- | -------- | -------- | ---------- | -------- | -------- | ------ | -------- |\n| zsdt     | tzgg     | zcfg     | zstj     | lnfsx      | bszs     | sszs     | tms    | qtzs     |",
  "example": "/xjtu/yz/zsdt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "yz.ts",
  "maintainers": [
    "YoghurtGuy"
  ],
  "name": "研究生招生信息网",
  "parameters": {
    "category": "栏目类型，默认请求`zsdt`，详见下方表格"
  },
  "path": "/yz/:category?",
  "radar": [
    {
      "source": [
        "yz.xjtu.edu.cn/index/:category.htm"
      ],
      "target": "/yz/:category"
    }
  ],
  "topFeeds": [
    {
      "description": "西安交通大学研究生招生信息网 - Powered by RSSHub",
      "errorAt": "2025-12-05T06:53:13.544Z",
      "errorMessage": "[GET] \"https://yz.xjtu.edu.cn/index/zsdt.htm\": <no response> fetch failed\n",
      "id": "134832567118453760",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://yz.xjtu.edu.cn/",
      "title": "西安交通大学研究生招生信息网",
      "type": "feed",
      "url": "rsshub://xjtu/yz/zsdt"
    }
  ]
}
```
