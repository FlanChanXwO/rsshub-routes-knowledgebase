# 观察者网 - 观学院

## Coverage
`index-only`

## Route
- Namespace: `guancha`
- Namespace Name: `观察者网`
- Route Path: `/member/:category?`
- Route Name: `观学院`
- Example: `/guancha/member/recommend`
- URL: `guancha.cn/`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `member.ts`
- Source Module: `() => import('@/routes/guancha/member.ts')`

## Description
| 精选      | 观书堂 | 在线课  | 观学院   |
| --------- | ------ | ------- | -------- |
| recommend | books  | courses | huodongs |

## Parameters
- `category`: 分类，见下表


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
  - `guancha.cn/`
- `target`: `/:category?`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 精选      | 观书堂 | 在线课  | 观学院   |\n| --------- | ------ | ------- | -------- |\n| recommend | books  | courses | huodongs |",
  "example": "/guancha/member/recommend",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "member.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/guancha/member.ts')",
  "name": "观学院",
  "parameters": {
    "category": "分类，见下表"
  },
  "path": "/member/:category?",
  "radar": [
    {
      "source": [
        "guancha.cn/"
      ],
      "target": "/:category?"
    }
  ],
  "url": "guancha.cn/"
}
```
