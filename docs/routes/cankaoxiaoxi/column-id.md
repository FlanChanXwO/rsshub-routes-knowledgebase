# 参考消息 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `cankaoxiaoxi`
- Namespace Name: `参考消息`
- Route Path: `/column/:id?`
- Route Name: `栏目`
- Example: `/cankaoxiaoxi/column/diyi`
- URL: `cankaoxiaoxi.com`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `yuxinliu-alex, nczitzk`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/cankaoxiaoxi/index.tsx')`

## Description
| 栏目           | id       |
| -------------- | -------- |
| 第一关注       | diyi     |
| 中国           | zhongguo |
| 国际           | gj       |
| 观点           | guandian |
| 锐参考         | ruick    |
| 体育健康       | tiyujk   |
| 科技应用       | kejiyy   |
| 文化旅游       | wenhualy |
| 参考漫谈       | cankaomt |
| 研究动态       | yjdt     |
| 海外智库       | hwzk     |
| 业界信息・观点 | yjxx     |
| 海外看中国城市 | hwkzgcs  |
| 译名趣谈       | ymymqt   |
| 译名发布       | ymymfb   |
| 双语汇         | ymsyh    |
| 参考视频       | video    |
| 军事           | junshi   |
| 参考人物       | cankaorw |

## Parameters
- `id`: 栏目 id，默认为 `diyi`，即第一关注


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
    "traditional-media"
  ],
  "description": "| 栏目           | id       |\n| -------------- | -------- |\n| 第一关注       | diyi     |\n| 中国           | zhongguo |\n| 国际           | gj       |\n| 观点           | guandian |\n| 锐参考         | ruick    |\n| 体育健康       | tiyujk   |\n| 科技应用       | kejiyy   |\n| 文化旅游       | wenhualy |\n| 参考漫谈       | cankaomt |\n| 研究动态       | yjdt     |\n| 海外智库       | hwzk     |\n| 业界信息・观点 | yjxx     |\n| 海外看中国城市 | hwkzgcs  |\n| 译名趣谈       | ymymqt   |\n| 译名发布       | ymymfb   |\n| 双语汇         | ymsyh    |\n| 参考视频       | video    |\n| 军事           | junshi   |\n| 参考人物       | cankaorw |",
  "example": "/cankaoxiaoxi/column/diyi",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.tsx",
  "maintainers": [
    "yuxinliu-alex",
    "nczitzk"
  ],
  "module": "() => import('@/routes/cankaoxiaoxi/index.tsx')",
  "name": "栏目",
  "parameters": {
    "id": "栏目 id，默认为 `diyi`，即第一关注"
  },
  "path": [
    "/column/:id?",
    "/:id?"
  ]
}
```
