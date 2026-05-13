# 上海交通大学 - 同去网最新活动

## Coverage
`index-only`

## Route
- Namespace: `sjtu`
- Namespace Name: `上海交通大学`
- Route Path: `/tongqu/:type?`
- Route Name: `同去网最新活动`
- Example: `/sjtu/tongqu/lecture`
- URL: `www.sjtu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `SeanChao`
- Source Location: `tongqu/activity.tsx`
- Source Module: `() => import('@/routes/sjtu/tongqu/activity.tsx')`

## Description
| 全部 | 最新   | 招新        | 讲座    | 户外      | 招聘 | 游学       | 比赛         | 公益           | 主题党日 | 学生事务       | 广告 | 其他   |
| ---- | ------ | ----------- | ------- | --------- | ---- | ---------- | ------------ | -------------- | -------- | -------------- | ---- | ------ |
| all  | newest | recruitment | lecture | outdoords | jobs | studyTours | competitions | publicWarefare | partyDay | studentAffairs | ads  | others |

## Parameters
- `type`: 类型，默认为全部


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
  "description": "| 全部 | 最新   | 招新        | 讲座    | 户外      | 招聘 | 游学       | 比赛         | 公益           | 主题党日 | 学生事务       | 广告 | 其他   |\n| ---- | ------ | ----------- | ------- | --------- | ---- | ---------- | ------------ | -------------- | -------- | -------------- | ---- | ------ |\n| all  | newest | recruitment | lecture | outdoords | jobs | studyTours | competitions | publicWarefare | partyDay | studentAffairs | ads  | others |",
  "example": "/sjtu/tongqu/lecture",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "tongqu/activity.tsx",
  "maintainers": [
    "SeanChao"
  ],
  "module": "() => import('@/routes/sjtu/tongqu/activity.tsx')",
  "name": "同去网最新活动",
  "parameters": {
    "type": "类型，默认为全部"
  },
  "path": "/tongqu/:type?"
}
```
