# 牛客网 - 面经

## Coverage
`index-only`

## Route
- Namespace: `nowcoder`
- Namespace Name: `牛客网`
- Route Path: `/experience/:tagId`
- Route Name: `面经`
- Example: `/nowcoder/experience/639?order=3&companyId=665&phaseId=0`
- URL: `nowcoder.com/`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `huyyi`
- Source Location: `experience.ts`
- Source Module: `() => import('@/routes/nowcoder/experience.ts')`

## Description
可选参数：

  -   companyId：公司 id，[🔗查询链接](https://www.nowcoder.com/discuss/tag/exp), 复制打开
  -   order：3 - 最新；1 - 最热
  -   phaseId：0 - 所有；1 - 校招；2 - 实习；3 - 社招

## Parameters
- `tagId`: 职位id [🔗查询链接](https://www.nowcoder.com/profile/all-jobs)复制打开


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
  - `nowcoder.com/`
- `target`: `/experience`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "可选参数：\n\n  -   companyId：公司 id，[🔗查询链接](https://www.nowcoder.com/discuss/tag/exp), 复制打开\n  -   order：3 - 最新；1 - 最热\n  -   phaseId：0 - 所有；1 - 校招；2 - 实习；3 - 社招",
  "example": "/nowcoder/experience/639?order=3&companyId=665&phaseId=0",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "experience.ts",
  "maintainers": [
    "huyyi"
  ],
  "module": "() => import('@/routes/nowcoder/experience.ts')",
  "name": "面经",
  "parameters": {
    "tagId": "职位id [🔗查询链接](https://www.nowcoder.com/profile/all-jobs)复制打开"
  },
  "path": "/experience/:tagId",
  "radar": [
    {
      "source": [
        "nowcoder.com/"
      ],
      "target": "/experience"
    }
  ],
  "url": "nowcoder.com/"
}
```
