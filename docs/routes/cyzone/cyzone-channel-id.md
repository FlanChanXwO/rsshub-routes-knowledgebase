# 创业邦 - Unknown

## Coverage
`index-only`

## Route
- Namespace: `cyzone`
- Namespace Name: `创业邦`
- Route Path: `/cyzone/channel/:id?`
- Route Name: `Unknown`
- Example: `_None_`
- URL: `cyzone.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 最新 | 快鲤鱼 | 创投 | 科创板 | 汽车 |
| ---- | ------ | ---- | ------ | ---- |
| news | 5      | 14   | 13     | 8    |

| 海外 | 消费 | 科技 | 医疗 | 文娱 |
| ---- | ---- | ---- | ---- | ---- |
| 10   | 9    | 7    | 27   | 11   |

| 城市 | 政策 | 特写 | 干货 | 科技股 |
| ---- | ---- | ---- | ---- | ------ |
| 16   | 15   | 6    | 12   | 33     |

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `cyzone.cn/channel/:id`
  - `cyzone.cn/`
- `target`: `/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 最新 | 快鲤鱼 | 创投 | 科创板 | 汽车 |\n| ---- | ------ | ---- | ------ | ---- |\n| news | 5      | 14   | 13     | 8    |\n\n| 海外 | 消费 | 科技 | 医疗 | 文娱 |\n| ---- | ---- | ---- | ---- | ---- |\n| 10   | 9    | 7    | 27   | 11   |\n\n| 城市 | 政策 | 特写 | 干货 | 科技股 |\n| ---- | ---- | ---- | ---- | ------ |\n| 16   | 15   | 6    | 12   | 33     |",
  "heat": 1,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Unknown",
  "path": [
    "/channel/:id?",
    "/:id?"
  ],
  "radar": [
    {
      "source": [
        "cyzone.cn/channel/:id",
        "cyzone.cn/"
      ],
      "target": "/:id"
    }
  ],
  "topFeeds": [
    {
      "description": "创业邦作为国际创新生态服务平台，为高成长企业、金融机构、产业园区、地方政府提供全方位的媒体资讯、数字会展、数据研究、创新咨询、教育培训、资本对接等服务。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74251279349151744",
      "image": "https://static.cyzone.cn/img/logo/orange.png",
      "ownerUserId": null,
      "siteUrl": "https://www.cyzone.cn/channel/news",
      "title": "最新资讯 - 创业邦",
      "type": "feed",
      "url": "rsshub://cyzone/channel/news"
    }
  ]
}
```
