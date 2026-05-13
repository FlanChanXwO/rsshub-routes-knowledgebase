# Quicker - 讨论区

## Coverage
`index-only`

## Route
- Namespace: `quicker`
- Namespace Name: `Quicker`
- Route Path: `/quicker/qa/:category?/:state?`
- Route Name: `讨论区`
- Example: `/quicker/qa`
- URL: `getquicker.net`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `Cesaryuan, nczitzk`
- Source Location: `qa.ts`
- Source Module: `_None_`

## Description
分类

| 使用问题 | 动作开发 | BUG 反馈 | 功能建议 |
| -------- | -------- | -------- | -------- |
| 1        | 9        | 3        | 4        |

| 动作需求 | 经验创意 | 动作推荐 | 信息发布 |
| -------- | -------- | -------- | -------- |
| 6        | 2        | 7        | 5        |

| 随便聊聊 | 异常报告 | 全部 |
| -------- | -------- | ---- |
| 8        | 10       | all  |

状态

| 全部 | 精华   | 已归档  |
| ---- | ------ | ------- |
|      | digest | achived |

## Parameters
- `category`: 分类，见下表，默认为全部
- `state`: 状态，见下表，默认为全部


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
    "programming"
  ],
  "description": "分类\n\n| 使用问题 | 动作开发 | BUG 反馈 | 功能建议 |\n| -------- | -------- | -------- | -------- |\n| 1        | 9        | 3        | 4        |\n\n| 动作需求 | 经验创意 | 动作推荐 | 信息发布 |\n| -------- | -------- | -------- | -------- |\n| 6        | 2        | 7        | 5        |\n\n| 随便聊聊 | 异常报告 | 全部 |\n| -------- | -------- | ---- |\n| 8        | 10       | all  |\n\n状态\n\n| 全部 | 精华   | 已归档  |\n| ---- | ------ | ------- |\n|      | digest | achived |",
  "example": "/quicker/qa",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "qa.ts",
  "maintainers": [
    "Cesaryuan",
    "nczitzk"
  ],
  "name": "讨论区",
  "parameters": {
    "category": "分类，见下表，默认为全部",
    "state": "状态，见下表，默认为全部"
  },
  "path": "/qa/:category?/:state?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "讨论区 - Quicker - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "71432897106233344",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://getquicker.net/QA",
      "title": "讨论区 - Quicker",
      "type": "feed",
      "url": "rsshub://quicker/qa"
    }
  ]
}
```
