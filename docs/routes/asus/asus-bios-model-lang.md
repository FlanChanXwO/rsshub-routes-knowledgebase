# ASUS - BIOS

## Coverage
`index-only`

## Route
- Namespace: `asus`
- Namespace Name: `ASUS`
- Route Path: `/asus/bios/:model/:lang?`
- Route Name: `BIOS`
- Example: `/asus/bios/RT-AX88U/zh`
- URL: `www.asus.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `Fatpandac`
- Source Location: `bios.tsx`
- Source Module: `_None_`

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
  "heat": 7,
  "location": "bios.tsx",
  "maintainers": [
    "Fatpandac"
  ],
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
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "ROG Zephyrus G16 (2024) GA605 BIOS - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84439902528045056",
      "image": "https://dlcdnwebimgs.asus.com/gain/90DC1EAA-393C-49B0-A7F0-10870C086D86/w185",
      "ownerUserId": null,
      "siteUrl": "https://rog.asus.com/laptops/rog-zephyrus/rog-zephyrus-g16-2024-ga605/",
      "title": "ROG Zephyrus G16 (2024) GA605 BIOS",
      "type": "feed",
      "url": "rsshub://asus/bios/GA605WV"
    },
    {
      "description": "ROG STRIX B560-A GAMING WIFI BIOS - Powered by RSSHub",
      "errorAt": "2025-03-18T06:24:28.802Z",
      "errorMessage": "Cannot read properties of undefined (reading 'Obj')\n",
      "id": "73279691433742336",
      "image": "https://dlcdnwebimgs.asus.com.cn/gain/2E6CCF1B-9A03-43B9-A991-CDE4A9704E00/w185",
      "ownerUserId": null,
      "siteUrl": "https://rog.asus.com.cn/motherboards/rog-strix/rog-strix-b560-a-gaming-wifi-model/",
      "title": "ROG STRIX B560-A GAMING WIFI BIOS",
      "type": "feed",
      "url": "rsshub://asus/bios/rog-strix-b560-i-gaming-wifi-model/zh"
    }
  ],
  "url": "www.asus.com"
}
```
