# home-ops

## Git

- Commits use conventional commits (`type(scope): subject`); a lefthook commit-msg hook rejects anything else.
- Small, low-risk changes (a single app's values, a version bump, a typo, a one-line fix) go straight to `main`.
- Anything bigger goes through a PR: a new app, changes across several apps, or anything touching talos, flux, networking, storage or secrets. When unsure, open a PR.
- PR descriptions are a few plain sentences, as if explaining the change to a colleague: what changed and why. No headings, no bullet lists, no "Summary"/"Test plan" sections, no emoji.
