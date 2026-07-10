# 中国科学技术大学 - 就业信息网

## Coverage
`index-only`

## Route
- Namespace: `ustc`
- Namespace Name: `中国科学技术大学`
- Route Path: `/ustc/job/:category?`
- Route Name: `就业信息网`
- Example: `/ustc/job`
- URL: `job.ustc.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `nczitzk`
- Source Location: `job.ts`
- Source Module: `_None_`

## Description
| 专场招聘会  | 校园双选会   | 空中宣讲  | 招聘公告 |
| ----------- | ------------ | --------- | -------- |
| RecruitList | Doublechoice | Broadcast | joblist2 |

## Parameters
- `category`: 分类，见下表，默认为招聘公告


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
  - `job.ustc.edu.cn/`
- `target`: `/job`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 专场招聘会  | 校园双选会   | 空中宣讲  | 招聘公告 |\n| ----------- | ------------ | --------- | -------- |\n| RecruitList | Doublechoice | Broadcast | joblist2 |",
  "example": "/ustc/job",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "job.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "就业信息网",
  "parameters": {
    "category": "分类，见下表，默认为招聘公告"
  },
  "path": "/job/:category?",
  "radar": [
    {
      "source": [
        "job.ustc.edu.cn/"
      ],
      "target": "/job"
    }
  ],
  "topFeeds": [],
  "url": "job.ustc.edu.cn/"
}
```
