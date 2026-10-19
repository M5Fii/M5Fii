# SURG 514 Practice Lab setup

This repository is connected to Vercel project `surg-514-practice-lab` in team `zer0-5f1c`. Production uses `main`.

The existing app source has not yet been imported into this repository. Add the complete source before deploying from Git.

The `ignoreCommand` in `vercel.json` skips commits whose subject contains `[skip vercel]`. Initialization commits use this marker to preserve the existing production deployment. Normal commits without the marker build normally.

GitHub browser commits work. The ChatGPT/Codex GitHub connector returned `403: Resource not accessible by integration` on a write; browser sign-in does not change that connector permission.
