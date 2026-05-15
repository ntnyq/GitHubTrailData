# GitHubTrail Data

This repository stores browsing history data synced by [GitHubTrail](https://github.com/ntnyq/GitHubTrail).

> [!NOTE]
> This data is managed automatically by the GitHubTrail browser extension.
> Manual edits may be overwritten during the next sync.

## What is GitHubTrail?

GitHubTrail is a browser extension that tracks your GitHub browsing history, helps you take research notes, and builds your open-source knowledge base.

**Features:**

- Automatic visit recording with configurable rules
- Rich metadata: visit type, duration, tags, notes, read status
- Full-text search across your browsing history
- GitHub sync with conflict resolution
- Analytics dashboard with trends and insights

## Repository Structure

```
.github-trail/
├── index.json          # Sync index and metadata
├── records/            # Visit records grouped by time period
│   ├── YYYY-MM.json    # Monthly (default) or YYYY-Www.json (weekly)
│   └── ...
├── stats/              # Pre-computed yearly statistics
│   ├── YYYY.json
│   └── ...
├── archive/            # Archived old records
│   └── ...
└── README.md           # This file
```

## Install

Get GitHubTrail for your browser:

- [Chrome Web Store](https://chromewebstore.google.com/)
- [Firefox Add-ons](https://addons.mozilla.org/)

## Links

- [Source Code](https://github.com/ntnyq/GitHubTrail)
- [Report Issues](https://github.com/ntnyq/GitHubTrail/issues)
