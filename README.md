# Amazon EMR (amazon-emr)
Amazon EMR is a cloud big data platform for running large-scale distributed data processing jobs, interactive SQL queries, and machine learning applications using open-source analytics frameworks such as Apache Spark, Apache Hive, Apache HBase, Apache Flink, Apache Hudi, and Presto.

**URL:** [https://aws.amazon.com/emr/](https://aws.amazon.com/emr/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Amazon Web Services, Analytics, Apache Spark, AWS, Big Data, Data Processing, Hadoop

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Amazon EMR API
API for creating and managing Amazon EMR clusters, steps, instance groups, and running distributed big data processing workloads.

**Human URL:** [https://aws.amazon.com/emr/](https://aws.amazon.com/emr/)

#### Tags:

 - Analytics, Big Data, Data Processing, Spark

#### Properties

- [Documentation](https://docs.aws.amazon.com/emr/latest/ManagementGuide/)
- [OpenAPI](openapi/amazon-emr-openapi.yml)
- [APIReference](https://docs.aws.amazon.com/emr/latest/APIReference/)
- [GettingStarted](https://aws.amazon.com/emr/getting-started/)
- [Pricing](https://aws.amazon.com/emr/pricing/)
- [FAQ](https://aws.amazon.com/emr/faqs/)
- [JSONSchema](json-schema/amazon-emr-schema.json)
- [JSONLD](json-ld/amazon-emr-context.jsonld)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [DeveloperPortal](https://aws.amazon.com/emr/)
- [Documentation](https://docs.aws.amazon.com/emr/)
- [Blog](https://aws.amazon.com/blogs/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/emr/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [Login](https://signin.aws.amazon.com/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Support](https://aws.amazon.com/support/)
- [FAQ](https://aws.amazon.com/emr/faqs/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Compliance](https://aws.amazon.com/compliance/)
- [Security](https://aws.amazon.com/security/)
- [YouTube](https://www.youtube.com/user/AmazonWebServices)
- [StackOverflow](https://stackoverflow.com/questions/tagged/emr)
- [KnowledgeCenter](https://repost.aws/knowledge-center)
- [Contact](https://aws.amazon.com/contact-us/)

## Features

| Name | Description |
|------|-------------|
| Apache Spark Support | Run Apache Spark jobs for large-scale data processing and machine learning |
| Auto Scaling | Automatically adjust cluster size based on workload demand |
| Spot Instance Integration | Use EC2 Spot instances to reduce costs up to 90% |
| EMR Serverless | Run analytics without provisioning or managing clusters |
| Studio Notebooks | Develop and debug jobs using EMR Studio Jupyter notebooks |

## Use Cases

| Name | Description |
|------|-------------|
| ETL Data Processing | Extract, transform, and load large datasets across data lakes and warehouses |
| Machine Learning | Train machine learning models on large datasets using Spark MLlib |
| Log Analytics | Process and analyze application logs at petabyte scale |
| Financial Risk Analysis | Run Monte Carlo simulations and risk models on large datasets |

## Integrations

| Name | Description |
|------|-------------|
| Amazon S3 | Use S3 as data lake storage for EMR clusters |
| AWS Glue | Integrate with Glue Data Catalog for metadata management |
| Amazon Athena | Query data processed by EMR using Athena SQL |
| Amazon SageMaker | Hand off processed data to SageMaker for model training |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [amazon-emr](openapi/amazon-emr-openapi.yml)

### JSON Schema

- [amazon-emr](json-schema/amazon-emr-schema.json)

### JSON Structure

- [amazon-emr](json-structure/amazon-emr-structure.json)

### JSON-LD

- [amazon-emr](json-ld/amazon-emr-context.jsonld)

### Examples

- [amazon-emr](examples/amazon-emr-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [EMR](capabilities/shared/api.yaml) — 1 operations

### Workflow Capabilities

| Workflow | Tools | Persona |
|----------|-------|---------|
| [Amazon EMR Management](capabilities/amazon-emr-capability.yaml) | 1 | Cloud Architect |

## Vocabulary

- [Amazon EMR Vocabulary](vocabulary/amazon-emr-vocabulary.yaml) — Unified taxonomy mapping 1 resources, 1 actions, 1 workflows, and 2 personas

## Rules

- [amazon-emr-spectral-rules.yml](rules/amazon-emr-spectral-rules.yml) — 0 rules enforcing Amazon EMR API conventions

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
