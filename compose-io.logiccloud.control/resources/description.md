# logiccloud Control

logiccloud Control is an industrial edge control plane for managing devices, monitoring system health, and orchestrating workloads across distributed edge environments.

## Features

- **Device Management**: Onboard, monitor, and manage edge devices across multiple sites
- **Workload Orchestration**: Deploy and manage containerized applications to edge fleets
- **Real-time Monitoring**: Track device health, resource utilization, and connectivity status
- **Multi-Architecture Support**: Runs on ARM (v7), ARM64, and AMD64 platforms
- **Industrial Automation**: Purpose-built for OT/IT convergence in manufacturing and industrial environments

## Architecture Support

| Architecture | Supported |
|-------------|-----------|
| amd64       | Yes       |
| arm64       | Yes       |
| arm/v7      | Yes       |

## Quick Start

```yaml
services:
  logiccloud-control:
    image: logiccloud/logiccloud-control:4.14.11
    ports:
      - "8080:8080"
    environment:
      - TZ=UTC
```

## Documentation

For full documentation, visit [logiccloud.io](https://logiccloud.io).
