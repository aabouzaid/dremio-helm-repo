# Dremio Helm Repository

This repo provides a Helm repository based on Dremio Helm chart v2
in [dremio/dremio-cloud-tools](https://github.com/dremio/dremio-cloud-tools/tree/master/charts/dremio_v2) repo
because the upstream doesn't provide a Helm repo for their charts.

## Versioning
Versioning is based on the tags of [Dremio Docker image](https://hub.docker.com/r/dremio/dremio-oss/),
so for example, Dremio Helm chart `24.0.0` uses Docker Helm chart [24.0.0](https://hub.docker.com/layers/dremio/dremio-oss/24.0.0/images/sha256-73499a9c6b82c3eb9b1b9c36d03397f716ddbe21d526e049279ee7bb605729a5?context=explore).