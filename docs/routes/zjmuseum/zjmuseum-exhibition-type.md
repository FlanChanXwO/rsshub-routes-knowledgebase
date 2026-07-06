# Zhejiang Provincial Museum - Temporary Exhibition

## Coverage
`index-only`

## Route
- Namespace: `zjmuseum`
- Namespace Name: `Zhejiang Provincial Museum`
- Route Path: `/zjmuseum/exhibition/:type?`
- Route Name: `Temporary Exhibition`
- Example: `/zjmuseum/exhibition/ondisplay`
- URL: `www.zjmuseum.com.cn/cn/`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `temporaryexhibition.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: Temporary Exhibition type, supported values: ondisplay （正在展出）、forecast（即将开始）、review（展览回顾）. Default: All exhibitions (ondisplay, forecast and review).


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.zjmuseum.com.cn/cn/`
- `target`: `/exhibition/:type?`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/zjmuseum/exhibition/ondisplay",
  "heat": 0,
  "location": "temporaryexhibition.tsx",
  "maintainers": [
    "magazian"
  ],
  "name": "Temporary Exhibition",
  "parameters": {
    "type": "Temporary Exhibition type, supported values: ondisplay （正在展出）、forecast（即将开始）、review（展览回顾）. Default: All exhibitions (ondisplay, forecast and review)."
  },
  "path": "/exhibition/:type?",
  "radar": [
    {
      "source": [
        "www.zjmuseum.com.cn/cn/"
      ],
      "target": "/exhibition/:type?"
    }
  ],
  "topFeeds": []
}
```
