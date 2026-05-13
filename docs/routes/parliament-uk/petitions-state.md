# UK Parliament - Petitions

## Coverage
`index-only`

## Route
- Namespace: `parliament.uk`
- Namespace Name: `UK Parliament`
- Route Path: `/petitions/:state?`
- Route Name: `Petitions`
- Example: `/parliament.uk/petitions/all`
- URL: `petition.parliament.uk`
- Language: `en`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `petitions.tsx`
- Source Module: `() => import('@/routes/parliament.uk/petitions.tsx')`

## Description
::: tip
If you subscribe to [Recent petitions](https://petition.parliament.uk/petitions?state=recent)，where the URL is `https://petition.parliament.uk/petitions?state=recent`, use the value of `state` as the parameter to fill in. Therefore, the route will be [`/parliament.uk/petitions/recent`](https://rsshub.app/parliament.uk/petitions/recent).
:::

<details>
<summary>More states</summary>

| Name                            | ID                |
| ------------------------------- | ----------------- |
| All petitions                   | all               |
| Open petitions                  | open              |
| Recent petitions                | recent            |
| Closed petitions                | closed            |
| Rejected petitions              | rejected          |
| Awaiting government response    | awaiting_response |
| Government responses            | with_response     |
| Awaiting a debate in Parliament | awaiting_debate   |
| Debated in Parliament           | debated           |
| Not debated in Parliament       | not_debated       |

</details>

## Parameters
- `state`: State, `all` by default, see below


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `petition.parliament.uk/petitions`
### Rule 2
- `title`: `All petitions`
- `source`:
  - `petition.parliament.uk/petitions`
- `target`: `/petitions/all`
### Rule 3
- `title`: `Open petitions`
- `source`:
  - `petition.parliament.uk/petitions`
- `target`: `/petitions/open`
### Rule 4
- `title`: `Recent petitions`
- `source`:
  - `petition.parliament.uk/petitions`
- `target`: `/petitions/recent`
### Rule 5
- `title`: `Closed petitions`
- `source`:
  - `petition.parliament.uk/petitions`
- `target`: `/petitions/closed`
### Rule 6
- `title`: `Rejected petitions`
- `source`:
  - `petition.parliament.uk/petitions`
- `target`: `/petitions/rejected`
### Rule 7
- `title`: `Awaiting government response`
- `source`:
  - `petition.parliament.uk/petitions`
- `target`: `/petitions/awaiting_response`
### Rule 8
- `title`: `Government responses`
- `source`:
  - `petition.parliament.uk/petitions`
- `target`: `/petitions/with_response`
### Rule 9
- `title`: `Awaiting a debate in Parliament`
- `source`:
  - `petition.parliament.uk/petitions`
- `target`: `/petitions/awaiting_debate`
### Rule 10
- `title`: `Debated in Parliament`
- `source`:
  - `petition.parliament.uk/petitions`
- `target`: `/petitions/debated`
### Rule 11
- `title`: `Not debated in Parliament`
- `source`:
  - `petition.parliament.uk/petitions`
- `target`: `/petitions/not_debated`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\nIf you subscribe to [Recent petitions](https://petition.parliament.uk/petitions?state=recent)，where the URL is `https://petition.parliament.uk/petitions?state=recent`, use the value of `state` as the parameter to fill in. Therefore, the route will be [`/parliament.uk/petitions/recent`](https://rsshub.app/parliament.uk/petitions/recent).\n:::\n\n<details>\n<summary>More states</summary>\n\n| Name                            | ID                |\n| ------------------------------- | ----------------- |\n| All petitions                   | all               |\n| Open petitions                  | open              |\n| Recent petitions                | recent            |\n| Closed petitions                | closed            |\n| Rejected petitions              | rejected          |\n| Awaiting government response    | awaiting_response |\n| Government responses            | with_response     |\n| Awaiting a debate in Parliament | awaiting_debate   |\n| Debated in Parliament           | debated           |\n| Not debated in Parliament       | not_debated       |\n\n</details>\n    ",
  "example": "/parliament.uk/petitions/all",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "petitions.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/parliament.uk/petitions.tsx')",
  "name": "Petitions",
  "parameters": {
    "state": "State, `all` by default, see below"
  },
  "path": "/petitions/:state?",
  "radar": [
    {
      "source": [
        "petition.parliament.uk/petitions"
      ]
    },
    {
      "source": [
        "petition.parliament.uk/petitions"
      ],
      "target": "/petitions/all",
      "title": "All petitions"
    },
    {
      "source": [
        "petition.parliament.uk/petitions"
      ],
      "target": "/petitions/open",
      "title": "Open petitions"
    },
    {
      "source": [
        "petition.parliament.uk/petitions"
      ],
      "target": "/petitions/recent",
      "title": "Recent petitions"
    },
    {
      "source": [
        "petition.parliament.uk/petitions"
      ],
      "target": "/petitions/closed",
      "title": "Closed petitions"
    },
    {
      "source": [
        "petition.parliament.uk/petitions"
      ],
      "target": "/petitions/rejected",
      "title": "Rejected petitions"
    },
    {
      "source": [
        "petition.parliament.uk/petitions"
      ],
      "target": "/petitions/awaiting_response",
      "title": "Awaiting government response"
    },
    {
      "source": [
        "petition.parliament.uk/petitions"
      ],
      "target": "/petitions/with_response",
      "title": "Government responses"
    },
    {
      "source": [
        "petition.parliament.uk/petitions"
      ],
      "target": "/petitions/awaiting_debate",
      "title": "Awaiting a debate in Parliament"
    },
    {
      "source": [
        "petition.parliament.uk/petitions"
      ],
      "target": "/petitions/debated",
      "title": "Debated in Parliament"
    },
    {
      "source": [
        "petition.parliament.uk/petitions"
      ],
      "target": "/petitions/not_debated",
      "title": "Not debated in Parliament"
    }
  ],
  "url": "petition.parliament.uk",
  "view": 0
}
```
