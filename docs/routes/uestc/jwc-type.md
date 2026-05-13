# 电子科技大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `uestc`
- Namespace Name: `电子科技大学`
- Route Path: `/jwc/:type?`
- Route Name: `教务处`
- Example: `/uestc/jwc/student`
- URL: `www.jwc.uestc.edu.cn/`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `achjqz, mobyw`
- Source Location: `jwc.ts`
- Source Module: `() => import('@/routes/uestc/jwc.ts')`

## Description
| 重要公告  | 学生事务公告 | 教师事务公告 | 教学新闻 | 办公室 |
| --------- | ------------ | ------------ | -------- | ------ |
| important | student      | teacher      | teaching | office |

## Parameters
- `type`: 默认为 `important`


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
  - `www.jwc.uestc.edu.cn/`
- `target`: `/jwc`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 重要公告  | 学生事务公告 | 教师事务公告 | 教学新闻 | 办公室 |\n| --------- | ------------ | ------------ | -------- | ------ |\n| important | student      | teacher      | teaching | office |",
  "example": "/uestc/jwc/student",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jwc.ts",
  "maintainers": [
    "achjqz",
    "mobyw"
  ],
  "module": "() => import('@/routes/uestc/jwc.ts')",
  "name": "教务处",
  "parameters": {
    "type": "默认为 `important`"
  },
  "path": "/jwc/:type?",
  "radar": [
    {
      "source": [
        "www.jwc.uestc.edu.cn/"
      ],
      "target": "/jwc"
    }
  ],
  "url": "www.jwc.uestc.edu.cn/"
}
```
