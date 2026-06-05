# 东西智库 - 分类

## Coverage
`index-only`

## Route
- Namespace: `dx2025`
- Namespace Name: `东西智库`
- Route Path: `/dx2025/:type?/:category?`
- Route Name: `分类`
- Example: `/dx2025`
- URL: `dx2025.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
内容类别

| 产业观察             | 行业报告         | 政策   | 数据 |
| -------------------- | ---------------- | ------ | ---- |
| industry-observation | industry-reports | policy | data |

行业分类

| 行业                 | 行业名称                                                          |
| -------------------- | ----------------------------------------------------------------- |
| 新一代信息技术       | next-generation-information-technology-industry-reports           |
| 高档数控机床和机器人 | high-grade-cnc-machine-tools-and-robots-industry-reports          |
| 航空航天装备         | aerospace-equipment-industry-reports                              |
| 海工装备及高技术船舶 | marine-engineering-equipment-and-high-tech-ships-industry-reports |
| 先进轨道交通装备     | advanced-rail-transportation-equipment-industry-reports           |
| 节能与新能源汽车     | energy-saving-and-new-energy-vehicles-industry-reports            |
| 电力装备             | electric-equipment-industry-reports                               |
| 农机装备             | agricultural-machinery-equipment-industry-reports                 |
| 新材料               | new-material-industry-reports                                     |
| 生物医药及医疗器械   | biomedicine-and-medical-devices-industry-reports                  |
| 现代服务业           | modern-service-industry-industry-reports                          |
| 制造业人才           | manufacturing-talent-industry-reports                             |

## Parameters
- `type`: 内容类别，见下表，默认为空
- `category`: 行业分类，见下表，默认为空


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
  "description": "内容类别\n\n| 产业观察             | 行业报告         | 政策   | 数据 |\n| -------------------- | ---------------- | ------ | ---- |\n| industry-observation | industry-reports | policy | data |\n\n行业分类\n\n| 行业                 | 行业名称                                                          |\n| -------------------- | ----------------------------------------------------------------- |\n| 新一代信息技术       | next-generation-information-technology-industry-reports           |\n| 高档数控机床和机器人 | high-grade-cnc-machine-tools-and-robots-industry-reports          |\n| 航空航天装备         | aerospace-equipment-industry-reports                              |\n| 海工装备及高技术船舶 | marine-engineering-equipment-and-high-tech-ships-industry-reports |\n| 先进轨道交通装备     | advanced-rail-transportation-equipment-industry-reports           |\n| 节能与新能源汽车     | energy-saving-and-new-energy-vehicles-industry-reports            |\n| 电力装备             | electric-equipment-industry-reports                               |\n| 农机装备             | agricultural-machinery-equipment-industry-reports                 |\n| 新材料               | new-material-industry-reports                                     |\n| 生物医药及医疗器械   | biomedicine-and-medical-devices-industry-reports                  |\n| 现代服务业           | modern-service-industry-industry-reports                          |\n| 制造业人才           | manufacturing-talent-industry-reports                             |",
  "example": "/dx2025",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1087,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "category": "行业分类，见下表，默认为空",
    "type": "内容类别，见下表，默认为空"
  },
  "path": "/:type?/:category?",
  "topFeeds": [
    {
      "description": "东西智库 – 专注中国制造业高质量发展 - Powered by RSSHub",
      "errorAt": "2026-01-24T01:12:42.838Z",
      "errorMessage": "[GET] \"https://www.dx2025.com\": <no response> fetch failed\n403 Forbidden\n[GET] \"https://www.dx2025.com\": <no response> fetch failed\n",
      "id": "42579624844251167",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.dx2025.com/",
      "title": "东西智库 – 专注中国制造业高质量发展",
      "type": "feed",
      "url": "rsshub://dx2025"
    },
    {
      "description": "产业政策 – 东西智库 - Powered by RSSHub",
      "errorAt": "2025-07-03T14:50:41.118Z",
      "errorMessage": "Failed to fetch\n",
      "id": "89544052487792640",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.dx2025.com/archives/category/%E6%94%BF%E7%AD%96/policy",
      "title": "产业政策 – 东西智库",
      "type": "feed",
      "url": "rsshub://dx2025/%E6%94%BF%E7%AD%96/policy"
    }
  ]
}
```
