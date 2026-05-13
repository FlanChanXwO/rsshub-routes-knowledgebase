# 知识星球 - 用户足迹

## Coverage
`index-only`

## Route
- Namespace: `zsxq`
- Namespace Name: `知识星球`
- Route Path: `/user/:id`
- Route Name: `用户足迹`
- Example: `/zsxq/user/2414218251`
- URL: `zsxq.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `KarasuShin`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/zsxq/user.ts')`

## Description
_None_

## Parameters
- `id`: 用户id，从网页端url中获取


## Features
- `requireConfig`: [{"description": "知识星球访问令牌,获取方式：\n1. 登录知识星球网页版\n2. 打开浏览器开发者工具，切换到 Application 面板\n3. 点击侧边栏中的Storage -> Cookies -> https://wx.zsxq.com\n4. 复制 Cookie 中的 zsxq_access_token 值", "name": "ZSXQ_ACCESS_TOKEN"}]

## Radar
### Rule 1
- `source`:
  - `wx.zsxq.com/dweb2/index/footprint/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zsxq/user/2414218251",
  "features": {
    "requireConfig": [
      {
        "description": "知识星球访问令牌,获取方式：\n1. 登录知识星球网页版\n2. 打开浏览器开发者工具，切换到 Application 面板\n3. 点击侧边栏中的Storage -> Cookies -> https://wx.zsxq.com\n4. 复制 Cookie 中的 zsxq_access_token 值",
        "name": "ZSXQ_ACCESS_TOKEN"
      }
    ]
  },
  "location": "user.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "module": "() => import('@/routes/zsxq/user.ts')",
  "name": "用户足迹",
  "parameters": {
    "id": "用户id，从网页端url中获取"
  },
  "path": "/user/:id",
  "radar": [
    {
      "source": [
        "wx.zsxq.com/dweb2/index/footprint/:id"
      ]
    }
  ]
}
```
