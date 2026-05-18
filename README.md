# Lootstash iOS — release mirror

Public mirror for SideStore distribution of Lootstash dev builds. Source of truth is `source.json`, updated automatically by CI in the private `md-bogush/lootstash` repo on every push to `master` that touches `apps/ios/**`.

## SideStore consumer URL

  ```
  https://raw.githubusercontent.com/md-bogush/lootstash-ios-release/main/source.json
  ```

Add this once per device in SideStore → Sources → +.

## What lives here

- `source.json` — SideStore feed (version, download URL, metadata). Overwritten by CI.
- `Lootstash.ipa` — attached as asset to the `dev-latest` release. Replaced on every build.

No source code. The app sources live in the private repo.
