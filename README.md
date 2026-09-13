# ParanormalCo. public pages

Official public support, privacy, advertising authorization, and launch configuration files for ParanormalCo.

- `privacy.html`: App Store privacy-policy URL
- `support.html`: App Store support URL
- `monetization-config.json`: legacy launch-safe overrides; rewarded ads remain disabled for older builds
- `monetization-config-1.2.1.json`: repaired-build overrides with production rewarded inventory enabled
- `app-ads.txt`: added once the final AdMob publisher ID is available

Each app release uses an explicit configuration path so a repaired build can be enabled without re-enabling ads in older binaries. The app also enforces non-remote safety ceilings locally.
