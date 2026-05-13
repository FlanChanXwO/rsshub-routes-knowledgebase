# 知乎 - 用户文章

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/posts/:usertype/:id`
- Route Name: `用户文章`
- Example: `/zhihu/posts/people/frederchen`
- URL: `www.zhihu.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `whtsky, Colin-XKL`
- Source Location: `posts.ts`
- Source Module: `() => import('@/routes/zhihu/posts.ts')`

## Description
| 普通用户 | 机构用户 |
| -------- | -------- |
| people   | org      |

## Parameters
- `usertype`: 作者 id，可在用户主页 URL 中找到
- `id`: 用户类型usertype，参考用户主页的URL。目前有两种，见下表


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
  - `www.zhihu.com/:usertype/:id/posts`
  - `www.zhihu.com/:usertype/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "| 普通用户 | 机构用户 |\n| -------- | -------- |\n| people   | org      |",
  "example": "/zhihu/posts/people/frederchen",
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
  "location": "posts.ts",
  "maintainers": [
    "whtsky",
    "Colin-XKL"
  ],
  "module": "() => import('@/routes/zhihu/posts.ts')",
  "name": "用户文章",
  "parameters": {
    "id": "用户类型usertype，参考用户主页的URL。目前有两种，见下表",
    "usertype": "作者 id，可在用户主页 URL 中找到"
  },
  "path": "/posts/:usertype/:id",
  "radar": [
    {
      "source": [
        "www.zhihu.com/:usertype/:id/posts",
        "www.zhihu.com/:usertype/:id"
      ]
    }
  ]
}
```
