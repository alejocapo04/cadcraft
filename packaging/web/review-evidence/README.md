# Native optional file-provider evidence

Source: `e0f565c8009abb91fce7fd757a1a71318989fd7f`. Workflow: `132ee236c6b0e5b6e3dc4f570cfbf96bcfee4a33`.

The local and external entries are synthetic fixtures. These captures validate the native UI separation, not real storage operations.

Rendered with the repository native offscreen renderer and pinned fonts. This is not browser/backend end-to-end evidence. No server, credentials or private files were used.

Run: https://github.com/alejocapo04/cadcraft/actions/runs/41281019745

- `local.png`: provider absent (default).
- `provider.png`: synthetic provider registered; device history remains separate.

The evidence lives on this review-only branch and is excluded from the feature PR. See provenance.json for input and image hashes.
