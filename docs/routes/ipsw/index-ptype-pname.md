# IPSW.me - Apple Firmware Update-IPSWs/OTAs version

## Coverage
`index-only`

## Route
- Namespace: `ipsw`
- Namespace Name: `IPSW.me`
- Route Path: `/index/:ptype/:pname`
- Route Name: `Apple Firmware Update-IPSWs/OTAs version`
- Example: `/ipsw/index/ipsws/iPad8,11`
- URL: `ipsw.me`
- Language: `zh-CN`
- Categories: `program-update`
- Maintainers: `Jeason0228`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/ipsw/index.ts')`

## Description
_None_

## Parameters
- `ptype`: Fill in ipsws or otas to get different versions of firmware
- `pname`: Product name, `http://rsshub.app/ipsw/index/ipsws/iPod`, if you fill in the iPad, follow the entire iPad series(ptype default to ipsws).`http://rsshub.app/ipsw/index/ipsws/iPhone11,8`, if you fill in the specific iPhone11,8, submit to the ipsws firmware information of this model


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/ipsw/index/ipsws/iPad8,11",
  "location": "index.ts",
  "maintainers": [
    "Jeason0228"
  ],
  "module": "() => import('@/routes/ipsw/index.ts')",
  "name": "Apple Firmware Update-IPSWs/OTAs version",
  "parameters": {
    "pname": "Product name, `http://rsshub.app/ipsw/index/ipsws/iPod`, if you fill in the iPad, follow the entire iPad series(ptype default to ipsws).`http://rsshub.app/ipsw/index/ipsws/iPhone11,8`, if you fill in the specific iPhone11,8, submit to the ipsws firmware information of this model",
    "ptype": "Fill in ipsws or otas to get different versions of firmware"
  },
  "path": "/index/:ptype/:pname"
}
```
