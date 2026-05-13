# 西南交通大学 - 扬华素质网

## Coverage
`index-only`

## Route
- Namespace: `swjtu`
- Namespace Name: `西南交通大学`
- Route Path: `/xg/:code?`
- Route Name: `扬华素质网`
- Example: `/swjtu/xg/tzgg`
- URL: `xg.swjtu.edu.cn/web/Home/PushNewsList`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `mobyw`
- Source Location: `xg.ts`
- Source Module: `() => import('@/routes/swjtu/xg.ts')`

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
  "location": "xg.ts",
  "maintainers": [
    "mobyw"
  ],
  "module": "() => import('@/routes/swjtu/xg.ts')",
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
  "url": "xg.swjtu.edu.cn/web/Home/PushNewsList"
}
```
