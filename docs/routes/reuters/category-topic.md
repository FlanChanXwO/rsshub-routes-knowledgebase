# Reuters - Category/Topic/Author

## Coverage
`index-only`

## Route
- Namespace: `reuters`
- Namespace Name: `Reuters`
- Route Path: `/:category/:topic?`
- Route Name: `Category/Topic/Author`
- Example: `/reuters/world/us`
- URL: `reuters.com`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `LyleLee, HenryQW, proletarius101, black-desk, nczitzk, pseudoyu`
- Source Location: `common.tsx`
- Source Module: `() => import('@/routes/reuters/common.tsx')`

## Description
-   `:category`:

      | World | Business | Legal | Markets | Breakingviews | Technology | Graphics |
      | ----- | -------- | ----- | ------- | ------------- | ---------- | -------- |
      | world | business | legal | markets | breakingviews | technology | graphics |

  -   `world/:topic`:

      | All | Africa | Americas | Asia Pacific | China | Europe | India | Middle East | United Kingdom | United States | The Great Reboot | Reuters Next |
      | --- | ------ | -------- | ------------ | ----- | ------ | ----- | ----------- | -------------- | ------------- | ---------------- | ------------ |
      |     | africa | americas | asia-pacific | china | europe | india | middle-east | uk             | us            | the-great-reboot | reuters-next |

  -   `business/:topic`:

      | All | Aerospace & Defense | Autos & Transportation | Energy | Environment | Finance | Healthcare & Pharmaceuticals | Media & Telecom | Retail & Consumer | Sustainable Business | Charged | Future of Health | Future of Money | Take Five | Reuters Impact |
      | --- | ------------------- | ---------------------- | ------ | ----------- | ------- | ---------------------------- | --------------- | ----------------- | -------------------- | ------- | ---------------- | --------------- | --------- | -------------- |
      |     | aerospace-defense   | autos-transportation   | energy | environment | finance | healthcare-pharmaceuticals   | media-telecom   | retail-consumer   | sustainable-business | charged | future-of-health | future-of-money | take-five | reuters-impact |

  -   `legal/:topic`:

      | All | Government | Legal Industry | Litigation | Transactional |
      | --- | ---------- | -------------- | ---------- | ------------- |
      |     | government | legalindustry  | litigation | transactional |

  -   `authors/:topic`:

      | Default | Jonathan Landay | any other authors |
      | ------- | --------------- | ----------------- |
      | reuters | jonathan-landay | their name in URL |

  More could be found in the URL of the category/topic page.

## Parameters
- `category`: {"default": "world", "description": "find it in the URL, or tables below", "options": [{"label": "World", "value": "world"}, {"label": "Business", "value": "business"}, {"label": "Legal", "value": "legal"}, {"label": "Markets", "value": "markets"}, {"label": "Breakingviews", "value": "breakingviews"}, {"label": "Technology", "value": "technology"}, {"label": "Graphics", "value": "graphics"}, {"label": "Authors", "value": "authors"}]}
- `topic`: find it in the URL, or tables below, leave empty for `All`


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
  - `reuters.com/:category/:topic?`
  - `reuters.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "-   `:category`:\n\n      | World | Business | Legal | Markets | Breakingviews | Technology | Graphics |\n      | ----- | -------- | ----- | ------- | ------------- | ---------- | -------- |\n      | world | business | legal | markets | breakingviews | technology | graphics |\n\n  -   `world/:topic`:\n\n      | All | Africa | Americas | Asia Pacific | China | Europe | India | Middle East | United Kingdom | United States | The Great Reboot | Reuters Next |\n      | --- | ------ | -------- | ------------ | ----- | ------ | ----- | ----------- | -------------- | ------------- | ---------------- | ------------ |\n      |     | africa | americas | asia-pacific | china | europe | india | middle-east | uk             | us            | the-great-reboot | reuters-next |\n\n  -   `business/:topic`:\n\n      | All | Aerospace & Defense | Autos & Transportation | Energy | Environment | Finance | Healthcare & Pharmaceuticals | Media & Telecom | Retail & Consumer | Sustainable Business | Charged | Future of Health | Future of Money | Take Five | Reuters Impact |\n      | --- | ------------------- | ---------------------- | ------ | ----------- | ------- | ---------------------------- | --------------- | ----------------- | -------------------- | ------- | ---------------- | --------------- | --------- | -------------- |\n      |     | aerospace-defense   | autos-transportation   | energy | environment | finance | healthcare-pharmaceuticals   | media-telecom   | retail-consumer   | sustainable-business | charged | future-of-health | future-of-money | take-five | reuters-impact |\n\n  -   `legal/:topic`:\n\n      | All | Government | Legal Industry | Litigation | Transactional |\n      | --- | ---------- | -------------- | ---------- | ------------- |\n      |     | government | legalindustry  | litigation | transactional |\n\n  -   `authors/:topic`:\n\n      | Default | Jonathan Landay | any other authors |\n      | ------- | --------------- | ----------------- |\n      | reuters | jonathan-landay | their name in URL |\n\n  More could be found in the URL of the category/topic page.",
  "example": "/reuters/world/us",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "common.tsx",
  "maintainers": [
    "LyleLee",
    "HenryQW",
    "proletarius101",
    "black-desk",
    "nczitzk",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/reuters/common.tsx')",
  "name": "Category/Topic/Author",
  "parameters": {
    "category": {
      "default": "world",
      "description": "find it in the URL, or tables below",
      "options": [
        {
          "label": "World",
          "value": "world"
        },
        {
          "label": "Business",
          "value": "business"
        },
        {
          "label": "Legal",
          "value": "legal"
        },
        {
          "label": "Markets",
          "value": "markets"
        },
        {
          "label": "Breakingviews",
          "value": "breakingviews"
        },
        {
          "label": "Technology",
          "value": "technology"
        },
        {
          "label": "Graphics",
          "value": "graphics"
        },
        {
          "label": "Authors",
          "value": "authors"
        }
      ]
    },
    "topic": "find it in the URL, or tables below, leave empty for `All`"
  },
  "path": "/:category/:topic?",
  "radar": [
    {
      "source": [
        "reuters.com/:category/:topic?",
        "reuters.com/"
      ]
    }
  ],
  "view": 0
}
```
