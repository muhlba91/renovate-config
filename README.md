# gitStream Configuration

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
- [`group-go.json`](group-go.json)
  - bumps Go in `mise.toml` and `go.mod` together, including the `go` directive
  - not meant for Go libraries, whose `go` directive should only move when needed
- [`group-pulumi.json`](group-pulumi.json)
  - bumps the Pulumi CLI and the Pulumi core SDK (Go, Node.js, Python) together
