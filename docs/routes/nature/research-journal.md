# Nature Journal - Latest Research

## Coverage
`index-only`

## Route
- Namespace: `nature`
- Namespace Name: `Nature Journal`
- Route Path: `/research/:journal?`
- Route Name: `Latest Research`
- Example: `/nature/research/ng`
- URL: `nature.com`
- Language: `en`
- Categories: `journal`
- Maintainers: `y9c, TonyRL, pseudoyu`
- Source Location: `research.ts`
- Source Module: `() => import('@/routes/nature/research.ts')`

## Description
|   `:journal`  |   Full Name of the Journal  | Route                                                                              |
| :-----------: | :-------------------------: | ---------------------------------------------------------------------------------- |
|     nature    |            Nature           | [/nature/research/nature](https://rsshub.app/nature/research/nature)               |
|      nbt      |     Nature Biotechnology    | [/nature/research/nbt](https://rsshub.app/nature/research/nbt)                     |
|     neuro     |     Nature Neuroscience     | [/nature/research/neuro](https://rsshub.app/nature/research/neuro)                 |
|       ng      |       Nature Genetics       | [/nature/research/ng](https://rsshub.app/nature/research/ng)                       |
|       ni      |      Nature Immunology      | [/nature/research/ni](https://rsshub.app/nature/research/ni)                       |
|     nmeth     |        Nature Method        | [/nature/research/nmeth](https://rsshub.app/nature/research/nmeth)                 |
|     nchem     |       Nature Chemistry      | [/nature/research/nchem](https://rsshub.app/nature/research/nchem)                 |
|      nmat     |       Nature Materials      | [/nature/research/nmat](https://rsshub.app/nature/research/nmat)                   |
| natmachintell | Nature Machine Intelligence | [/nature/research/natmachintell](https://rsshub.app/nature/research/natmachintell) |

  -   Using router (`/nature/research/` + "short name for a journal") to query latest research paper for a certain journal of Nature Publishing Group.
      If the `:journal` parameter is blank, then latest research of Nature will return.
  -   The journals from NPG are run by different group of people, and the website of may not be consitent for all the journals
  -   Only abstract is rendered in some researches

## Parameters
- `journal`: short name for a journal, `nature` by default


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: true

## Radar
### Rule 1
- `source`:
  - `nature.com/:journal/research-articles`
  - `nature.com/:journal`
  - `nature.com/`
- `target`: `/research/:journal`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "|   `:journal`  |   Full Name of the Journal  | Route                                                                              |\n| :-----------: | :-------------------------: | ---------------------------------------------------------------------------------- |\n|     nature    |            Nature           | [/nature/research/nature](https://rsshub.app/nature/research/nature)               |\n|      nbt      |     Nature Biotechnology    | [/nature/research/nbt](https://rsshub.app/nature/research/nbt)                     |\n|     neuro     |     Nature Neuroscience     | [/nature/research/neuro](https://rsshub.app/nature/research/neuro)                 |\n|       ng      |       Nature Genetics       | [/nature/research/ng](https://rsshub.app/nature/research/ng)                       |\n|       ni      |      Nature Immunology      | [/nature/research/ni](https://rsshub.app/nature/research/ni)                       |\n|     nmeth     |        Nature Method        | [/nature/research/nmeth](https://rsshub.app/nature/research/nmeth)                 |\n|     nchem     |       Nature Chemistry      | [/nature/research/nchem](https://rsshub.app/nature/research/nchem)                 |\n|      nmat     |       Nature Materials      | [/nature/research/nmat](https://rsshub.app/nature/research/nmat)                   |\n| natmachintell | Nature Machine Intelligence | [/nature/research/natmachintell](https://rsshub.app/nature/research/natmachintell) |\n\n  -   Using router (`/nature/research/` + \"short name for a journal\") to query latest research paper for a certain journal of Nature Publishing Group.\n      If the `:journal` parameter is blank, then latest research of Nature will return.\n  -   The journals from NPG are run by different group of people, and the website of may not be consitent for all the journals\n  -   Only abstract is rendered in some researches",
  "example": "/nature/research/ng",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": true
  },
  "location": "research.ts",
  "maintainers": [
    "y9c",
    "TonyRL",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/nature/research.ts')",
  "name": "Latest Research",
  "parameters": {
    "journal": "short name for a journal, `nature` by default"
  },
  "path": "/research/:journal?",
  "radar": [
    {
      "source": [
        "nature.com/:journal/research-articles",
        "nature.com/:journal",
        "nature.com/"
      ],
      "target": "/research/:journal"
    }
  ]
}
```
