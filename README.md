# Ship Studio — Umbrel Community App Store

Community app store for [Umbrel](https://umbrel.com). Contains app manifests
only; no application source.

## Add it to your Umbrel

App Store → ⋯ (top right) → **Community App Stores** → paste:

```
https://github.com/icraigshaw/neotes-app-store
```

## Apps

### Neotes

Writing, content management and publishing. Sheets in a library tree, internal
links that stay intact through publishing, bulk publish and find-and-replace
with a one-click undo, and media sourced from an [Eagle](https://eagle.cool)
library.

Image: `ghcr.io/icraigshaw/neotes`, pinned by digest.

## Notes

This repository is public because umbrelOS clones community app stores
anonymously — the Add dialog accepts a URL and no credentials. It holds nothing
but the manifests; the application source is private.

Manifests are generated from the `deploy/umbrel-app-store/` directory of the
Neotes repository, which remains the source of truth. Edit them there.
