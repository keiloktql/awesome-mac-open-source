# Contributing

Thanks for helping! The README is generated, so please **edit only [`data/apps.json`](data/apps.json)**.

## Adding an app

Add one object to `data/apps.json`:

```json
{
  "name": "AppName",
  "repo": "owner/repo",
  "category": "menubar",
  "description": "What it does, in one line"
}
```

- `repo` is the GitHub `owner/repo` of the app's source code.
- `category` is one of the slugs below.
- `description` is optional: without it, the GitHub description is used. No trailing period, no marketing ("best", "ultimate").

The app must be **open source**, a **native or desktop app that runs on macOS**, and **maintained** (a commit in the last 24 months). Apps that stop being maintained move to the Unmaintained section automatically.

One app per pull request, please. Stars, last commit and Homebrew casks are filled in by the weekly refresh: don't add them by hand.

## Categories

| Slug | Section |
| --- | --- |
| `ai` | AI & LLM |
| `audio` | Audio & Music |
| `backup` | Backup & Sync |
| `browsers` | Browsers |
| `communication` | Chat & Communication |
| `editors` | Code & Text Editors |
| `databases` | Databases |
| `design` | Design & Graphics |
| `developer` | Developer Tools |
| `downloads` | Downloaders |
| `email` | Email |
| `files` | Files & Finder |
| `finance` | Finance & Crypto |
| `games` | Games & Emulators |
| `git` | Git |
| `images` | Images & Screenshots |
| `keyboard` | Keyboard & Input |
| `writing` | Markdown & Writing |
| `menubar` | Menu Bar |
| `network` | Network, VPN & Proxy |
| `notes` | Notes & Knowledge |
| `productivity` | Productivity |
| `reading` | Reading, News & RSS |
| `security` | Security & Privacy |
| `system` | System & Monitoring |
| `terminal` | Terminal |
| `utilities` | Utilities |
| `video` | Video & Screen Recording |
| `virtualization` | Virtualization |
| `wallpapers` | Wallpapers & Screensavers |
| `windows` | Window Management |
