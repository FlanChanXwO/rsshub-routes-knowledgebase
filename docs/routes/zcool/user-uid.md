# 站酷 - 用户作品

## Coverage
`index-only`

## Route
- Namespace: `zcool`
- Namespace Name: `站酷`
- Route Path: `/user/:uid`
- Route Name: `用户作品`
- Example: `/zcool/user/baiyong`
- URL: `www.zcool.com.cn`
- Language: `zh-CN`
- Categories: `design`
- Maintainers: `junbaor`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/zcool/user.ts')`

## Description
例如:

    站酷的个人主页 `https://baiyong.zcool.com.cn` 对应 rss 路径 `/zcool/user/baiyong`

    站酷的个人主页 `https://www.zcool.com.cn/u/568339` 对应 rss 路径 `/zcool/user/568339`

## Parameters
- `uid`: 个性域名前缀或者用户ID


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
  - `www.zcool.com.cn/u/:id`
- `target`: `/user/:id`

## Raw JSON
```json
{
  "categories": [
    "design"
  ],
  "description": "  例如:\n\n    站酷的个人主页 `https://baiyong.zcool.com.cn` 对应 rss 路径 `/zcool/user/baiyong`\n\n    站酷的个人主页 `https://www.zcool.com.cn/u/568339` 对应 rss 路径 `/zcool/user/568339`",
  "example": "/zcool/user/baiyong",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user.ts",
  "maintainers": [
    "junbaor"
  ],
  "module": "() => import('@/routes/zcool/user.ts')",
  "name": "用户作品",
  "parameters": {
    "uid": "个性域名前缀或者用户ID"
  },
  "path": "/user/:uid",
  "radar": [
    {
      "source": [
        "www.zcool.com.cn/u/:id"
      ],
      "target": "/user/:id"
    }
  ],
  "view": 2
}
```
