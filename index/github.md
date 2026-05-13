# GitHub Route Index

## Namespace
- Namespace: `github`
- Display Name: `GitHub`
- URL: `github.com`
- Language: `en`
- Aliases: `github, github.com`
- Route Count: `24`

## Routes

### User Activities
- Route ID: `github:/activity/:user`
- Route Path: `/activity/:user`
- File: `docs/routes/github/activity-user.md`
- File Name: `activity-user.md`
- Categories: `programming`
- Maintainers: `hyoban`

### Github Advisory Database RSS
- Route ID: `github:/advisor/data/:type?/:category?`
- Route Path: `/advisor/data/:type?/:category?`
- File: `docs/routes/github/advisor-data-type-category.md`
- File Name: `advisor-data-type-category.md`
- Categories: `programming`
- Maintainers: `sd0ric4`

### Repo Branches
- Route ID: `github:/branches/:user/:repo`
- Route Path: `/branches/:user/:repo`
- File: `docs/routes/github/branches-user-repo.md`
- File Name: `branches-user-repo.md`
- Categories: `programming`
- Maintainers: `max-arnold`

### Issue / Pull Request comments
- Route ID: `github:/comments/:user/:repo/:number?`
- Route Path: `/comments/:user/:repo/:number?`
- File: `docs/routes/github/comments-user-repo-number.md`
- File Name: `comments-user-repo-number.md`
- Categories: `programming`
- Maintainers: `TonyRL, FliegendeWurst`

### Repo Contributors
- Route ID: `github:/contributors/:user/:repo/:order?/:anon?`
- Route Path: `/contributors/:user/:repo/:order?/:anon?`
- File: `docs/routes/github/contributors-user-repo-order-anon.md`
- File Name: `contributors-user-repo-order-anon.md`
- Categories: `programming`
- Maintainers: `zoenglinghou`

### Repo Discussions
- Route ID: `github:/discussion/:user/:repo/:state?/:category?`
- Route Path: `/discussion/:user/:repo/:state?/:category?`
- File: `docs/routes/github/discussion-user-repo-state-category.md`
- File Name: `discussion-user-repo-state-category.md`
- Categories: `programming`
- Maintainers: `waynzh`

### User's Feed
- Route ID: `github:/feed/:user/:types?`
- Route Path: `/feed/:user/:types?`
- File: `docs/routes/github/feed-user-types.md`
- File Name: `feed-user-types.md`
- Categories: `programming`
- Maintainers: `RtYkk`

### File Commits
- Route ID: `github:/file/:user/:repo/:branch/:filepath{.+}`
- Route Path: `/file/:user/:repo/:branch/:filepath{.+}`
- File: `docs/routes/github/file-user-repo-branch-filepath.md`
- File Name: `file-user-repo-branch-filepath.md`
- Categories: `None`
- Maintainers: `zengxs`

### Gist Commits
- Route ID: `github:/gist/:gistId`
- Route Path: `/gist/:gistId`
- File: `docs/routes/github/gist-gistid.md`
- File Name: `gist-gistid.md`
- Categories: `programming`
- Maintainers: `TonyRL`

### Repo Issues
- Route ID: `github:/issue/:user/:repo/:state?/:labels?`
- Route Path: `/issue/:user/:repo/:state?/:labels?`
- File: `docs/routes/github/issue-user-repo-state-labels.md`
- File Name: `issue-user-repo-state-labels.md`
- Categories: `programming`
- Maintainers: `HenryQW, AndreyMZ`

### Notifications
- Route ID: `github:/notifications`
- Route Path: `/notifications`
- File: `docs/routes/github/notifications.md`
- File Name: `notifications.md`
- Categories: `programming`
- Maintainers: `zhzy0077`

### Organization Event
- Route ID: `github:/org_event/:org/:types?`
- Route Path: `/org_event/:org/:types?`
- File: `docs/routes/github/org_event-org-types.md`
- File Name: `org_event-org-types.md`
- Categories: `programming`
- Maintainers: `mslxl`

