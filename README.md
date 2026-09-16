# Parapet releases

Signed Safari content-blocker rule releases served to the Parapet app over GitHub Pages.

`v1/manifest.json` names the current release; its Ed25519 signature is in `manifest.sig`. The app verifies the signature and every file hash before installing anything, so these files carry no trust of their own.
