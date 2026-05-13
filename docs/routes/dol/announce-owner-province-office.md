# Thailand Department of Lands - e-LandsAnnouncement

## Coverage
`index-only`

## Route
- Namespace: `dol`
- Namespace Name: `Thailand Department of Lands`
- Route Path: `/announce/:owner?/:province?/:office?`
- Route Name: `e-LandsAnnouncement`
- Example: `/dol/announce`
- URL: `announce.dol.go.th`
- Language: `en`
- Categories: `government`
- Maintainers: `itpcc`
- Source Location: `announce.ts`
- Source Module: `() => import('@/routes/dol/announce.ts')`

## Description
_None_

## Parameters
- `owner`: Requester/former land owner
- `province`: Province which the land is belongs to
- `office`: DOL office name which the land is belongs to (สำนักงานที่ดิน(กรุงเทพมหานคร|จังหวัด*) [สาขา*])


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
    "government"
  ],
  "example": "/dol/announce",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "announce.ts",
  "maintainers": [
    "itpcc"
  ],
  "module": "() => import('@/routes/dol/announce.ts')",
  "name": "e-LandsAnnouncement",
  "parameters": {
    "office": "DOL office name which the land is belongs to (สำนักงานที่ดิน(กรุงเทพมหานคร|จังหวัด*) [สาขา*])",
    "owner": "Requester/former land owner",
    "province": "Province which the land is belongs to"
  },
  "path": "/announce/:owner?/:province?/:office?"
}
```
