# 知乎 - xhu - 用户回答

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/xhu/people/answers/:hexId`
- Route Name: `xhu - 用户回答`
- Example: `/zhihu/xhu/people/answers/246e6cf44e94cefbf4b959cb5042bc91`
- URL: `www.zhihu.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `JimenezLi`
- Source Location: `xhu/answers.ts`
- Source Module: `() => import('@/routes/zhihu/xhu/answers.ts')`

## Description
_None_

## Parameters
- `hexId`: 用户的 16 进制 id，获取方式同 [xhu - 用户动态](#zhi-hu-xhu-yong-hu-dong-tai)


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
  - `www.zhihu.com/people/:id/answers`
- `target`: `/people/answers/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/xhu/people/answers/246e6cf44e94cefbf4b959cb5042bc91",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "xhu/answers.ts",
  "maintainers": [
    "JimenezLi"
  ],
  "module": "() => import('@/routes/zhihu/xhu/answers.ts')",
  "name": "xhu - 用户回答",
  "parameters": {
    "hexId": "用户的 16 进制 id，获取方式同 [xhu - 用户动态](#zhi-hu-xhu-yong-hu-dong-tai)"
  },
  "path": "/xhu/people/answers/:hexId",
  "radar": [
    {
      "source": [
        "www.zhihu.com/people/:id/answers"
      ],
      "target": "/people/answers/:id"
    }
  ]
}
```
