# Docker Hub - Owner Repositories

## Coverage
`index-only`

## Route
- Namespace: `dockerhub`
- Namespace Name: `Docker Hub`
- Route Path: `/repositories/:owner`
- Route Name: `Owner Repositories`
- Example: `/dockerhub/repositories/diygod`
- URL: `hub.docker.com`
- Language: `en`
- Categories: `program-update`
- Maintainers: `CaoMeiYouRen`
- Source Location: `repositories.ts`
- Source Module: `() => import('@/routes/dockerhub/repositories.ts')`

## Description
List of repositories for an image owner

## Parameters
- `owner`: Image owner


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
  "description": "List of repositories for an image owner",
  "example": "/dockerhub/repositories/diygod",
  "location": "repositories.ts",
  "maintainers": [
    "CaoMeiYouRen"
  ],
  "module": "() => import('@/routes/dockerhub/repositories.ts')",
  "name": "Owner Repositories",
  "parameters": {
    "owner": "Image owner"
  },
  "path": "/repositories/:owner",
  "view": 5
}
```
