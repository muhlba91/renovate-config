# gitStream Configuration

[![Build status](https://img.shields.io/github/actions/workflow/status/muhlba91/renovate-config/pipeline.yml?style=for-the-badge)](https://github.com/muhlba91/renovate-config/actions/workflows/pipeline.yml)
[![License](https://img.shields.io/github/license/muhlba91/renovate-config?style=for-the-badge)](LICENSE.md)
[![](https://api.scorecard.dev/projects/github.com/muhlba91/renovate-config/badge?style=for-the-badge)](https://scorecard.dev/viewer/?uri=github.com/muhlba91/renovate-config)

This repository contains the global configuration for [Renovate](https://renovatebot.com).

---

## Configuration

Each `*.json` file represents a named preset for Renovate.

### List of Configurations

- [`default.json`](default.json)
  - applies defaults
  - applies automerge defaults for patch, digest, and pin updates
- [`automerge.json`](automerge.json)
  - automerges PRs based on their update type
