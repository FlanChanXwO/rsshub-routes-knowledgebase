# 知乎 - 用户回答

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/people/answers/:id`
- Route Name: `用户回答`
- Example: `/zhihu/people/answers/diygod`
- URL: `www.zhihu.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `DIYgod, prnake`
- Source Location: `answers.ts`
- Source Module: `() => import('@/routes/zhihu/answers.ts')`

## Description
_None_

## Parameters
- `id`: 作者 id，可在用户主页 URL 中找到


## Features
- `requireConfig`: [{"description": "", "name": "ZHIHU_COOKIES", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.zhihu.com/people/:id/answers`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/people/answers/diygod",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "",
        "name": "ZHIHU_COOKIES",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "answers.ts",
  "maintainers": [
    "DIYgod",
    "prnake"
  ],
  "module": "() => import('@/routes/zhihu/answers.ts')",
  "name": "用户回答",
  "parameters": {
    "id": "作者 id，可在用户主页 URL 中找到"
  },
  "path": "/people/answers/:id",
  "radar": [
    {
      "source": [
        "www.zhihu.com/people/:id/answers"
      ]
    }
  ]
}
```
