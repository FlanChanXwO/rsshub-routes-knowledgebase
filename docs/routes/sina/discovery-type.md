# 新浪 - 科技 - 科学探索

## Coverage
`index-only`

## Route
- Namespace: `sina`
- Namespace Name: `新浪`
- Route Path: `/discovery/:type`
- Route Name: `科技 - 科学探索`
- Example: `/sina/discovery/zx`
- URL: `finance.sina.com.cn`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `LogicJake`
- Source Location: `discovery.ts`
- Source Module: `() => import('@/routes/sina/discovery.ts')`

## Description
| 最新 | 天文航空 | 动物植物 | 自然地理 | 历史考古 | 生命医学 | 生活百科 | 科技前沿 |
| ---- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| zx   | twhk     | dwzw     | zrdl     | lskg     | smyx     | shbk     | kjqy     |

## Parameters
- `type`: 订阅分区类型，见下表


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
  "description": "| 最新 | 天文航空 | 动物植物 | 自然地理 | 历史考古 | 生命医学 | 生活百科 | 科技前沿 |\n| ---- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |\n| zx   | twhk     | dwzw     | zrdl     | lskg     | smyx     | shbk     | kjqy     |",
  "example": "/sina/discovery/zx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "discovery.ts",
  "maintainers": [
    "LogicJake"
  ],
  "module": "() => import('@/routes/sina/discovery.ts')",
  "name": "科技 - 科学探索",
  "parameters": {
    "type": "订阅分区类型，见下表"
  },
  "path": "/discovery/:type"
}
```
