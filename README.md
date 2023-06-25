# Big Bang - Chainguard Edition

Big Bang is a declarative, continuous delivery tool for deploying DoD hardened and approved packages into a Kubernetes cluster. This project uses [Chainguard](https://www.chainguard.dev) images where available.

> _Forked from [Repo1](https://repo1.dso.mil/) by [DoD Platform One](http://p1.dso.mil/).  Please direct all code changes, issues and comments to [https://repo1.dso.mil/platform-one/big-bang/bigbang](https://repo1.dso.mil/platform-one/big-bang/bigbang)_

## Progress

Not all Iron Bank containers have a corresponding match in Chainguard (yet!). Services which have been migrated are:

- flux
- kyverno
- prometheus
- metrics server

Both Istio and Grafana need to be supported by CHainguard to enable a vanilla, Big Bang Core Services deployment without Iron Bank.