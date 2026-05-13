# 云谦的博客 - 文章

## Coverage
`index-only`

## Route
- Namespace: `sorrycc`
- Namespace Name: `云谦的博客`
- Route Path: `/`
- Route Name: `文章`
- Example: `/sorrycc`
- URL: `sorrycc.com`
- Language: `zh-CN`
- Categories: `blog`
- Maintainers: `KarasuShin`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/sorrycc/index.ts')`

## Description
云谦的博客，部分内容存在权限校验，访问完整内容请部署RSSHub私有实例并配置授权信息

## Parameters
_None_


## Features
- `supportRadar`: true
- `requireConfig`: [{"description": "登录用户的Cookie,获取方式：\n1. 登录sorrycc.com\n2. 打开浏览器开发者工具，切换到 Application 面板\n3. 点击侧边栏中的Storage -> Cookies -> https://sorrycc.com\n4. 复制 Cookie 中的 wordpress_logged_in_f05fca638390aed897fbe3c2fff03000 值", "name": "SORRYCC_COOKIES", "optional": true}]

## Radar
### Rule 1
- `source`:
  - `sorrycc.com`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "description": "云谦的博客，部分内容存在权限校验，访问完整内容请部署RSSHub私有实例并配置授权信息",
  "example": "/sorrycc",
  "features": {
    "requireConfig": [
      {
        "description": "登录用户的Cookie,获取方式：\n1. 登录sorrycc.com\n2. 打开浏览器开发者工具，切换到 Application 面板\n3. 点击侧边栏中的Storage -> Cookies -> https://sorrycc.com\n4. 复制 Cookie 中的 wordpress_logged_in_f05fca638390aed897fbe3c2fff03000 值",
        "name": "SORRYCC_COOKIES",
        "optional": true
      }
    ],
    "supportRadar": true
  },
  "location": "index.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "module": "() => import('@/routes/sorrycc/index.ts')",
  "name": "文章",
  "path": "/",
  "radar": [
    {
      "source": [
        "sorrycc.com"
      ]
    }
  ],
  "view": 0
}
```
