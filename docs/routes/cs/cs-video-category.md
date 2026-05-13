# 中证网 - 中证视频

## Coverage
`index-only`

## Route
- Namespace: `cs`
- Namespace Name: `中证网`
- Route Path: `/cs/video/:category?`
- Route Name: `中证视频`
- Example: `/cs/video/今日聚焦`
- URL: `cs.com.cn`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `video.ts`
- Source Module: `_None_`

## Description
| 今日聚焦 | 传闻求证 | 高端访谈 | 投教课堂 | 直播汇 |
| -------- | -------- | -------- | -------- | ------ |

## Parameters
- `category`: 分类，见下表，默认为今日聚焦


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| 今日聚焦 | 传闻求证 | 高端访谈 | 投教课堂 | 直播汇 |\n| -------- | -------- | -------- | -------- | ------ |",
  "example": "/cs/video/今日聚焦",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "video.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "中证视频",
  "parameters": {
    "category": "分类，见下表，默认为今日聚焦"
  },
  "path": "/video/:category?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "中证视频致力于为用户提供专业的财经视频直播、路演，用镜头关注宏观经济、金融市场、上市公司、投资理财等财经领域热点新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "154741594454642688",
      "image": "http://index.zhongshuheyi.com/pic/1595731734674.png",
      "ownerUserId": null,
      "siteUrl": "https://video.cs.com.cn/list.html?title=%E4%BB%8A%E6%97%A5%E8%81%9A%E7%84%A6&id=178",
      "title": "中证视频 - 中证网 | 今日聚焦",
      "type": "feed",
      "url": "rsshub://cs/video"
    }
  ]
}
```
