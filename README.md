# Mandarin Helper update info

The Mandarin Helper app reads `version.json` from GitHub Pages to tell players when a new version is on Google Play.

- `latest_code` / `latest_version`: newest release (raise only once the Play rollout is at 100%)
- `min_code`: versions below this must update (card can't be closed); 0 = never force
- `message` / `message_zh`: optional one-line teaser shown with the banner
