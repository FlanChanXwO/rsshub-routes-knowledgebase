# 空气质量 - 实时 AQI

## Coverage
`index-only`

## Route
- Namespace: `aqicn`
- Namespace Name: `空气质量`
- Route Path: `/:city/:pollution?`
- Route Name: `实时 AQI`
- Example: `/aqicn/beijing/pm25`
- URL: `aqicn.org`
- Language: `zh-CN`
- Categories: `other`
- Maintainers: `ladeng07`
- Source Location: `aqi.ts`
- Source Module: `() => import('@/routes/aqicn/aqi.ts')`

## Description
_None_

## Parameters
- `city`: 城市拼音或地区 ID，详见[aqicn.org](http://aqicn.org/city/)
- `pollution`: 可选择显示更详细的空气污染成分


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `aqicn.org`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "descriptions": "\n|   参数   | 污染成分 |\n| -------- | -------- |\n|   pm25   |  PM2.5   |\n|   pm10   |  PM10    |\n|   o3     |  O3      |\n|   no2    |  NO2     |\n|   so2    |  SO2     |\n|   co     |  CO      |\n\n举例: [https://rsshub.app/aqicn/beijing/pm25,pm10](https://rsshub.app/aqicn/beijing/pm25,pm10)\n\n1. 显示单个污染成分，例如「pm25」, [https://rsshub.app/aqicn/beijing/pm25](https://rsshub.app/aqicn/beijing/pm25)\n2. 逗号分隔显示多个污染成分，例如「pm25,pm10」，[https://rsshub.app/aqicn/beijing/pm25,pm10](https://rsshub.app/aqicn/beijing/pm25,pm10)\n3. 城市子站 ID 获取方法：右键显示网页源代码，搜索 \"idx\" （带双冒号），后面的 ID 就是子站的 ID，如你给的链接 ID 是 4258，RSS 地址就是 [https://rsshub.app/aqicn/4258](https://rsshub.app/aqicn/4258)\n",
  "example": "/aqicn/beijing/pm25",
  "location": "aqi.ts",
  "maintainers": [
    "ladeng07"
  ],
  "module": "() => import('@/routes/aqicn/aqi.ts')",
  "name": "实时 AQI",
  "parameters": {
    "city": "城市拼音或地区 ID，详见[aqicn.org](http://aqicn.org/city/)",
    "pollution": "可选择显示更详细的空气污染成分"
  },
  "path": "/:city/:pollution?",
  "radar": [
    {
      "source": [
        "aqicn.org"
      ]
    }
  ],
  "url": "aqicn.org"
}
```
