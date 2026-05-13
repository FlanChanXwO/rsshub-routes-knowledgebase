# 穆迪评级 - industry

## Coverage
`index-only`

## Route
- Namespace: `moodysmismicrosite`
- Namespace Name: `穆迪评级`
- Route Path: `/report/:industry?`
- Route Name: `industry`
- Example: `/moodysmismicrosite/report/企业&金融机构`
- URL: `www.moodysmismicrosite.com`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `Cedaric`
- Source Location: `report.ts`
- Source Module: `() => import('@/routes/moodysmismicrosite/report.ts')`

## Description
| ID | Description |
| ---   | ---   |
| 0 | 企业 |
| 1 | 金融机构 |
| 2 | 主权 |
| 3 | 地方政府及城投公司 |
| 4 | 宏观经济 |
| 5 | 结构融资 |
| 6 | 基础设施项目融资 |
| 7 | ESG |
| 8 | 其他 |

## Parameters
- `industry`: {"default": "全部", "description": "可选参数，默认为全部行业。行业选择，支持使用&连接多个。", "options": [{"label": "企业", "value": "0"}, {"label": "金融机构", "value": "1"}, {"label": "主权", "value": "2"}, {"label": "地方政府及城投公司", "value": "3"}, {"label": "宏观经济", "value": "4"}, {"label": "结构融资", "value": "5"}, {"label": "基础设施及项目融资", "value": "6"}, {"label": "ESG", "value": "7"}, {"label": "其他", "value": "8"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.moodysmismicrosite.com/report`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "\n| ID | Description |\n| ---   | ---   |\n| 0 | 企业 |\n| 1 | 金融机构 |\n| 2 | 主权 |\n| 3 | 地方政府及城投公司 |\n| 4 | 宏观经济 |\n| 5 | 结构融资 |\n| 6 | 基础设施项目融资 |\n| 7 | ESG |\n| 8 | 其他 |\n    ",
  "example": "/moodysmismicrosite/report/企业&金融机构",
  "location": "report.ts",
  "maintainers": [
    "Cedaric"
  ],
  "module": "() => import('@/routes/moodysmismicrosite/report.ts')",
  "name": "industry",
  "parameters": {
    "industry": {
      "default": "全部",
      "description": "可选参数，默认为全部行业。行业选择，支持使用&连接多个。",
      "options": [
        {
          "label": "企业",
          "value": "0"
        },
        {
          "label": "金融机构",
          "value": "1"
        },
        {
          "label": "主权",
          "value": "2"
        },
        {
          "label": "地方政府及城投公司",
          "value": "3"
        },
        {
          "label": "宏观经济",
          "value": "4"
        },
        {
          "label": "结构融资",
          "value": "5"
        },
        {
          "label": "基础设施及项目融资",
          "value": "6"
        },
        {
          "label": "ESG",
          "value": "7"
        },
        {
          "label": "其他",
          "value": "8"
        }
      ]
    }
  },
  "path": "/report/:industry?",
  "radar": [
    {
      "source": [
        "www.moodysmismicrosite.com/report"
      ]
    }
  ],
  "view": 0
}
```
