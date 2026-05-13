# NIO - NIO Radio

## Coverage
`index-only`

## Route
- Namespace: `nio`
- Namespace Name: `NIO`
- Route Path: `/nioradio/:albumid`
- Route Name: `NIO Radio`
- Example: `/nio/nioradio/5`
- URL: `nio.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `marcosteam`
- Source Location: `nioradio.ts`
- Source Module: `() => import('@/routes/nio/nioradio.ts')`

## Description
::: tip
**如何获取电台 ID？**
打开蔚来 APP 后，点击“此地”→“NIO Radio”，找到自己想要转换为播客的专辑，分享后在生成的链接中找到`container_id=`后方的数字即可。
常见电台 ID：
| 电台名称          | 电台 ID |
| :------------ | :---- |
| 资讯充电站（早间版）    | 5     |
| 资讯充电站（晚间版）    | 23    |
| E 次元财经报       | 148   |
| 塞萌不塞车         | 661   |
| 乐行记           | 11    |
| Weekend Dance | 547   |
:::

## Parameters
- `albumid`: 电台专辑 ID


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
  "description": "\n::: tip\n**如何获取电台 ID？**\n打开蔚来 APP 后，点击“此地”→“NIO Radio”，找到自己想要转换为播客的专辑，分享后在生成的链接中找到`container_id=`后方的数字即可。\n常见电台 ID：\n| 电台名称          | 电台 ID |\n| :------------ | :---- |\n| 资讯充电站（早间版）    | 5     |\n| 资讯充电站（晚间版）    | 23    |\n| E 次元财经报       | 148   |\n| 塞萌不塞车         | 661   |\n| 乐行记           | 11    |\n| Weekend Dance | 547   |\n:::",
  "example": "/nio/nioradio/5",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "location": "nioradio.ts",
  "maintainers": [
    "marcosteam"
  ],
  "module": "() => import('@/routes/nio/nioradio.ts')",
  "name": "NIO Radio",
  "parameters": {
    "albumid": "电台专辑 ID"
  },
  "path": "/nioradio/:albumid"
}
```
