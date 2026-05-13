# 东西智库 - 分类

## Coverage
`index-only`

## Route
- Namespace: `dx2025`
- Namespace Name: `东西智库`
- Route Path: `/:type?/:category?`
- Route Name: `分类`
- Example: `/dx2025`
- URL: `dx2025.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/dx2025/index.ts')`

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
  "description": "内容类别\n\n| 产业观察             | 行业报告         | 政策   | 数据 |\n| -------------------- | ---------------- | ------ | ---- |\n| industry-observation | industry-reports | policy | data |\n\n  行业分类\n\n| 行业                 | 行业名称                                                          |\n| -------------------- | ----------------------------------------------------------------- |\n| 新一代信息技术       | next-generation-information-technology-industry-reports           |\n| 高档数控机床和机器人 | high-grade-cnc-machine-tools-and-robots-industry-reports          |\n| 航空航天装备         | aerospace-equipment-industry-reports                              |\n| 海工装备及高技术船舶 | marine-engineering-equipment-and-high-tech-ships-industry-reports |\n| 先进轨道交通装备     | advanced-rail-transportation-equipment-industry-reports           |\n| 节能与新能源汽车     | energy-saving-and-new-energy-vehicles-industry-reports            |\n| 电力装备             | electric-equipment-industry-reports                               |\n| 农机装备             | agricultural-machinery-equipment-industry-reports                 |\n| 新材料               | new-material-industry-reports                                     |\n| 生物医药及医疗器械   | biomedicine-and-medical-devices-industry-reports                  |\n| 现代服务业           | modern-service-industry-industry-reports                          |\n| 制造业人才           | manufacturing-talent-industry-reports                             |",
  "example": "/dx2025",
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
  "module": "() => import('@/routes/dx2025/index.ts')",
  "name": "分类",
  "parameters": {
    "category": "行业分类，见下表，默认为空",
    "type": "内容类别，见下表，默认为空"
  },
  "path": "/:type?/:category?"
}
```
