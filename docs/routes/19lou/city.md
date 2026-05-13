# 19 楼 - 头条

## Coverage
`index-only`

## Route
- Namespace: `19lou`
- Namespace Name: `19 楼`
- Route Path: `/:city?`
- Route Name: `头条`
- Example: `/19lou/jiaxing`
- URL: `19lou.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/19lou/index.ts')`

## Description
| 杭州 | 台州    | 嘉兴    | 宁波   | 湖州   |
| ---- | ------- | ------- | ------ | ------ |
| www  | taizhou | jiaxing | ningbo | huzhou |

| 绍兴     | 湖州   | 温州    | 金华   | 舟山     |
| -------- | ------ | ------- | ------ | -------- |
| shaoxing | huzhou | wenzhou | jinhua | zhoushan |

| 衢州   | 丽水   | 义乌 | 萧山     | 余杭   |
| ------ | ------ | ---- | -------- | ------ |
| quzhou | lishui | yiwu | xiaoshan | yuhang |

| 临安  | 富阳   | 桐庐   | 建德   | 淳安   |
| ----- | ------ | ------ | ------ | ------ |
| linan | fuyang | tonglu | jiande | chunan |

## Parameters
- `city`: 分类，见下表，默认为 www，即杭州


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
    "bbs"
  ],
  "description": "| 杭州 | 台州    | 嘉兴    | 宁波   | 湖州   |\n| ---- | ------- | ------- | ------ | ------ |\n| www  | taizhou | jiaxing | ningbo | huzhou |\n\n| 绍兴     | 湖州   | 温州    | 金华   | 舟山     |\n| -------- | ------ | ------- | ------ | -------- |\n| shaoxing | huzhou | wenzhou | jinhua | zhoushan |\n\n| 衢州   | 丽水   | 义乌 | 萧山     | 余杭   |\n| ------ | ------ | ---- | -------- | ------ |\n| quzhou | lishui | yiwu | xiaoshan | yuhang |\n\n| 临安  | 富阳   | 桐庐   | 建德   | 淳安   |\n| ----- | ------ | ------ | ------ | ------ |\n| linan | fuyang | tonglu | jiande | chunan |",
  "example": "/19lou/jiaxing",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/19lou/index.ts')",
  "name": "头条",
  "parameters": {
    "city": "分类，见下表，默认为 www，即杭州"
  },
  "path": "/:city?"
}
```
