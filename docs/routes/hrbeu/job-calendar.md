# 哈尔滨工程大学 - 就业服务平台

## Coverage
`index-only`

## Route
- Namespace: `hrbeu`
- Namespace Name: `哈尔滨工程大学`
- Route Path: `/job/calendar`
- Route Name: `就业服务平台`
- Example: `/hrbeu/job/calendar`
- URL: `job.hrbeu.edu.cn/*`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `Derekmini`
- Source Location: `job/calendar.ts`
- Source Module: `() => import('@/routes/hrbeu/job/calendar.ts')`

## Description
| 通知公告 | 热点新闻 |
| :------: | :------: |
|   tzgg   |   rdxw   |

#### 大型招聘会 {#ha-er-bin-gong-cheng-da-xue-jiu-ye-fu-wu-ping-tai-da-xing-zhao-pin-hui}


#### 今日招聘会 {#ha-er-bin-gong-cheng-da-xue-jiu-ye-fu-wu-ping-tai-jin-ri-zhao-pin-hui}

## Parameters
_None_


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
  - `job.hrbeu.edu.cn/*`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告 | 热点新闻 |\n| :------: | :------: |\n|   tzgg   |   rdxw   |\n\n#### 大型招聘会 {#ha-er-bin-gong-cheng-da-xue-jiu-ye-fu-wu-ping-tai-da-xing-zhao-pin-hui}\n\n\n#### 今日招聘会 {#ha-er-bin-gong-cheng-da-xue-jiu-ye-fu-wu-ping-tai-jin-ri-zhao-pin-hui}",
  "example": "/hrbeu/job/calendar",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "job/calendar.ts",
  "maintainers": [
    "Derekmini"
  ],
  "module": "() => import('@/routes/hrbeu/job/calendar.ts')",
  "name": "就业服务平台",
  "parameters": {},
  "path": "/job/calendar",
  "radar": [
    {
      "source": [
        "job.hrbeu.edu.cn/*"
      ]
    }
  ],
  "url": "job.hrbeu.edu.cn/*"
}
```
