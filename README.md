# Hi, I'm Nico

Based in Berlin. I started as a backend developer, moved into cloud & kubernetes and now I like building the infrastructure that others build on. Most of my work happens in private gitlab repos and my github mainly reflects contributions to OSS projects.

---

## Open Source Contributions

### S3 & Object Storage

<table>
<tr>
<td valign="top" width="50%">

<b><a href="https://github.com/gaul/s3proxy">gaul/s3proxy</a></b><br>
Access other storage backends via the S3 API

</td>
<td valign="top" width="50%">

<b><a href="https://github.com/KafScale/platform">KafScale/platform</a></b><br>
Kafka-compatible data streaming on S3

</td>
</tr>
<tr>
<td valign="top">

<details>
<summary>9 PRs, 5 issues</summary>

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

</details>

</td>
<td valign="top">

<details>
<summary>6 PRs, 6 issues</summary>

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

</td>
</tr>
<tr>
<td valign="top">

<b><a href="https://github.com/giantswarm/etcd-backup-operator">giantswarm/etcd-backup-operator</a></b><br>
Creates etcd backups and uploads them to AWS S3

</td>
<td></td>
</tr>
<tr>
<td valign="top">

<details>
<summary>1 PR</summary>

PRs:
- [add support for s3 compatible storages](https://github.com/giantswarm/etcd-backup-operator/pull/792)

</details>

</td>
<td>

<details>
<summary>&nbsp;</summary>
</details>

</td>
</tr>
</table>

---

### Kubernetes & Cloud Native

<table>
<tr>
<td valign="top" width="50%">

<b><a href="https://github.com/klaudworks/kubeconfig-operator">klaudworks/kubeconfig-operator</a></b> <i>(creator)</i><br>
Generates restricted kubeconfigs for Kubernetes

</td>
<td valign="top" width="50%">

<b><a href="https://github.com/open-telemetry/opentelemetry-helm-charts">open-telemetry/opentelemetry-helm-charts</a></b><br>
OpenTelemetry Helm Charts

</td>
</tr>
<tr>
<td>

<details>
<summary>&nbsp;</summary>
</details>

</td>
<td valign="top">

<details>
<summary>3 PRs, 1 issue</summary>

PRs:
- [Simplify dependency propagation](https://github.com/open-telemetry/opentelemetry-helm-charts/pull/367)
- [Fix resolution of dependent environment variable](https://github.com/open-telemetry/opentelemetry-helm-charts/pull/361)
- [Fix email service address](https://github.com/open-telemetry/opentelemetry-helm-charts/pull/369)

Issues:
- [Checkout service can't access email service](https://github.com/open-telemetry/opentelemetry-helm-charts/issues/363)

</details>

</td>
</tr>
<tr>
<td valign="top">

<b><a href="https://github.com/argoproj/argo-cd">argoproj/argo-cd</a></b><br>
Declarative GitOps CD for Kubernetes

</td>
<td valign="top">

<b><a href="https://github.com/crossplane-contrib/provider-http">crossplane-contrib/provider-http</a></b><br>
Crossplane Provider for HTTP requests as resources

</td>
</tr>
<tr>
<td valign="top">

<details>
<summary>2 issues</summary>

Issues:
- [Faulty unrelated conversion webhook brings argocd to a halt](https://github.com/argoproj/argo-cd/issues/25305)
- [ServerSideDiff not detecting diff in manifests](https://github.com/argoproj/argo-cd/issues/23127)

</details>

</td>
<td valign="top">

<details>
<summary>2 PRs, 2 issues</summary>

PRs:
- [Add MissingFieldStrategy for KeyInjection](https://github.com/crossplane-contrib/provider-http/pull/83)
- [fix flaky test by guaranteeing execution order](https://github.com/crossplane-contrib/provider-http/pull/96)

Issues:
- [Creation of resource is not skipped if resource already exists](https://github.com/crossplane-contrib/provider-http/issues/85)
- [Replacing sensitive values doesn't work in certain cases](https://github.com/crossplane-contrib/provider-http/issues/84)

</details>

</td>
</tr>
<tr>
<td valign="top">

<b><a href="https://github.com/kubernetes-sigs/kubebuilder">kubernetes-sigs/kubebuilder</a></b><br>
SDK for building Kubernetes APIs

</td>
<td valign="top">

<b><a href="https://github.com/cloudnative-pg/plugin-barman-cloud">cloudnative-pg/plugin-barman-cloud</a></b><br>
Barman Cloud plugin for CloudNativePG

</td>
</tr>
<tr>
<td valign="top">

<details>
<summary>1 issue</summary>

Issues:
- [Helm ServiceAccount scaffolding NIL pointers](https://github.com/kubernetes-sigs/kubebuilder/issues/4562)

</details>

</td>
<td valign="top">

<details>
<summary>2 issues</summary>

Issues:
- [Backups are not restorable on low-activity databases due to missing final WAL segment](https://github.com/cloudnative-pg/plugin-barman-cloud/issues/652)
- [Restore breaks when increasing wal.maxParallel to 8](https://github.com/cloudnative-pg/plugin-barman-cloud/issues/516)

</details>

</td>
</tr>
<tr>
<td valign="top">

<b><a href="https://github.com/kutespaces/argocd">kutespaces/argocd</a></b> <i>(creator)</i><br>
Preconfigured learning environment for GitOps with Kubernetes & Argo CD

</td>
<td valign="top">

<b><a href="https://github.com/kutespaces/strimzi-kafka-operator">kutespaces/strimzi-kafka-operator</a></b> <i>(creator)</i><br>
Preconfigured Strimzi Kafka environment for Kubernetes

</td>
</tr>
<tr>
<td>

<details>
<summary>&nbsp;</summary>
</details>

</td>
<td>

<details>
<summary>&nbsp;</summary>
</details>

</td>
</tr>
</table>

---

### AWS

<table>
<tr>
<td valign="top" width="50%">

<b><a href="https://github.com/awslabs/cdk-eks-blueprints">awslabs/cdk-eks-blueprints</a></b><br>
AWS CDK EKS Blueprints

</td>
<td valign="top" width="50%">

<b><a href="https://github.com/cloudtools/troposphere">cloudtools/troposphere</a></b><br>
Python library to create AWS CloudFormation descriptions

</td>
</tr>
<tr>
<td valign="top">

<details>
<summary>1 PR</summary>

PRs:
- [Add zone id filter using external args](https://github.com/awslabs/cdk-eks-blueprints/pull/818)

</details>

</td>
<td valign="top">

<details>
<summary>1 PR</summary>

PRs:
- [Support for OpenApiVersion in serverless.Api](https://github.com/cloudtools/troposphere/pull/1778)

</details>

</td>
</tr>
<tr>
<td valign="top">

<b><a href="https://github.com/canida-software/k8s-on-aws">canida-software/k8s-on-aws</a></b> <i>(creator)</i><br>
Accompanies a series of blogposts about Kubernetes on AWS

</td>
<td valign="top">

<b><a href="https://github.com/canida-software/terraform-ecs-fargate-spot-quickstart">canida-software/terraform-ecs-fargate-spot-quickstart</a></b> <i>(creator)</i><br>
Quickstart to set up applications on AWS ECS with Fargate Spot using Terraform

</td>
</tr>
<tr>
<td>

<details>
<summary>&nbsp;</summary>
</details>

</td>
<td>

<details>
<summary>&nbsp;</summary>
</details>

</td>
</tr>
</table>

---

### AI & LLM Tooling

<table>
<tr>
<td valign="top" width="50%">

<b><a href="https://github.com/klaudworks/universal-skills">klaudworks/universal-skills</a></b> <i>(creator)</i><br>
Claude Code skills collection

</td>
<td valign="top" width="50%">

<b><a href="https://github.com/skills-directory/skill-codex">skills-directory/skill-codex</a></b> <i>(creator)</i><br>
A Claude Code skill to delegate prompts to Codex

</td>
</tr>
<tr>
<td>

<details>
<summary>&nbsp;</summary>
</details>

</td>
<td>

<details>
<summary>&nbsp;</summary>
</details>

</td>
</tr>
<tr>
<td valign="top">

<b><a href="https://github.com/BerriAI/litellm">BerriAI/litellm</a></b><br>
Python SDK & Proxy Server to call 100+ LLM APIs

</td>
<td valign="top">

<b><a href="https://github.com/apache/flink-agents">apache/flink-agents</a></b><br>
Agentic AI framework based on Apache Flink

</td>
</tr>
<tr>
<td valign="top">

<details>
<summary>1 PR, 1 issue</summary>

PRs:
- [fix: stop leaking x-litellm-api-key to Anthropic + support OAuth tokens in passthrough](https://github.com/BerriAI/litellm/pull/20432)

Issues:
- [LiteLLM Proxy to Transcription Model Fails](https://github.com/BerriAI/litellm/issues/10584)

</details>

</td>
<td valign="top">

<details>
<summary>1 PR, 1 issue</summary>

PRs:
- [[Bugfix] Use Thread Context ClassLoader for user class loading](https://github.com/apache/flink-agents/pull/514)

Issues:
- [ClassNotFoundException when loading user-defined resource classes from uploaded JARs](https://github.com/apache/flink-agents/issues/515)

</details>

</td>
</tr>
</table>

---

### Data & Stream Processing

<table>
<tr>
<td valign="top" width="50%">

<b><a href="https://github.com/dbs-leipzig/gradoop">dbs-leipzig/gradoop</a></b><br>
Distributed graph analytics with Apache Flink

</td>
<td valign="top" width="50%">

<b><a href="https://github.com/lensesio/stream-reactor">lensesio/stream-reactor</a></b><br>
Open source Kafka Connectors

</td>
</tr>
<tr>
<td valign="top">

<details>
<summary>6 PRs, 5 issues</summary>

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

</td>
<td valign="top">

<details>
<summary>1 PR</summary>

PRs:
- [Fix connect.s3.vhost.bucket inverted semantics](https://github.com/lensesio/stream-reactor/pull/2013)

</details>

</td>
</tr>
</table>

---

### Developer Tools & Other

<table>
<tr>
<td valign="top" width="50%">

<b><a href="https://github.com/Beingpax/VoiceInk">Beingpax/VoiceInk</a></b><br>
Voice-to-text app for macOS

</td>
<td valign="top" width="50%">

<b><a href="https://github.com/zereight/gitlab-mcp">zereight/gitlab-mcp</a></b><br>
GitLab MCP server

</td>
</tr>
<tr>
<td valign="top">

<details>
<summary>1 PR, 2 issues</summary>

PRs:
- [Fix OCR capturing VoiceInk status overlay instead of frontmost app window](https://github.com/Beingpax/VoiceInk/pull/429)

Issues:
- [Date and execution time flipped for history request](https://github.com/Beingpax/VoiceInk/issues/430)
- [Screen content not detected](https://github.com/Beingpax/VoiceInk/issues/424)

</details>

</td>
<td valign="top">

<details>
<summary>1 PR</summary>

PRs:
- [Pin zod-to-json-schema to 3.24.5](https://github.com/zereight/gitlab-mcp/pull/285)

</details>

</td>
</tr>
<tr>
<td valign="top">

<b><a href="https://github.com/hasura/graphql-engine">hasura/graphql-engine</a></b><br>
Blazing fast, instant realtime GraphQL APIs

</td>
<td></td>
</tr>
<tr>
<td valign="top">

<details>
<summary>1 issue</summary>

Issues:
- [Remote Schema Permissions Default Value Null leads to Validation Error](https://github.com/hasura/graphql-engine/issues/7772)

</details>

</td>
<td>

<details>
<summary>&nbsp;</summary>
</details>

</td>
</tr>
</table>
