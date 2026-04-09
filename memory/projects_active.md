---
name: Active Projects
description: Current work projects with blockers and status
type: project
---

## 1. API / Integration Connectivity — Active Escalation
Network-integrated API gateway can't complete TCP handshakes to downstream service.
- Open ticket with network/infrastructure team
- **Why:** Network integration restricts outbound routes; firewall rules likely blocking target CIDR
- **How to apply:** Track resolution; flag any firewall rule update mentions in email

## 2. Compute Migration
Migrating workloads from legacy compute to modern serverless infrastructure.
- **Blocker:** Dependency compatibility issues with serverless environment
- Evaluating: preprocessing layer, alternative libraries, init scripts
- **How to apply:** Suggest compatible alternatives when discussing migration work

## 3. Data Pipeline
Production data pipeline involving batch jobs, encrypted file transfers, and stage tracking tables.
- Status: Ongoing maintenance and monitoring
- **How to apply:** Treat as production-critical; flag errors or anomalies immediately

## 4. BI Tool → Data Platform Integration
Architecture: BI tool → proxy service → data platform jobs API
- Package built; currently in validation/deployment phase
- **How to apply:** Focus on deployment blockers and validation issues
