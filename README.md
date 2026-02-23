# h2c-indexer-pvc

PVC indexer for [helmfile2compose](https://github.com/helmfile2compose/helmfile2compose) — pre-registers PersistentVolumeClaim references so volume conversion can resolve host paths on first run.

**The Binder** — one of the Eight Monks, the founding extensions of the helmfile2compose distribution.

> Heresy level: 1/10 — barely strays from scripture. Inlines one helper the temple no longer needs.

## Type

`IndexerConverter` (priority 50)

## Kinds

- `PersistentVolumeClaim`

## Install

Via [h2c-manager](https://github.com/helmfile2compose/h2c-manager):

```sh
python3 h2c-manager.py pvc-indexer
```

Or listed in `distribution.json` — installed automatically when building a distribution.
