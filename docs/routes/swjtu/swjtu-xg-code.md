# 西南交通大学 - 扬华素质网

## Coverage
`index-only`

## Route
- Namespace: `swjtu`
- Namespace Name: `西南交通大学`
- Route Path: `/swjtu/xg/:code?`
- Route Name: `扬华素质网`
- Example: `/swjtu/xg/tzgg`
- URL: `xg.swjtu.edu.cn/web/Home/PushNewsList`
- Language: `_None_`
- Categories: `university`
- Maintainers: `mobyw`
- Source Location: `xg.ts`
- Source Module: `_None_`

## Description
栏目列表：

| 通知公告 | 扬华新闻 | 多彩学院 | 学工之家 |
| -------- | -------- | -------- | -------- |
| tzgg     | yhxw     | dcxy     | xgzj     |

## Parameters
- `code`: 栏目(默认为tzgg)


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `xg.swjtu.edu.cn/web/Home/PushNewsList`
  - `xg.swjtu.edu.cn/web/Home/NewsList`
  - `xg.swjtu.edu.cn/web/Home/ColourfulCollegeNewsList`
  - `xg.swjtu.edu.cn/web/Publicity/List`
  - `xg.swjtu.edu.cn/`
- `target`: `/xg`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "栏目列表：\n\n| 通知公告 | 扬华新闻 | 多彩学院 | 学工之家 |\n| -------- | -------- | -------- | -------- |\n| tzgg     | yhxw     | dcxy     | xgzj     |",
  "example": "/swjtu/xg/tzgg",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "xg.ts",
  "maintainers": [
    "mobyw"
  ],
  "name": "扬华素质网",
  "parameters": {
    "code": "栏目(默认为tzgg)"
  },
  "path": "/xg/:code?",
  "radar": [
    {
      "source": [
        "xg.swjtu.edu.cn/web/Home/PushNewsList",
        "xg.swjtu.edu.cn/web/Home/NewsList",
        "xg.swjtu.edu.cn/web/Home/ColourfulCollegeNewsList",
        "xg.swjtu.edu.cn/web/Publicity/List",
        "xg.swjtu.edu.cn/"
      ],
      "target": "/xg"
    }
  ],
  "topFeeds": [
    {
      "description": "西南交大-扬华素质网 - Powered by RSSHub",
      "errorAt": "2026-05-08T19:18:51.234Z",
      "errorMessage": "[GET] \"http://xg.swjtu.edu.cn/web/Home/PushNewsList?Lmk7LJw34Jmu=010j.shtml\": <no response> fetch failed\n",
      "id": "72512219481102338",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://xg.swjtu.edu.cn/web/Home/PushNewsList?Lmk7LJw34Jmu=010j.shtml",
      "title": "西南交大-扬华素质网",
      "type": "feed",
      "url": "rsshub://swjtu/xg/tzgg"
    },
    {
      "description": "西南交大-扬华素质网 - Powered by RSSHub",
      "errorAt": "2025-10-29T11:20:45.197Z",
      "errorMessage": "[GET] \"http://xg.swjtu.edu.cn/web/Home/PushNewsList?Lmk7LJw34Jmu=010j.shtml\": <no response> fetch failed\n",
      "id": "206259218544363520",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://xg.swjtu.edu.cn/web/Home/PushNewsList?Lmk7LJw34Jmu=010j.shtml",
      "title": "西南交大-扬华素质网",
      "type": "feed",
      "url": "rsshub://swjtu/xg"
    }
  ],
  "url": "xg.swjtu.edu.cn/web/Home/PushNewsList"
}
```
