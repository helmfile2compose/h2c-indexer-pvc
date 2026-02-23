# h2c-indexer-pvc

PVC indexer for [helmfile2compose](https://github.com/helmfile2compose/helmfile2compose) — pre-registers PersistentVolumeClaim references so volume conversion can resolve host paths on first run.

**The Binder** — one of the Seven Bishops, the founding extensions of the helmfile2compose distribution.

## Type

`IndexerConverter` (priority 50)

## Kinds

- `PersistentVolumeClaim`

## Note

This is a **build-time only** extension, designed to be concatenated by `build-distribution.py` into a single-file distribution. It uses internal core imports that are resolved at build time. It is **not** designed for runtime loading via `--extensions-dir`.

## Install

Listed in `distribution.json` — installed automatically when building a distribution via `h2c-manager`.
