# ASUS - BIOS

## Coverage
`index-only`

## Route
- Namespace: `asus`
- Namespace Name: `ASUS`
- Route Path: `/bios/:model/:lang?`
- Route Name: `BIOS`
- Example: `/asus/bios/RT-AX88U/zh`
- URL: `www.asus.com`
- Language: `zh-CN`
- Categories: `program-update`
- Maintainers: `Fatpandac`
- Source Location: `bios.tsx`
- Source Module: `() => import('@/routes/asus/bios.tsx')`

## Description
_None_

## Parameters
- `model`: Model, can be found in product page
- `lang`: {"default": "en", "description": "Language, provide access routes for other parts of the world", "options": [{"label": "Chinese", "value": "zh"}, {"label": "Global", "value": "en"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.asus.com/displays-desktops/:productLine/:series/:model`
  - `www.asus.com/laptops/:productLine/:series/:model`
  - `www.asus.com/motherboards-components/:productLine/:series/:model`
  - `www.asus.com/networking-iot-servers/:productLine/:series/:model`
  - `www.asus.com/:region/displays-desktops/:productLine/:series/:model`
  - `www.asus.com/:region/laptops/:productLine/:series/:model`
  - `www.asus.com/:region/motherboards-components/:productLine/:series/:model`
  - `www.asus.com/:region/networking-iot-servers/:productLine/:series/:model`
- `target`: `/bios/:model`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/asus/bios/RT-AX88U/zh",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "bios.tsx",
  "maintainers": [
    "Fatpandac"
  ],
  "module": "() => import('@/routes/asus/bios.tsx')",
  "name": "BIOS",
  "parameters": {
    "lang": {
      "default": "en",
      "description": "Language, provide access routes for other parts of the world",
      "options": [
        {
          "label": "Chinese",
          "value": "zh"
        },
        {
          "label": "Global",
          "value": "en"
        }
      ]
    },
    "model": "Model, can be found in product page"
  },
  "path": "/bios/:model/:lang?",
  "radar": [
    {
      "source": [
        "www.asus.com/displays-desktops/:productLine/:series/:model",
        "www.asus.com/laptops/:productLine/:series/:model",
        "www.asus.com/motherboards-components/:productLine/:series/:model",
        "www.asus.com/networking-iot-servers/:productLine/:series/:model",
        "www.asus.com/:region/displays-desktops/:productLine/:series/:model",
        "www.asus.com/:region/laptops/:productLine/:series/:model",
        "www.asus.com/:region/motherboards-components/:productLine/:series/:model",
        "www.asus.com/:region/networking-iot-servers/:productLine/:series/:model"
      ],
      "target": "/bios/:model"
    }
  ],
  "url": "www.asus.com"
}
```
