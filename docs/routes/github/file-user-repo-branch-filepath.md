# GitHub - File Commits

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/file/:user/:repo/:branch/:filepath{.+}`
- Route Name: `File Commits`
- Example: `/github/file/DIYgod/RSSHub/master/README.md`
- URL: `github.com`
- Language: `en`
- Categories: `None`
- Maintainers: `zengxs`
- Source Location: `file.ts`
- Source Module: `() => import('@/routes/github/file.ts')`

## Description
_None_

## Parameters
- `user`: GitHub user or org name
- `repo`: repository name
- `branch`: branch name
- `filepath`: path of target file


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `github.com/:user/:repo/blob/:branch/*filepath`
- `target`: `/file/:user/:repo/:branch/:filepath`

## Raw JSON
```json
{
  "example": "/github/file/DIYgod/RSSHub/master/README.md",
  "location": "file.ts",
  "maintainers": [
    "zengxs"
  ],
  "module": "() => import('@/routes/github/file.ts')",
  "name": "File Commits",
  "parameters": {
    "branch": "branch name",
    "filepath": "path of target file",
    "repo": "repository name",
    "user": "GitHub user or org name"
  },
  "path": "/file/:user/:repo/:branch/:filepath{.+}",
  "radar": [
    {
      "source": [
        "github.com/:user/:repo/blob/:branch/*filepath"
      ],
      "target": "/file/:user/:repo/:branch/:filepath"
    }
  ]
}
```
