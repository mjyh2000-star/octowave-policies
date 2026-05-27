# octowave Legal Documents

This repository hosts the static legal/policy pages for the Android app
**octowave: Sleep & Focus** (`com.eightsoundhealing.app`), published on
Google Play by **MagicJohn**.

## Pages

| Path | Purpose |
|---|---|
| `index.html` | Menu landing page |
| `privacy.html` | Privacy Policy (개인정보처리방침) |
| `terms.html` | Terms of Service (이용약관) |
| `account-deletion.html` | Account Deletion request page (Google Play data-safety requirement) |

## Why GitHub Pages?

These pages must remain accessible to Google Play's automated and manual
policy review at all times. Hosting them as static files on GitHub Pages
gives us a 99.9% SLA at zero cost, decoupled from the app's backend infra.

## URLs (after GitHub Pages activation)

```
https://[YOUR-GITHUB-USERNAME].github.io/octowave-policies/                       (menu)
https://[YOUR-GITHUB-USERNAME].github.io/octowave-policies/privacy.html
https://[YOUR-GITHUB-USERNAME].github.io/octowave-policies/terms.html
https://[YOUR-GITHUB-USERNAME].github.io/octowave-policies/account-deletion.html
```

Use the last two URLs in Play Console:
- **App content → Privacy Policy** → `privacy.html` URL
- **App content → Data safety → Account deletion link** → `account-deletion.html` URL

## How to update

1. Edit the HTML file directly on GitHub, or push a commit from a local clone.
2. GitHub Pages auto-rebuilds within ~1 minute.
3. If the change is material (e.g. new data type collected), re-submit to
   Google Play via *Policy → Privacy policy → Save* to trigger re-review.

## Contact

- Developer: MagicJohn
- Email: mjyh2000@gmail.com
- Google Play: <https://play.google.com/store/apps/details?id=com.eightsoundhealing.app>
