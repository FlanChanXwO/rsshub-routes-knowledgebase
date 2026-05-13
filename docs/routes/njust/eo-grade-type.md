# 南京理工大学 - 电光学院年级网站

## Coverage
`index-only`

## Route
- Namespace: `njust`
- Namespace Name: `南京理工大学`
- Route Path: `/eo/:grade?/:type?`
- Route Name: `电光学院年级网站`
- Example: `/njust/eo/17/tz`
- URL: `jwc.njust.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `jasongzy`
- Source Location: `eo.ts`
- Source Module: `() => import('@/routes/njust/eo.ts')`

## Description
`grade` 列表：

| 本科 2016 级 | 本科 2017 级 | 本科 2018 级 | 本科 2019 级 |
| ------------ | ------------ | ------------ | ------------ |
| 16           | 17           | 18           | 19           |

  `type` 列表：

| 年级通知（通知公告） | 每日动态（主任寄语） |
| -------------------- | -------------------- |
| tz                   | dt                   |

## Parameters
- `grade`: 年级，见下表，默认为本科 2017 级，未列出的年级所对应的参数可以从级网二级页面的 URL Path 中找到，例如：本科 2020 级为 `_t1316`
- `type`: 类别，见下表，默认为年级通知（通知公告），未列出的类别所对应的参数可以从级网二级页面的 URL Path 中找到，例如：电光 20 的通知公告为 `tzgg_12969`


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
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
  "description": "`grade` 列表：\n\n| 本科 2016 级 | 本科 2017 级 | 本科 2018 级 | 本科 2019 级 |\n| ------------ | ------------ | ------------ | ------------ |\n| 16           | 17           | 18           | 19           |\n\n  `type` 列表：\n\n| 年级通知（通知公告） | 每日动态（主任寄语） |\n| -------------------- | -------------------- |\n| tz                   | dt                   |",
  "example": "/njust/eo/17/tz",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "eo.ts",
  "maintainers": [
    "jasongzy"
  ],
  "module": "() => import('@/routes/njust/eo.ts')",
  "name": "电光学院年级网站",
  "parameters": {
    "grade": "年级，见下表，默认为本科 2017 级，未列出的年级所对应的参数可以从级网二级页面的 URL Path 中找到，例如：本科 2020 级为 `_t1316`",
    "type": "类别，见下表，默认为年级通知（通知公告），未列出的类别所对应的参数可以从级网二级页面的 URL Path 中找到，例如：电光 20 的通知公告为 `tzgg_12969`"
  },
  "path": "/eo/:grade?/:type?"
}
```
