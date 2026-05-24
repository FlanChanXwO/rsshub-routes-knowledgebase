# National Museum Of China - Exhibitions

## Coverage
`index-only`

## Route
- Namespace: `chnmuseum`
- Namespace Name: `National Museum Of China`
- Route Path: `/chnmuseum/zl/:type?/:subType?`
- Route Name: `Exhibitions`
- Example: `/chnmuseum/zl/lszl/zdztzl`
- URL: `www.chnmuseum.cn`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `zl.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: Exhibition type, supported values: zhanlanyugao（正在展出）、ztzl（主题展览）、jbcl（基本陈列）、ztcl（专题展览）、lszl（临时展览）、gbxz（国博巡展）. Default: All exhibitions.
- `subType`: subtype only works under type lszl（临时展览）, supported values: zdztzl（主题展览）、dfjpwwxl（精品文物展）、lswhxl（历史文化展）、kgfjxl（考古发现展）、kjcxz（科技创新展）、dywhxl（地域文化展）、jdmszpxl（经典美术展）、gjjlxl（国际交流展）


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.chnmuseum.cn/zl/`
- `target`: `/zl`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/chnmuseum/zl/lszl/zdztzl",
  "heat": 0,
  "location": "zl.tsx",
  "maintainers": [
    "magazian"
  ],
  "name": "Exhibitions",
  "parameters": {
    "subType": "subtype only works under type lszl（临时展览）, supported values: zdztzl（主题展览）、dfjpwwxl（精品文物展）、lswhxl（历史文化展）、kgfjxl（考古发现展）、kjcxz（科技创新展）、dywhxl（地域文化展）、jdmszpxl（经典美术展）、gjjlxl（国际交流展）",
    "type": "Exhibition type, supported values: zhanlanyugao（正在展出）、ztzl（主题展览）、jbcl（基本陈列）、ztcl（专题展览）、lszl（临时展览）、gbxz（国博巡展）. Default: All exhibitions."
  },
  "path": "/zl/:type?/:subType?",
  "radar": [
    {
      "source": [
        "www.chnmuseum.cn/zl/"
      ],
      "target": "/zl"
    }
  ],
  "topFeeds": []
}
```
