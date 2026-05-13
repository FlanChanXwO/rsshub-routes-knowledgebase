# 百合会 - BBS - 讨论串

## Coverage
`index-only`

## Route
- Namespace: `yamibo`
- Namespace Name: `百合会`
- Route Path: `/bbs/thread/:tid`
- Route Name: `BBS - 讨论串`
- Example: `/yamibo/bbs/thread/541914`
- URL: `yamibo.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `KarasuShin`
- Source Location: `bbs/thread.ts`
- Source Module: `() => import('@/routes/yamibo/bbs/thread.ts')`

## Description
::: warning
百合会BBS访问部分讨论串需要用户登录认证，请参考配置说明
:::

## Parameters
- `tid`: 讨论串 id，可从URL中提取。https://bbs.yamibo.com/forum.php?mod=viewthread&tid=xxxx中的xxx或https://bbs.yamibo.com/thread-aaa-b-c.html中的aaa部分即为tid值


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
  "description": "::: warning\n百合会BBS访问部分讨论串需要用户登录认证，请参考配置说明\n:::",
  "example": "/yamibo/bbs/thread/541914",
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
  "location": "bbs/thread.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "module": "() => import('@/routes/yamibo/bbs/thread.ts')",
  "name": "BBS - 讨论串",
  "parameters": {
    "tid": "讨论串 id，可从URL中提取。https://bbs.yamibo.com/forum.php?mod=viewthread&tid=xxxx中的xxx或https://bbs.yamibo.com/thread-aaa-b-c.html中的aaa部分即为tid值"
  },
  "path": "/bbs/thread/:tid"
}
```
