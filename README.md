# Hi, I'm Nico

Based in Berlin. I started as a backend developer, moved into ops and infrastructure - mostly Kubernetes - and now I spend most of my time combining both by writing the infrastructure itself. I like fixing things in projects I use.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nico-duldhardt/)
[![X](https://img.shields.io/badge/X-000000?style=flat&logo=x&logoColor=white)](https://x.com/klaudworks)

---

## Open Source Contributions

### S3 & Object Storage

<table>
<tr>
<td valign="top" width="50%">

**[gaul/s3proxy](https://github.com/gaul/s3proxy)**
Access other storage backends via the S3 API

</td>
<td valign="top" width="50%">

**[KafScale/platform](https://github.com/KafScale/platform)**
Kafka-compatible data streaming on S3

</td>
</tr>
</table>

<details><summary>9 PRs, 11 issues</summary>

#### gaul/s3proxy

PRs:
- [Implement multipart upload for azureblob-sdk provider](https://github.com/gaul/s3proxy/pull/904)
- [Implement atomic conditional puts for azureblob-sdk](https://github.com/gaul/s3proxy/pull/902)
- [Add If-Match and If-None-Match support for PutObject operations](https://github.com/gaul/s3proxy/pull/893)
- [Add OpenTelemetry Prometheus metrics with configurable port/host](https://github.com/gaul/s3proxy/pull/946)
- [Fix server-side copy with Managed Identity in AzureBlobStore](https://github.com/gaul/s3proxy/pull/944)
- [Fix azureblob multipart upload regression](https://github.com/gaul/s3proxy/pull/930)
- [Update tests for multipart upload azureblob-sdk](https://github.com/gaul/s3-tests/pull/4) *(s3-tests)*
- [Skip delimiter prefix tests on s3proxy localstack](https://github.com/gaul/s3-tests/pull/5) *(s3-tests)*
- [Enable ifmatch and ifnonematch tests](https://github.com/gaul/s3-tests/pull/3) *(s3-tests)*

Issues:
- [Feature: Metrics for S3 operations](https://github.com/gaul/s3proxy/issues/945)
- [ListObjectsV2 start-after fails on azureblob-sdk backend](https://github.com/gaul/s3proxy/issues/938)
- [azureblob-sdk provider does not work with aws-sdk-java-v2 < 2.35](https://github.com/gaul/s3proxy/issues/906)
- [Release 2.8.0](https://github.com/gaul/s3proxy/issues/896)
- [Autoprocessor fails when using Java 24](https://github.com/gaul/s3proxy/issues/895)

#### KafScale/platform

PRs:
- [fix: arm64 images contain amd64 binaries due to hardcoded TARGETARCH default](https://github.com/KafScale/platform/pull/117)
- [fix: handle orphaned S3 segments gracefully in RestoreFromS3 and Read](https://github.com/KafScale/platform/pull/114)
- [perf: S3 concurrency semaphore and lock-free flush uploads](https://github.com/KafScale/platform/pull/111)
- [perf: parallelize S3 segment and index uploads](https://github.com/KafScale/platform/pull/110)
- [cleanup: remove minio defaults from broker, pass through operator env vars](https://github.com/KafScale/platform/pull/119)
- [fix: don't block all partitions while one is initializing](https://github.com/KafScale/platform/pull/118)

Issues:
- [bug: consumer groups with more than 1 consumer leads to GroupCoordinator split brain](https://github.com/KafScale/platform/issues/121)
- [bug: two brokers writing to the same partition can produce overlapping offsets](https://github.com/KafScale/platform/issues/120)
- [perf: reduce e2e produce + fetch latency on AWS to < 100ms](https://github.com/KafScale/platform/issues/115)
- [perf: parallelize S3 .index + .kfs downloads in processors](https://github.com/KafScale/platform/issues/113)
- [Handle orphaned and corrupt segments gracefully in RestoreFromS3](https://github.com/KafScale/platform/issues/112)
- [parallelize S3 uploads for .index and .kfs](https://github.com/KafScale/platform/issues/109)

</details>

<table>
<tr>
<td valign="top" width="50%">

**[giantswarm/etcd-backup-operator](https://github.com/giantswarm/etcd-backup-operator)**
Creates etcd backups and uploads them to AWS S3

</td>
<td valign="top" width="50%">
</td>
</tr>
</table>

<details><summary>1 PR</summary>

#### giantswarm/etcd-backup-operator

PRs:
- [add support for s3 compatible storages](https://github.com/giantswarm/etcd-backup-operator/pull/792)

</details>

---

### Kubernetes & Cloud Native

<table>
<tr>
<td valign="top" width="50%">

**[klaudworks/kubeconfig-operator](https://github.com/klaudworks/kubeconfig-operator)** *(creator)*
Generates restricted kubeconfigs for Kubernetes

</td>
<td valign="top" width="50%">

**[open-telemetry/opentelemetry-helm-charts](https://github.com/open-telemetry/opentelemetry-helm-charts)**
OpenTelemetry Helm Charts

</td>
</tr>
</table>

<details><summary>4 PRs, 1 issue</summary>

#### open-telemetry/opentelemetry-helm-charts

PRs:
- [Simplify dependency propagation](https://github.com/open-telemetry/opentelemetry-helm-charts/pull/367)
- [Fix resolution of dependent environment variable](https://github.com/open-telemetry/opentelemetry-helm-charts/pull/361)
- [Fix email service address](https://github.com/open-telemetry/opentelemetry-helm-charts/pull/369)

Issues:
- [Checkout service can't access email service](https://github.com/open-telemetry/opentelemetry-helm-charts/issues/363)

#### klaudworks/kubeconfig-operator

Issues:
- [single install.yaml](https://github.com/klaudworks/kubeconfig-operator/issues/1)

</details>

<table>
<tr>
<td valign="top" width="50%">

**[crossplane-contrib/provider-http](https://github.com/crossplane-contrib/provider-http)**
Crossplane Provider for HTTP requests as resources

</td>
<td valign="top" width="50%">

**[argoproj/argo-cd](https://github.com/argoproj/argo-cd)**
Declarative GitOps CD for Kubernetes

</td>
</tr>
</table>

<details><summary>2 PRs, 4 issues</summary>

#### crossplane-contrib/provider-http

PRs:
- [Add MissingFieldStrategy for KeyInjection](https://github.com/crossplane-contrib/provider-http/pull/83)
- [fix flaky test by guaranteeing execution order](https://github.com/crossplane-contrib/provider-http/pull/96)

Issues:
- [Creation of resource is not skipped if resource already exists](https://github.com/crossplane-contrib/provider-http/issues/85)
- [Replacing sensitive values doesn't work in certain cases](https://github.com/crossplane-contrib/provider-http/issues/84)

#### argoproj/argo-cd

Issues:
- [Faulty unrelated conversion webhook brings argocd to a halt](https://github.com/argoproj/argo-cd/issues/25305)
- [ServerSideDiff not detecting diff in manifests](https://github.com/argoproj/argo-cd/issues/23127)

</details>

<table>
<tr>
<td valign="top" width="50%">

**[awslabs/cdk-eks-blueprints](https://github.com/awslabs/cdk-eks-blueprints)**
AWS CDK EKS Blueprints

</td>
<td valign="top" width="50%">

**[cdk8s-team/cdk8s](https://github.com/cdk8s-team/cdk8s)**
Define Kubernetes apps using programming languages

</td>
</tr>
</table>

<details><summary>2 PRs</summary>

#### awslabs/cdk-eks-blueprints

PRs:
- [Add zone id filter using external args](https://github.com/awslabs/cdk-eks-blueprints/pull/818)

#### cdk8s-team/cdk8s

PRs:
- [chore(adopters): canida.io](https://github.com/cdk8s-team/cdk8s/pull/1484)

</details>

<table>
<tr>
<td valign="top" width="50%">

**[kubernetes-sigs/kubebuilder](https://github.com/kubernetes-sigs/kubebuilder)**
SDK for building Kubernetes APIs

</td>
<td valign="top" width="50%">

**[cloudnative-pg/plugin-barman-cloud](https://github.com/cloudnative-pg/plugin-barman-cloud)**
Barman Cloud plugin for CloudNativePG

</td>
</tr>
</table>

<details><summary>3 issues</summary>

#### kubernetes-sigs/kubebuilder

Issues:
- [Helm ServiceAccount scaffolding NIL pointers](https://github.com/kubernetes-sigs/kubebuilder/issues/4562)

#### cloudnative-pg/plugin-barman-cloud

Issues:
- [Backups are not restorable on low-activity databases due to missing final WAL segment](https://github.com/cloudnative-pg/plugin-barman-cloud/issues/652)
- [Restore breaks when increasing wal.maxParallel to 8](https://github.com/cloudnative-pg/plugin-barman-cloud/issues/516)

</details>

<table>
<tr>
<td valign="top" width="50%">

**[klaudworks/hasura-helm-chart](https://github.com/klaudworks/hasura-helm-chart)** *(creator)*
Helm chart to deploy Hasura with metadata and migrations from a git repo

</td>
<td valign="top" width="50%">

**[kutespaces/argocd](https://github.com/kutespaces/argocd)** *(creator)*
Preconfigured learning environment for GitOps with Kubernetes & Argo CD

</td>
</tr>
</table>

---

### AI & LLM Tooling

<table>
<tr>
<td valign="top" width="50%">

**[skills-directory/skill-codex](https://github.com/skills-directory/skill-codex)** *(creator)*
A Claude Code skill to delegate prompts to Codex

</td>
<td valign="top" width="50%">

**[klaudworks/universal-skills](https://github.com/klaudworks/universal-skills)** *(creator)*
Claude Code skills collection

</td>
</tr>
</table>

<table>
<tr>
<td valign="top" width="50%">

**[BerriAI/litellm](https://github.com/BerriAI/litellm)**
Python SDK & Proxy Server to call 100+ LLM APIs

</td>
<td valign="top" width="50%">

**[apache/flink-agents](https://github.com/apache/flink-agents)**
Agentic AI framework based on Apache Flink

</td>
</tr>
</table>

<details><summary>2 PRs, 3 issues</summary>

#### BerriAI/litellm

PRs:
- [fix: stop leaking x-litellm-api-key to Anthropic + support OAuth tokens in passthrough](https://github.com/BerriAI/litellm/pull/20432)

Issues:
- [LiteLLM Proxy to Transcription Model Fails](https://github.com/BerriAI/litellm/issues/10584)

#### apache/flink-agents

PRs:
- [[Bugfix] Use Thread Context ClassLoader for user class loading](https://github.com/apache/flink-agents/pull/514)

Issues:
- [ClassNotFoundException when loading user-defined resource classes from uploaded JARs](https://github.com/apache/flink-agents/issues/515)

</details>

<table>
<tr>
<td valign="top" width="50%">

**[hesreallyhim/awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code)**
Curated list of skills, hooks, and plugins for Claude Code

</td>
<td valign="top" width="50%">

**[travisvn/awesome-claude-skills](https://github.com/travisvn/awesome-claude-skills)**
Curated list of Claude Skills and resources

</td>
</tr>
</table>

<details><summary>1 issue</summary>

#### hesreallyhim/awesome-claude-code

Issues:
- [[Resource]: Codex integration via skill](https://github.com/hesreallyhim/awesome-claude-code/issues/271)

</details>

---

### Data & Stream Processing

<table>
<tr>
<td valign="top" width="50%">

**[dbs-leipzig/gradoop](https://github.com/dbs-leipzig/gradoop)**
Distributed graph analytics with Apache Flink

</td>
<td valign="top" width="50%">

**[lensesio/stream-reactor](https://github.com/lensesio/stream-reactor)**
Open source Kafka Connectors

</td>
</tr>
</table>

<details><summary>6 PRs, 5 issues</summary>

#### dbs-leipzig/gradoop

PRs:
- [[#551] csv graph collection import and export](https://github.com/dbs-leipzig/gradoop/pull/976)
- [[#966] Reduce createMetaData() bloating](https://github.com/dbs-leipzig/gradoop/pull/980)
- [[#973] remove semicolon from ascii gdl graph](https://github.com/dbs-leipzig/gradoop/pull/977)
- [[#876] added print for logical graph and graph collection](https://github.com/dbs-leipzig/gradoop/pull/913)
- [[#877] added support for property value null](https://github.com/dbs-leipzig/gradoop/pull/908)
- [[#881] Fix runtime error empty edge set](https://github.com/dbs-leipzig/gradoop/pull/898)

Issues:
- [Rename log4j-test.properties](https://github.com/dbs-leipzig/gradoop/issues/981)
- [Fix bloated test output](https://github.com/dbs-leipzig/gradoop/issues/978)
- [Improve DataSource getLogicalGraph()](https://github.com/dbs-leipzig/gradoop/issues/974)
- [ExclusionTest testReduceCollection() token recognition error](https://github.com/dbs-leipzig/gradoop/issues/973)
- [GraphCollectionsFactory.fromTransaction() null pointer exception](https://github.com/dbs-leipzig/gradoop/issues/922)

</details>

<table>
<tr>
<td valign="top" width="50%">

**[cloudtools/troposphere](https://github.com/cloudtools/troposphere)**
Python library to create AWS CloudFormation descriptions

</td>
<td valign="top" width="50%">
</td>
</tr>
</table>

<details><summary>1 PR</summary>

#### cloudtools/troposphere

PRs:
- [Support for OpenApiVersion in serverless.Api](https://github.com/cloudtools/troposphere/pull/1778)

</details>

---

### Developer Tools & Other

<table>
<tr>
<td valign="top" width="50%">

**[Beingpax/VoiceInk](https://github.com/Beingpax/VoiceInk)**
Voice-to-text app for macOS

</td>
<td valign="top" width="50%">

**[zereight/gitlab-mcp](https://github.com/zereight/gitlab-mcp)**
GitLab MCP server

</td>
</tr>
</table>

<details><summary>2 PRs, 2 issues</summary>

#### Beingpax/VoiceInk

PRs:
- [Fix OCR capturing VoiceInk status overlay instead of frontmost app window](https://github.com/Beingpax/VoiceInk/pull/429)

Issues:
- [Date and execution time flipped for history request](https://github.com/Beingpax/VoiceInk/issues/430)
- [Screen content not detected](https://github.com/Beingpax/VoiceInk/issues/424)

#### zereight/gitlab-mcp

PRs:
- [Pin zod-to-json-schema to 3.24.5](https://github.com/zereight/gitlab-mcp/pull/285)

</details>

<table>
<tr>
<td valign="top" width="50%">

**[hasura/graphql-engine](https://github.com/hasura/graphql-engine)**
Blazing fast, instant realtime GraphQL APIs

</td>
<td valign="top" width="50%">

**[fastapi/full-stack-fastapi-template](https://github.com/fastapi/full-stack-fastapi-template)**
Full stack FastAPI template

</td>
</tr>
</table>

<details><summary>2 issues</summary>

#### hasura/graphql-engine

Issues:
- [Remote Schema Permissions Default Value Null leads to Validation Error](https://github.com/hasura/graphql-engine/issues/7772)

#### fastapi/full-stack-fastapi-template

Issues:
- [FastApi, Uvicorn and Gunicorn are installed 2 times inside the docker image](https://github.com/fastapi/full-stack-fastapi-template/issues/280)

</details>

<table>
<tr>
<td valign="top" width="50%">

**[fastapiutils/fastapi-utils](https://github.com/fastapiutils/fastapi-utils)**
Reusable utilities for FastAPI

</td>
<td valign="top" width="50%">

**[heroku/12factor](https://github.com/heroku/12factor)**
The Twelve-Factor App methodology

</td>
</tr>
</table>

<details><summary>2 PRs</summary>

#### fastapiutils/fastapi-utils

PRs:
- [Enable SQLAlchemy Caching for GUID type](https://github.com/fastapiutils/fastapi-utils/pull/223)

#### heroku/12factor

PRs:
- [Update intro.md by changing phrase "scaling up" to "scaling out"](https://github.com/heroku/12factor/pull/287)

</details>

<table>
<tr>
<td valign="top" width="50%">

**[klaudworks/gptprep](https://github.com/klaudworks/gptprep)** *(creator)*
Filter & load your code into the clipboard for LLM context

</td>
<td valign="top" width="50%">

**[klaudworks/docker-compose-ansible](https://github.com/klaudworks/docker-compose-ansible)** *(creator)*
Docker Compose with Ansible image

</td>
</tr>
</table>
