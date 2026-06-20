# Gcore (gcore)

Gcore is a global edge cloud, CDN, streaming, and AI infrastructure provider operating 210+ points of presence. A single REST platform at https://api.gcore.com (APIKey auth) spans content delivery, GPU cloud and bare-metal compute, S3-compatible object storage, managed DNS, video streaming and live, Everywhere Inference (edge AI), WAAP/DDoS security, and FastEdge serverless functions.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/gcore/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/gcore/refs/heads/main/apis.yml)

## Tags

- Edge Cloud
- CDN
- Streaming
- Edge AI
- Infrastructure

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Gcore CDN API

Manage CDN resources, origin groups, caching and delivery rules, SSL certificates, and cache purge across 210+ points of presence.

- **Human URL:** [https://gcore.com/docs/api-reference/cdn](https://gcore.com/docs/api-reference/cdn)
- **Base URL:** `https://api.gcore.com/cdn`

#### Tags

- CDN
- Content Delivery
- Caching
- Purge

#### Properties

- [Documentation](https://gcore.com/docs/cdn)
- [API Reference](https://gcore.com/docs/api-reference/cdn)
- [OpenAPI](openapi/gcore-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gcore.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gcore.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gcore Cloud API

Provision and manage virtual machine instances, GPU and bare-metal compute, networks, volumes, floating IPs, and SSH keys scoped by project and region under /cloud/v1.

- **Human URL:** [https://gcore.com/docs/api-reference/cloud](https://gcore.com/docs/api-reference/cloud)
- **Base URL:** `https://api.gcore.com/cloud`

#### Tags

- Cloud
- Compute
- GPU
- Instances

#### Properties

- [Documentation](https://gcore.com/docs/cloud)
- [API Reference](https://gcore.com/docs/api-reference/cloud)
- [OpenAPI](openapi/gcore-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gcore.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gcore.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gcore Object Storage API

Provision and manage S3-compatible and SFTP object storage buckets, locations, and access credentials; billed per GB-hour of stored data.

- **Human URL:** [https://gcore.com/docs/api-reference/storage](https://gcore.com/docs/api-reference/storage)
- **Base URL:** `https://api.gcore.com/storage`

#### Tags

- Storage
- Object Storage
- S3

#### Properties

- [Documentation](https://gcore.com/docs/storage)
- [API Reference](https://gcore.com/docs/api-reference/storage)
- [OpenAPI](openapi/gcore-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gcore.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gcore.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gcore DNS API

Managed authoritative DNS - create and manage zones and RRSets (A, AAAA, CNAME, MX, TXT and more), including dynamic GeoDNS and failover records under /dns/v2.

- **Human URL:** [https://gcore.com/docs/api-reference/dns](https://gcore.com/docs/api-reference/dns)
- **Base URL:** `https://api.gcore.com/dns/v2`

#### Tags

- DNS
- Zones
- RRSets

#### Properties

- [Documentation](https://gcore.com/docs/dns)
- [API Reference](https://gcore.com/docs/api-reference/dns)
- [OpenAPI](openapi/gcore-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gcore.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gcore.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gcore Streaming API

Video hosting (VOD) and low-latency live streaming - upload and manage videos, create live streams, restreams, and recordings with adaptive multi-bitrate transcoding.

- **Human URL:** [https://gcore.com/docs/api-reference/streaming](https://gcore.com/docs/api-reference/streaming)
- **Base URL:** `https://api.gcore.com/streaming`

#### Tags

- Streaming
- Video
- Live
- VOD

#### Properties

- [Documentation](https://gcore.com/docs/streaming-platform)
- [API Reference](https://gcore.com/docs/api-reference/streaming)
- [OpenAPI](openapi/gcore-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gcore.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gcore.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gcore Everywhere Inference API

Everywhere Inference (Inference at the Edge) - deploy trained AI models to edge nodes across 180+ locations with smart routing, container registries, and optional per-deployment API-key auth (X-API-Key).

- **Human URL:** [https://gcore.com/docs/edge-ai/everywhere-inference](https://gcore.com/docs/edge-ai/everywhere-inference)
- **Base URL:** `https://api.gcore.com/cloud`

#### Tags

- Edge AI
- Inference
- AI Models

#### Properties

- [Documentation](https://gcore.com/docs/edge-ai/everywhere-inference)
- [API Reference](https://gcore.com/docs/api-reference/cloud)
- [OpenAPI](openapi/gcore-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gcore.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gcore.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gcore Security & WAAP API

Web Application and API Protection (WAAP), API discovery, custom and policy rules, plus DDoS Protection for infrastructure under /waap and /security/iaas.

- **Human URL:** [https://gcore.com/docs/api-reference/waap](https://gcore.com/docs/api-reference/waap)
- **Base URL:** `https://api.gcore.com/waap`

#### Tags

- Security
- WAAP
- WAF
- DDoS

#### Properties

- [Documentation](https://gcore.com/docs/waap)
- [API Reference](https://gcore.com/docs/api-reference/waap)
- [OpenAPI](openapi/gcore-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gcore.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gcore.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gcore FastEdge API

FastEdge serverless edge computing - deploy WebAssembly apps and functions that run on Gcore CDN edge nodes close to end users.

- **Human URL:** [https://gcore.com/docs/api-reference/fastedge](https://gcore.com/docs/api-reference/fastedge)
- **Base URL:** `https://api.gcore.com/fastedge`

#### Tags

- FastEdge
- Edge Functions
- Serverless
- WASM

#### Properties

- [Documentation](https://gcore.com/docs/fastedge)
- [API Reference](https://gcore.com/docs/api-reference/fastedge)
- [OpenAPI](openapi/gcore-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gcore.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gcore.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/G-Core)
- [LinkedIn](https://www.linkedin.com/company/gcore)
- [Website](https://gcore.com/)
- [Documentation](https://gcore.com/docs/api-reference/overview)
- [Plans](plans/gcore-plans-pricing.yml)
- [Rate Limits](rate-limits/gcore-rate-limits.yml)
- [Fin Ops](finops/gcore-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