### Repo Pull Requests
- Route ID: `github:/pull/:user/:repo/:state?/:labels?`
- Route Path: `/pull/:user/:repo/:state?/:labels?`
- File: `docs/routes/github/pull-user-repo-state-labels.md`
- File Name: `pull-user-repo-state-labels.md`
- Categories: `programming`
- Maintainers: `hashman, TonyRL`

### Repo Pulse
- Route ID: `github:/pulse/:user/:repo/:period?`
- Route Path: `/pulse/:user/:repo/:period?`
- File: `docs/routes/github/pulse-user-repo-period.md`
- File Name: `pulse-user-repo-period.md`
- Categories: `programming`
- Maintainers: `jameschensmith`

### Repository Event
- Route ID: `github:/repo_event/:owner/:repo/:types?`
- Route Path: `/repo_event/:owner/:repo/:types?`
- File: `docs/routes/github/repo_event-owner-repo-types.md`
- File Name: `repo_event-owner-repo-types.md`
- Categories: `programming`
- Maintainers: `mslxl`

### User Repo
- Route ID: `github:/repos/:user/:type?/:sort?`
- Route Path: `/repos/:user/:type?/:sort?`
- File: `docs/routes/github/repos-user-type-sort.md`
- File Name: `repos-user-type-sort.md`
- Categories: `programming`
- Maintainers: `DIYgod`

### Search Result
- Route ID: `github:/search/:query/:sort?/:order?`
- Route Path: `/search/:query/:sort?/:order?`
- File: `docs/routes/github/search-query-sort-order.md`
- File Name: `search-query-sort-order.md`
- Categories: `programming`
- Maintainers: `LogicJake`

### User Starred Repositories
- Route ID: `github:/starred_repos/:user`
- Route Path: `/starred_repos/:user`
- File: `docs/routes/github/starred_repos-user.md`
- File Name: `starred_repos-user.md`
- Categories: `programming`
- Maintainers: `LanceZhu`

### Repo Stars
- Route ID: `github:/stars/:user/:repo`
- Route Path: `/stars/:user/:repo`
- File: `docs/routes/github/stars-user-repo.md`
- File Name: `stars-user-repo.md`
- Categories: `programming`
- Maintainers: `HenryQW`

### Topics
- Route ID: `github:/topics/:name/:qs?`
- Route Path: `/topics/:name/:qs?`
- File: `docs/routes/github/topics-name-qs.md`
- File Name: `topics-name-qs.md`
- Categories: `programming`
- Maintainers: `queensferryme`

### Trending
- Route ID: `github:/trending/:since/:language/:spoken_language?`
- Route Path: `/trending/:since/:language/:spoken_language?`
- File: `docs/routes/github/trending-since-language-spoken_language.md`
- File Name: `trending-since-language-spoken_language.md`
- Categories: `programming`
- Maintainers: `DIYgod, jameschensmith`

### User Followers
- Route ID: `github:/user/followers/:user`
- Route Path: `/user/followers/:user`
- File: `docs/routes/github/user-followers-user.md`
- File Name: `user-followers-user.md`
- Categories: `programming`
- Maintainers: `HenryQW`

### User Event
- Route ID: `github:/user_event/:username/:types?`
- Route Path: `/user_event/:username/:types?`
- File: `docs/routes/github/user_event-username-types.md`
- File Name: `user_event-username-types.md`
- Categories: `programming`
- Maintainers: `mslxl`

### Wiki History
- Route ID: `github:/wiki/:user/:repo/:page?`
- Route Path: `/wiki/:user/:repo/:page?`
- File: `docs/routes/github/wiki-user-repo-page.md`
- File Name: `wiki-user-repo-page.md`
- Categories: `programming`
- Maintainers: `TonyRL`
