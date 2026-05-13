# 云听 - 直播

## Coverage
`index-only`

## Route
- Namespace: `radio`
- Namespace Name: `云听`
- Route Path: `/zhibo/:id`
- Route Name: `直播`
- Example: `/radio/zhibo/1395528`
- URL: `radio.cn`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `zhibo.ts`
- Source Module: `() => import('@/routes/radio/zhibo.ts')`

## Description
如果订阅 [新闻和报纸摘要](http://www.radio.cn/pc-portal/sanji/zhibo_2.html?name=1395528)，其 URL 为 `http://www.radio.cn/pc-portal/sanji/zhibo_2.html?name=1395528`，可以得到 `name` 为 `1395528`

  所以对应路由为 [`/radio/zhibo/1395528`](https://rsshub.app/radio/zhibo/1395528)

::: tip
  查看更多电台直播节目，可前往 [电台直播](http://www.radio.cn/pc-portal/erji/radioStation.html)
:::

## Parameters
- `id`: 直播 id，可在对应点播页面的 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "如果订阅 [新闻和报纸摘要](http://www.radio.cn/pc-portal/sanji/zhibo_2.html?name=1395528)，其 URL 为 `http://www.radio.cn/pc-portal/sanji/zhibo_2.html?name=1395528`，可以得到 `name` 为 `1395528`\n\n  所以对应路由为 [`/radio/zhibo/1395528`](https://rsshub.app/radio/zhibo/1395528)\n\n::: tip\n  查看更多电台直播节目，可前往 [电台直播](http://www.radio.cn/pc-portal/erji/radioStation.html)\n:::",
  "example": "/radio/zhibo/1395528",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "location": "zhibo.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/radio/zhibo.ts')",
  "name": "直播",
  "parameters": {
    "id": "直播 id，可在对应点播页面的 URL 中找到"
  },
  "path": "/zhibo/:id"
}
```
