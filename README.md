# Uncanned support and legal pages

Public support and policy site for Uncanned, the iOS app for cutting down and quitting nicotine pouches and snus.

- [Website](https://unpouched.github.io/uncanned/)
- [Support](https://unpouched.github.io/uncanned/support/)
- [Privacy Policy](https://unpouched.github.io/uncanned/privacy/)
- [Terms of Use](https://unpouched.github.io/uncanned/terms/)
- [Sources](https://unpouched.github.io/uncanned/sources/)

## Publishing

GitHub Pages publishes the `main` branch from the repository root. Keep `baseurl: /uncanned` in `_config.yml`. Public pages have explicit permalinks; update internal links when changing a path.

The existing support email, `unpouchedapp@gmail.com`, is intentionally retained. App Store bundle IDs and purchase product IDs are technical identifiers and are separate from this site's branding.

The app repository keeps a copy of these pages in `docs/`. Update that copy whenever the published policies change. Existing alternate support URLs must continue to resolve for older app versions.

## Compatibility routes

- `unpouched/unpouched.github.io` preserves the old `/unpouched/` website paths used by published app versions.
- `sndr999/uncanned-site` forwards the alternate support URLs created during the rebrand.
- Both point to this site's `/uncanned/` pages. Keep the forwarding pages while installed app versions or App Store metadata still use them.

## Keeping the policy accurate

The current app opens Keepwell only after a Contact Support tap and uses its support-only mode. If that integration or another data flow changes, update the privacy page and the app's privacy disclosures together. Verify account deletion, support contact details, and all published page links before changing release metadata.
