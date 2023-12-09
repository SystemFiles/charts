# bootstrap

![Version: 0.1.1](https://img.shields.io/badge/Version-0.1.1-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 1.16.0](https://img.shields.io/badge/AppVersion-1.16.0-informational?style=flat-square)

A helm chart for bootstrapping an RKE2 cluster platform

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| application | object | `{}` |  |
| core.metallb.config.addressPools | list | `[]` |  |
| core.metallb.namespace.labels."pod-security.kubernetes.io/audit" | string | `"privileged"` |  |
| core.metallb.namespace.labels."pod-security.kubernetes.io/enforce" | string | `"privileged"` |  |
| core.metallb.namespace.labels."pod-security.kubernetes.io/warn" | string | `"privileged"` |  |
| core.metallb.namespace.name | string | `"metallb-system"` |  |
| core.metallb.namespace.purpose | string | `"system"` |  |

