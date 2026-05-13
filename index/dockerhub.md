# Docker Hub Route Index

## Namespace
- Namespace: `dockerhub`
- Display Name: `Docker Hub`
- URL: `hub.docker.com`
- Language: `_None_`
- Aliases: `docker hub, dockerhub, hub, hub.docker.com`
- Route Count: `3`

## Routes

### Image New Build
- Route ID: `dockerhub:/dockerhub/build/:owner/:image/:tag?`
- Route Path: `/dockerhub/build/:owner/:image/:tag?`
- File: `docs/routes/dockerhub/dockerhub-build-owner-image-tag.md`
- File Name: `dockerhub-build-owner-image-tag.md`
- Categories: `program-update`
- Maintainers: `HenryQW`

### Owner Repositories
- Route ID: `dockerhub:/dockerhub/repositories/:owner`
- Route Path: `/dockerhub/repositories/:owner`
- File: `docs/routes/dockerhub/dockerhub-repositories-owner.md`
- File Name: `dockerhub-repositories-owner.md`
- Categories: `program-update`
- Maintainers: `CaoMeiYouRen`

### Image New Tag
- Route ID: `dockerhub:/dockerhub/tag/:owner/:image/:limits?`
- Route Path: `/dockerhub/tag/:owner/:image/:limits?`
- File: `docs/routes/dockerhub/dockerhub-tag-owner-image-limits.md`
- File Name: `dockerhub-tag-owner-image-limits.md`
- Categories: `program-update`
- Maintainers: `pseudoyu`
