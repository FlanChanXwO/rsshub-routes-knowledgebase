# Docker Hub Route Index

## Namespace
- Namespace: `dockerhub`
- Display Name: `Docker Hub`
- URL: `hub.docker.com`
- Language: `en`
- Aliases: `docker hub, dockerhub, hub, hub.docker.com`
- Route Count: `3`

## Routes

### Image New Build
- Route ID: `dockerhub:/build/:owner/:image/:tag?`
- Route Path: `/build/:owner/:image/:tag?`
- File: `docs/routes/dockerhub/build-owner-image-tag.md`
- File Name: `build-owner-image-tag.md`
- Categories: `program-update`
- Maintainers: `HenryQW`

### Owner Repositories
- Route ID: `dockerhub:/repositories/:owner`
- Route Path: `/repositories/:owner`
- File: `docs/routes/dockerhub/repositories-owner.md`
- File Name: `repositories-owner.md`
- Categories: `program-update`
- Maintainers: `CaoMeiYouRen`

### Image New Tag
- Route ID: `dockerhub:/tag/:owner/:image/:limits?`
- Route Path: `/tag/:owner/:image/:limits?`
- File: `docs/routes/dockerhub/tag-owner-image-limits.md`
- File Name: `tag-owner-image-limits.md`
- Categories: `program-update`
- Maintainers: `pseudoyu`
