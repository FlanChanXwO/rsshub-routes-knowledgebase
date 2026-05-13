# 百合会 - BBS - 板块

## Coverage
`index-only`

## Route
- Namespace: `yamibo`
- Namespace Name: `百合会`
- Route Path: `/bbs/forum/:fid/:type?`
- Route Name: `BBS - 板块`
- Example: `/yamibo/bbs/forum/5/404`
- URL: `yamibo.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `KarasuShin`
- Source Location: `bbs/forum.ts`
- Source Module: `() => import('@/routes/yamibo/bbs/forum.ts')`

## Description
::: warning
百合会BBS访问部分板块需要用户登录认证，请参考配置说明
:::

## Parameters
- `fid`: 板块 id，可从URL中提取。https://bbs.yamibo.com/forum-aa-b.html中的aa部分即为fid值
- `type`: 板块子分类，网页中选中板块分类后URL中的typeid值


## Features
- `antiCrawler`: true
- `requireConfig`: [{"description": "百合会BBS登录后的认证信息，获取方式：1. 登录百合会BBS网页版 2. 打开浏览器开发者工具，切换到 Application 面板\n3. 点击侧边栏中的Storage -> Cookies -> https://bbs.yamibo.com 4. 复制 Cookie 中的 EeqY_2132_saltkey 值", "name": "YAMIBO_SALT", "optional": true}, {"description": "百合会BBS登录后的认证信息，获取方式：1. 登录百合会BBS网页版 2. 打开浏览器开发者工具，切换到 Application 面板\n3. 点击侧边栏中的Storage -> Cookies -> https://bbs.yamibo.com 4. 复制 Cookie 中的 EeqY_2132_auth 值", "name": "YAMIBO_AUTH", "optional": true}]

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "::: warning\n百合会BBS访问部分板块需要用户登录认证，请参考配置说明\n:::",
  "example": "/yamibo/bbs/forum/5/404",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "百合会BBS登录后的认证信息，获取方式：1. 登录百合会BBS网页版 2. 打开浏览器开发者工具，切换到 Application 面板\n3. 点击侧边栏中的Storage -> Cookies -> https://bbs.yamibo.com 4. 复制 Cookie 中的 EeqY_2132_saltkey 值",
        "name": "YAMIBO_SALT",
        "optional": true
      },
      {
        "description": "百合会BBS登录后的认证信息，获取方式：1. 登录百合会BBS网页版 2. 打开浏览器开发者工具，切换到 Application 面板\n3. 点击侧边栏中的Storage -> Cookies -> https://bbs.yamibo.com 4. 复制 Cookie 中的 EeqY_2132_auth 值",
        "name": "YAMIBO_AUTH",
        "optional": true
      }
    ]
  },
  "location": "bbs/forum.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "module": "() => import('@/routes/yamibo/bbs/forum.ts')",
  "name": "BBS - 板块",
  "parameters": {
    "fid": "板块 id，可从URL中提取。https://bbs.yamibo.com/forum-aa-b.html中的aa部分即为fid值",
    "type": "板块子分类，网页中选中板块分类后URL中的typeid值"
  },
  "path": "/bbs/forum/:fid/:type?"
}
```
