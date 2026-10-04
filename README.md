# Static Pages

Static pages (Terms of Service, Privacy Policy, and similar) hosted via
GitHub Pages, shared across my personal projects. Each project gets its own
subfolder.

## Live pages

### TikTok fact bot

* Official website page: https://rom4sky.github.io/tiktok-fact-bot/
* Terms of Service: https://rom4sky.github.io/tiktok-fact-bot/terms.html
* Privacy Policy: https://rom4sky.github.io/tiktok-fact-bot/privacy.html
* OAuth callback (TikTok Login Kit redirect URI): https://rom4sky.github.io/tiktok-fact-bot/callback.html — displays the authorization code from the URL so it can be copied into the local OAuth script during the one-time authorization step.

## Structure

```
rom4sky.github.io/
└── tiktok-fact-bot/
    ├── index.html      — landing page (official website URL for TikTok app)
    ├── terms.html       — Terms of Service (UA/EN)
    ├── privacy.html      — Privacy Policy (UA/EN)
    └── callback.html      — OAuth redirect URI, shows auth code for copy-paste
```

New projects get their own subfolder here rather than a new repository.

