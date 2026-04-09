---
name: Active Projects
description: Vijay's current work projects at Lockton with blockers and status
type: project
---

## 1. Azure APIM / MuleSoft Connectivity — Active Escalation
VNet-integrated APIM instance can't complete TCP handshakes to MuleSoft CloudHub (10.5.0.0/22).
- Open ticket with firewall/network team
- **Why:** VNet integration restricts outbound routes; firewall rules likely blocking CloudHub CIDR
- **How to apply:** Track resolution; flag any firewall rule update mentions in email

## 2. Databricks Serverless Migration
Migrating workloads from classic compute to serverless.
- **Blocker:** Maven dependencies (Spark Excel connector) incompatible with serverless
- Evaluating: preprocessing layer, init scripts, alternative libs
- **How to apply:** Suggest serverless-compatible alternatives when discussing Databricks work

## 3. D&B DUNS Pipeline
Runs on Databricks / Unity Catalog. Involves D&B API batch jobs, S3 uploads with AES256 encryption, stage tracking tables.
- Status: Ongoing maintenance and monitoring
- **How to apply:** Treat as production-critical; flag errors or anomalies immediately

## 4. Power BI → Databricks Integration
Architecture: Power BI → Databricks App (FastAPI proxy) → Jobs API
- pbiviz-ready package built; currently in validation/deployment phase
- **How to apply:** Focus on deployment blockers and validation issues
