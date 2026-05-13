# iFi audio - Download Hub

## Coverage
`index-only`

## Route
- Namespace: `ifi-audio`
- Namespace Name: `iFi audio`
- Route Path: `/download/:val/:id`
- Route Name: `Download Hub`
- Example: `/ifi-audio/download/1503007035/44472`
- URL: `ifi-audio.com`
- Language: `en`
- Categories: `program-update`
- Maintainers: `EthanWng97`
- Source Location: `download.ts`
- Source Module: `() => import('@/routes/ifi-audio/download.ts')`

## Description
::: warning
1.  Open [https://ifi-audio.com/download-hub](https://ifi-audio.com/download-hub) and the Network panel
2.  Select the device and the corresponding serial number in the website and click Search
3.  Find the last request named `https://ifi-audio.com/wp-admin/admin-ajax.php` in the Network panel, find out the val and id in the Payload panel, and fill in the url
:::

## Parameters
- `val`: product val
- `id`: product id


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
    "program-update"
  ],
  "description": "::: warning\n1.  Open [https://ifi-audio.com/download-hub](https://ifi-audio.com/download-hub) and the Network panel\n2.  Select the device and the corresponding serial number in the website and click Search\n3.  Find the last request named `https://ifi-audio.com/wp-admin/admin-ajax.php` in the Network panel, find out the val and id in the Payload panel, and fill in the url\n:::",
  "example": "/ifi-audio/download/1503007035/44472",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "download.ts",
  "maintainers": [
    "EthanWng97"
  ],
  "module": "() => import('@/routes/ifi-audio/download.ts')",
  "name": "Download Hub",
  "parameters": {
    "id": "product id",
    "val": "product val"
  },
  "path": "/download/:val/:id"
}
```
