# earlye fork of ArtCraft

This repository is a fork of [storytold/artcraft](https://github.com/storytold/artcraft).
Rather than maintaining a diverging code history, the fork is maintained by
re-applying a set of change prompts on top of upstream; see the fork's NQAF
prompt history for the prompts themselves.

## Differences from upstream

- `feature-000` — adds this file and the fork notice in `README.md`.
- `feature-001` — the login modal no longer opens automatically at startup and can be
  dismissed; features that need an ArtCraft account still prompt for login.
- `feature-002` — adds the fork-local `earlye-build.yml` workflow, which builds unsigned
  macOS (arm64) and Windows artifacts on every push to a non-`main` branch, with Linux
  available on manual dispatch.
