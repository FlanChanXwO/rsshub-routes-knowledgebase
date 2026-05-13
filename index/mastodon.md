# Mastodon Route Index

## Namespace
- Namespace: `mastodon`
- Display Name: `Mastodon`
- URL: `mastodon.social`
- Language: `en`
- Aliases: `mastodon, mastodon.social`
- Route Count: `5`

## Routes

### User timeline (by account ID)
- Route ID: `mastodon:/account_id/:site/:account_id/statuses/:only_media?`
- Route Path: `/account_id/:site/:account_id/statuses/:only_media?`
- File: `docs/routes/mastodon/account_id-site-account_id-statuses-only_media.md`
- File Name: `account_id-site-account_id-statuses-only_media.md`
- Categories: `social-media`
- Maintainers: `notofoe, pseudoyu`

### User timeline
- Route ID: `mastodon:/acct/:acct/statuses/:only_media?`
- Route Path: `/acct/:acct/statuses/:only_media?`
- File: `docs/routes/mastodon/acct-acct-statuses-only_media.md`
- File Name: `acct-acct-statuses-only_media.md`
- Categories: `social-media`
- Maintainers: `notofoe`

### Instance timeline (federated)
- Route ID: `mastodon:/remote/:site/:only_media?`
- Route Path: `/remote/:site/:only_media?`
- File: `docs/routes/mastodon/remote-site-only_media.md`
- File Name: `remote-site-only_media.md`
- Categories: `social-media`
- Maintainers: `hoilc`

### Hashtag timeline
- Route ID: `mastodon:/tag/:site/:hashtag/:only_media?`
- Route Path: `/tag/:site/:hashtag/:only_media?`
- File: `docs/routes/mastodon/tag-site-hashtag-only_media.md`
- File Name: `tag-site-hashtag-only_media.md`
- Categories: `social-media`
- Maintainers: `yuikisaito`

### Instance timeline (local)
- Route ID: `mastodon:/timeline/:site/:only_media?`
- Route Path: `/timeline/:site/:only_media?`
- File: `docs/routes/mastodon/timeline-site-only_media.md`
- File Name: `timeline-site-only_media.md`
- Categories: `social-media`
- Maintainers: `hoilc`
