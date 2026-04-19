# Apache Airflow (airflow)
Apache Airflow is an open-source platform to programmatically author, schedule, and monitor workflows. Airflow uses directed acyclic graphs (DAGs) to manage workflow orchestration. The Airflow REST API provides programmatic access to DAGs, DAG runs, tasks, connections, variables, pools, and monitoring for both Airflow OSS and cloud-managed deployments.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/airflow/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Workflow Orchestration, Data Pipeline, Open Source, Apache, DAG, Scheduling, ETL, Data Engineering

## Timestamps

- **Created:** 2026-01-02
- **Modified:** 2026-04-19

## APIs

### Apache Airflow API
The Apache Airflow REST API (v2) provides stable, backward-compatible endpoints for managing workflows (DAGs), DAG runs, task instances, connections, variables, XComs, pools, and plugins. Available at /api/v2 on any Airflow deployment.

**Human URL:** [https://airflow.apache.org/docs/apache-airflow/stable/stable-rest-api-ref.html](https://airflow.apache.org/docs/apache-airflow/stable/stable-rest-api-ref.html)

#### Tags:

 - Workflow Orchestration, DAG, Scheduling, Data Pipeline, Open Source

#### Properties

- [Documentation](https://airflow.apache.org/docs/apache-airflow/stable/stable-rest-api-ref.html)
- [APIReference](https://airflow.apache.org/docs/apache-airflow/stable/stable-rest-api-ref.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/airflow/refs/heads/main/openapi/airflow-openapi.yml)
- [Authentication](https://airflow.apache.org/docs/apache-airflow/stable/security/api.html)
- [PyPI Package](https://pypi.org/project/apache-airflow/)
- [Python Client SDK](https://pypi.org/project/apache-airflow-client/)
- [GitHub Repository](https://github.com/apache/airflow)

## Common Properties

- [Portal](https://airflow.apache.org)
- [GettingStarted](https://airflow.apache.org/docs/)
- [GitHubOrganization](https://github.com/apache/airflow)
- [GitHubRepository](https://github.com/apache/airflow)
- [Blog](https://airflow.apache.org/blog/)
- [StackOverflow](https://stackoverflow.com/questions/tagged/airflow)
- [ChangeLog](https://airflow.apache.org/docs/apache-airflow/stable/release_notes.html)
- [Docker Image](https://hub.docker.com/r/apache/airflow)
- [Helm Chart](https://artifacthub.io/packages/helm/airflow-helm/airflow)
- [SpectralRules](https://raw.githubusercontent.com/api-evangelist/airflow/refs/heads/main/rules/airflow-spectral-rules.yml)
- [NaftikoCapability - Workflow Orchestration](https://raw.githubusercontent.com/api-evangelist/airflow/refs/heads/main/capabilities/workflow-orchestration.yaml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/airflow/refs/heads/main/vocabulary/airflow-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| DAG Authoring | Define workflows as Python code using Directed Acyclic Graphs (DAGs). |
| Dynamic DAG Generation | Programmatically generate DAGs and tasks based on configuration or data. |
| Rich Operator Library | Pre-built operators for databases, cloud services, APIs, and data tools. |
| REST API v2 | Stable REST API for programmatic management of DAGs, runs, tasks, and infrastructure. |
| Web UI | Built-in web interface for monitoring, triggering, and debugging workflows. |
| Scheduler | Robust scheduler with support for CRON and timed triggers. |
| Extensible | Plugin system and provider packages for extending functionality. |
| Multi-Cloud Support | Provider packages for AWS, GCP, Azure, and other cloud platforms. |
| Managed Services | Available as managed service from AWS (MWAA), GCP (Cloud Composer), and Astronomer. |

## Use Cases

| Name | Description |
|------|-------------|
| ETL Pipeline Orchestration | Schedule and monitor extract, transform, load data pipelines. |
| ML Pipeline Management | Orchestrate machine learning training, evaluation, and deployment workflows. |
| Data Quality Checks | Schedule data validation and quality check jobs. |
| Report Generation | Automate periodic report generation and distribution. |
| API Orchestration | Coordinate calls to multiple APIs in complex workflows. |
| Database Operations | Schedule database maintenance, migrations, and backup jobs. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Spark | Run Spark jobs from Airflow DAGs. |
| dbt | Orchestrate dbt model runs via the dbt operator. |
| Kubernetes | Run tasks in Kubernetes pods with the KubernetesPodOperator. |
| AWS | Provider package for S3, Redshift, EMR, Lambda, and other AWS services. |
| Google Cloud | Provider package for BigQuery, Dataflow, GCS, and other GCP services. |
| Azure | Provider package for Azure Data Factory, Blob Storage, and other Azure services. |
| Snowflake | SnowflakeOperator for running SQL in Snowflake data warehouse. |
| Airbyte | Trigger Airbyte syncs from Airflow DAGs. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache Airflow OpenAPI](openapi/airflow-openapi.yml)

### JSON Schema

138 schema files covering all Airflow API resources including DAGResponse, DAGRunResponse, TaskInstanceResponse, ConnectionResponse, VariableResponse, and more.

### JSON Structure

138 JSON Structure (json-structure.org) files converted from JSON Schema.

### JSON-LD

- [Airflow Context](json-ld/airflow-context.jsonld)

### Examples

138 example JSON files generated from JSON Schema definitions.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Apache Airflow API](capabilities/shared/airflow-api.yaml) — 9 operations for workflow orchestration

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Workflow Orchestration](capabilities/workflow-orchestration.yaml) | Apache Airflow API | 10 | Data Engineer, Platform Admin |

## Vocabulary

- [Airflow Vocabulary](vocabulary/airflow-vocabulary.yaml) — Unified taxonomy mapping 9 resources, 7 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Airflow Spectral Rules](rules/airflow-spectral-rules.yml) — 22 rules across 9 categories enforcing Apache Airflow API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
