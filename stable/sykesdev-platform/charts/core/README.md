# core

![Version: 0.1.0](https://img.shields.io/badge/Version-0.1.0-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 1.16.0](https://img.shields.io/badge/AppVersion-1.16.0-informational?style=flat-square)

A Helm chart for deployment of my opinionated core platform components

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| metallb.config.addressPools | list | `[]` |  |
| metallb.namespace.labels."pod-security.kubernetes.io/audit" | string | `"privileged"` |  |
| metallb.namespace.labels."pod-security.kubernetes.io/enforce" | string | `"privileged"` |  |
| metallb.namespace.labels."pod-security.kubernetes.io/warn" | string | `"privileged"` |  |
| metallb.namespace.name | string | `"metallb-system"` |  |
| metallb.namespace.purpose | string | `"system"` |  |

