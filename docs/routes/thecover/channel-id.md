# 封面新闻 - 频道

## Coverage
`index-only`

## Route
- Namespace: `thecover`
- Namespace Name: `封面新闻`
- Route Path: `/channel/:id?`
- Route Name: `频道`
- Example: `/thecover/channel/3560`
- URL: `thecover.cn`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `yuxinliu-alex`
- Source Location: `channel.ts`
- Source Module: `() => import('@/routes/thecover/channel.ts')`

## Description
| 天下 | 四川 | 辟谣 | 国际 | 云招考 | 30 秒 | 拍客 | 体育 | 国内 | 帮扶铁军 | 文娱 | 宽窄 | 商业 | 千面 | 封面号 |
| ---- | ---- | ---- | ---- | ------ | ----- | ---- | ---- | ---- | -------- | ---- | ---- | ---- | ---- | ------ |
| 3892 | 3560 | 3909 | 3686 | 11     | 3902  | 3889 | 3689 | 1    | 4002     | 12   | 46   | 4    | 21   | 17     |

## Parameters
- `id`: 对应id,可在频道链接中获取，默认为3892


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
    "new-media"
  ],
  "description": "| 天下 | 四川 | 辟谣 | 国际 | 云招考 | 30 秒 | 拍客 | 体育 | 国内 | 帮扶铁军 | 文娱 | 宽窄 | 商业 | 千面 | 封面号 |\n| ---- | ---- | ---- | ---- | ------ | ----- | ---- | ---- | ---- | -------- | ---- | ---- | ---- | ---- | ------ |\n| 3892 | 3560 | 3909 | 3686 | 11     | 3902  | 3889 | 3689 | 1    | 4002     | 12   | 46   | 4    | 21   | 17     |",
  "example": "/thecover/channel/3560",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "channel.ts",
  "maintainers": [
    "yuxinliu-alex"
  ],
  "module": "() => import('@/routes/thecover/channel.ts')",
  "name": "频道",
  "parameters": {
    "id": "对应id,可在频道链接中获取，默认为3892"
  },
  "path": "/channel/:id?"
}
```
