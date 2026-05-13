# 知乎 - xhu - 用户动态

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/xhu/people/activities/:hexId`
- Route Name: `xhu - 用户动态`
- Example: `/zhihu/xhu/people/activities/246e6cf44e94cefbf4b959cb5042bc91`
- URL: `www.zhihu.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `JimenezLi`
- Source Location: `xhu/activities.ts`
- Source Module: `() => import('@/routes/zhihu/xhu/activities.ts')`

## Description
[xhu](https://github.com/REToys/xhu)

::: tip
  用户的 16 进制 id 获取方式：

  1.  可以通过 RSSHub Radar 扩展获取；
  2.  或者在用户主页打开 F12 控制台，执行以下代码：`console.log(/"id":"([0-9a-f]*?)","urlToken"/.exec(document.getElementById('js-initialData').innerHTML)[1]);` 即可获取用户的 16 进制 id。
:::

## Parameters
- `hexId`: 用户的 16 进制 id，获取方式见下方说明


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
  - `www.zhihu.com/people/:id`
- `target`: `/people/activities/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "[xhu](https://github.com/REToys/xhu)\n\n::: tip\n  用户的 16 进制 id 获取方式：\n\n  1.  可以通过 RSSHub Radar 扩展获取；\n  2.  或者在用户主页打开 F12 控制台，执行以下代码：`console.log(/\"id\":\"([0-9a-f]*?)\",\"urlToken\"/.exec(document.getElementById('js-initialData').innerHTML)[1]);` 即可获取用户的 16 进制 id。\n:::",
  "example": "/zhihu/xhu/people/activities/246e6cf44e94cefbf4b959cb5042bc91",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "xhu/activities.ts",
  "maintainers": [
    "JimenezLi"
  ],
  "module": "() => import('@/routes/zhihu/xhu/activities.ts')",
  "name": "xhu - 用户动态",
  "parameters": {
    "hexId": "用户的 16 进制 id，获取方式见下方说明"
  },
  "path": "/xhu/people/activities/:hexId",
  "radar": [
    {
      "source": [
        "www.zhihu.com/people/:id"
      ],
      "target": "/people/activities/:id"
    }
  ]
}
```
