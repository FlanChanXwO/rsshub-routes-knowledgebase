# 明月中文网 - 分类

## Coverage
`index-only`

## Route
- Namespace: `56kog`
- Namespace Name: `明月中文网`
- Route Path: `/class/:category?`
- Route Name: `分类`
- Example: `/56kog/class/1_1`
- URL: `56kog.com`
- Language: `zh-CN`
- Categories: `reading`
- Maintainers: `nczitzk`
- Source Location: `class.ts`
- Source Module: `() => import('@/routes/56kog/class.ts')`

## Description
| [玄幻魔法](https://www.56kog.com/class/1_1.html) | [武侠修真](https://www.56kog.com/class/2_1.html) | [历史军事](https://www.56kog.com/class/4_1.html) | [侦探推理](https://www.56kog.com/class/5_1.html) | [网游动漫](https://www.56kog.com/class/6_1.html) |
| ------------------------------------------------ | ------------------------------------------------ | ------------------------------------------------ | ------------------------------------------------ | ------------------------------------------------ |
| 1_1                                             | 2_1                                             | 4_1                                             | 5_1                                             | 6_1                                             |

| [恐怖灵异](https://www.56kog.com/class/8_1.html) | [都市言情](https://www.56kog.com/class/3_1.html) | [科幻](https://www.56kog.com/class/7_1.html) | [女生小说](https://www.56kog.com/class/9_1.html) | [其他](https://www.56kog.com/class/10_1.html) |
| ------------------------------------------------ | ------------------------------------------------ | -------------------------------------------- | ------------------------------------------------ | --------------------------------------------- |
| 8_1                                             | 3_1                                             | 7_1                                         | 9_1                                             | 10_1                                         |

## Parameters
- `category`: 分类，见下表，默认为玄幻魔法


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
    "reading"
  ],
  "description": "| [玄幻魔法](https://www.56kog.com/class/1_1.html) | [武侠修真](https://www.56kog.com/class/2_1.html) | [历史军事](https://www.56kog.com/class/4_1.html) | [侦探推理](https://www.56kog.com/class/5_1.html) | [网游动漫](https://www.56kog.com/class/6_1.html) |\n| ------------------------------------------------ | ------------------------------------------------ | ------------------------------------------------ | ------------------------------------------------ | ------------------------------------------------ |\n| 1_1                                             | 2_1                                             | 4_1                                             | 5_1                                             | 6_1                                             |\n\n| [恐怖灵异](https://www.56kog.com/class/8_1.html) | [都市言情](https://www.56kog.com/class/3_1.html) | [科幻](https://www.56kog.com/class/7_1.html) | [女生小说](https://www.56kog.com/class/9_1.html) | [其他](https://www.56kog.com/class/10_1.html) |\n| ------------------------------------------------ | ------------------------------------------------ | -------------------------------------------- | ------------------------------------------------ | --------------------------------------------- |\n| 8_1                                             | 3_1                                             | 7_1                                         | 9_1                                             | 10_1                                         |",
  "example": "/56kog/class/1_1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "class.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/56kog/class.ts')",
  "name": "分类",
  "parameters": {
    "category": "分类，见下表，默认为玄幻魔法"
  },
  "path": "/class/:category?"
}
```
