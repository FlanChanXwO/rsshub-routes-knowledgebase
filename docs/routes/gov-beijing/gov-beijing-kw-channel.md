# 北京市人民政府 - 北京市科学技术委员会、中关村科技园区管理委员会

## Coverage
`index-only`

## Route
- Namespace: `gov/beijing`
- Namespace Name: `北京市人民政府`
- Route Path: `/gov/beijing/kw/:channel`
- Route Name: `北京市科学技术委员会、中关村科技园区管理委员会`
- Example: `/gov/beijing/kw/col736`
- URL: `www.beijing.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `Fatpandac`
- Source Location: `kw/index.ts`
- Source Module: `_None_`

## Description
频道参数可在官网获取，如：

`http://kw.beijing.gov.cn/col/col736/index.html` 对应 `/gov/beijing/kw/col736`

## Parameters
- `channel`: 频道


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `kw.beijing.gov.cn/col/:channel/index.html`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "频道参数可在官网获取，如：\n\n`http://kw.beijing.gov.cn/col/col736/index.html` 对应 `/gov/beijing/kw/col736`",
  "example": "/gov/beijing/kw/col736",
  "heat": 0,
  "location": "kw/index.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "北京市科学技术委员会、中关村科技园区管理委员会",
  "parameters": {
    "channel": "频道"
  },
  "path": "/kw/:channel",
  "radar": [
    {
      "source": [
        "kw.beijing.gov.cn/col/:channel/index.html"
      ]
    }
  ],
  "topFeeds": []
}
```
