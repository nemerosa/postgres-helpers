[`pg-db-backup-do-space`](values.yaml)
======================================

This chart is used to set up a job which saves the content of a Digital Ocean database
as SQL into a Digital Ocean space.

# Usage

```bash
helm install my-db-owner postgres-helpers/pg-db-backup-do-space --values values.yaml
```

> See [`values.yaml`](values.yaml) for the list of options.

# Change log

## 0.1.0

* Initial version
