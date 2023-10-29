Utilities for Postgres in Terraform & Helm
==========================================

# Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```
helm repo add postgres-helpers https://nemerosa.github.io/postgres-helpers
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
ontrack` to see the charts.

# Charts

* [`pg-db-owner`](charts/pg-db-owner/README.md) - setting up the owner of a Postgres database inside a cluster
* [`pg-db-backup-do-space`](charts/pg-db-backup-do-space/README.md) - job to backup a Digital Ocean (DO) Postgres database into a DO Space
