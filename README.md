# Beacon Vendor Mirror

Vendored snapshots of the third-party projects that ship with the Beacon line.
Each component subtree mirrors the upstream project at the commit pinned for the
current release gate; the `LICENSE` file in each subtree is the upstream file
committed verbatim.

## Components

| component key | project | subtree |
| --- | --- | --- |
| tidecore | TideCore Runtime | `components/tidecore/` |
| shardline | Shardline Query Adapter | `components/shardline/` |
| boruvka | Boruvka Graph Kit | `components/boruvka/` |
| fernwright | Fernwright Crypto Library | `components/fernwright/` |
| mirepoix | Mirepoix Metrics Client | `components/mirepoix/` |
| quillon | Quillon Event Codec | `components/quillon/` |

## Layout

```
components/<component_key>/README.md
components/<component_key>/LICENSE
```

Third-party notice material, where an upstream project publishes one, lives
next to the component under `LICENSE-NOTICE.md`.
