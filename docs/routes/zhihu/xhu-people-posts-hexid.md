# 知乎 - xhu - 用户文章

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/xhu/people/posts/:hexId`
- Route Name: `xhu - 用户文章`
- Example: `/zhihu/xhu/people/posts/246e6cf44e94cefbf4b959cb5042bc91`
- URL: `www.zhihu.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `JimenezLi`
- Source Location: `xhu/posts.ts`
- Source Module: `() => import('@/routes/zhihu/xhu/posts.ts')`

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
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/xhu/people/posts/246e6cf44e94cefbf4b959cb5042bc91",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "xhu/posts.ts",
  "maintainers": [
    "JimenezLi"
  ],
  "module": "() => import('@/routes/zhihu/xhu/posts.ts')",
  "name": "xhu - 用户文章",
  "parameters": {
    "hexId": "用户的 16 进制 id，获取方式同 [xhu - 用户动态](#zhi-hu-xhu-yong-hu-dong-tai)"
  },
  "path": "/xhu/people/posts/:hexId"
}
```
