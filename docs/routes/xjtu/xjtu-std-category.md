# 西安交通大学 - 科技在线

## Coverage
`index-only`

## Route
- Namespace: `xjtu`
- Namespace Name: `西安交通大学`
- Route Path: `/xjtu/std/:category?`
- Route Name: `科技在线`
- Example: `/xjtu/std/zytz`
- URL: `2yuan.xjtu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `nczitzk`
- Source Location: `std.tsx`
- Source Module: `_None_`

## Description
| 通知公告 | 重要通知 | 项目申报 | 成果申报 | 信息快讯 |
| -------- | -------- | -------- | -------- | -------- |
|          | zytz     | xmsb     | cgsb     | xxkx     |

## Parameters
- `category`: 分类，见下表，默认为通知公告


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
    "university"
  ],
  "description": "| 通知公告 | 重要通知 | 项目申报 | 成果申报 | 信息快讯 |\n| -------- | -------- | -------- | -------- | -------- |\n|          | zytz     | xmsb     | cgsb     | xxkx     |",
  "example": "/xjtu/std/zytz",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "std.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "科技在线",
  "parameters": {
    "category": "分类，见下表，默认为通知公告"
  },
  "path": "/std/:category?",
  "topFeeds": []
}
```
