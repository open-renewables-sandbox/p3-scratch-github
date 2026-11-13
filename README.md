# P3 scratch library

Synthetic library for the P3 site and release rehearsals.

This is an OKF v0.2 knowledge library built from the OKF library template. It runs on GitHub: pull requests are validated by CI and revision history is written after each merge.

## Working on the library

```bash
uv sync --all-groups
uv run poe check
uv run poe test
```

Create a concept with `uv run python scripts/new_concept.py <Type> <path>`.

## Licences

| Path | Licence |
| --- | --- |
| `knowledge/` | CC-BY-4.0: see `LICENSE-content` |
| Code and changes by the owner | Apache-2.0: see `LICENSE` |
| Files inherited from the template | Apache-2.0: see `NOTICE` and, if the code licence differs, `LICENSE-template` |
