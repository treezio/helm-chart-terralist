# Terralist Helm Chart
## Description

This repository contains helm chart to deploy [Terralist](https://terralist.io)

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![Release Charts](https://github.com/treezio/helm-chart-terralist/actions/workflows/chart-releaser.yaml/badge.svg?branch=main)](https://github.com/treezio/helm-chart-terralist/actions/workflows/chart-releaser.yaml)

## Requirements

- [Helm](https://helm.sh)

## Usage

```console
helm repo add terralist https://treezio.github.io/helm-chart-terralist
```

You list the charts running `helm search repo terralist/terralist`.

## Install Chart

```console
helm install [RELEASE_NAME] terralist/terralist
```

## Uninstall Chart

```console
helm uninstall [RELEASE_NAME]
```

## Configuring

Check [values.yaml](./charts/terralist/values.yaml) file or run:

```console
helm show values terralist/terralist
```


