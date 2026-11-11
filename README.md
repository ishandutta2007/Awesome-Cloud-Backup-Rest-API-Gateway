# Awesome-Cloud-Backup-Rest-API-Gateway

## Top Cloud Backup REST API Gateway Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on API Traffic Management, Backup Service Integration & Multi-Tenant Gateway Orchestration*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Backup REST API Gateway**. These tools provide the API entry point for backup and data protection services—handling authentication, rate limiting, request routing, tenant isolation, and usage metering for backup APIs (Druva, Veeam, Commvault, etc.) while enforcing security and observability.

**Examples** include Druva API Gateway, Kong Gateway, AWS API Gateway, Apigee, Tyk, Azure API Management, Gravitee.io, MuleSoft Anypoint, Traefik, and WSO2 API Manager (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted API gateways with strong community backing and production adoption—ideal for platform engineers, backup administrators, and developers building transparent, vendor-neutral API infrastructure without per-request cloud billing surprises.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global API management and gateway sector is estimated at **$8.6B to $13.5B in 2026** (growing at ~16–28% CAGR), driven by microservices architectures, hybrid cloud data mobility, and AI agent API traffic. The market is **moderately fragmented**: enterprise infrastructure is heavily concentrated at the top among hyperscalers (Microsoft, Alphabet, Amazon) and enterprise suites (Salesforce/MuleSoft), while strong open-core innovators (Kong, Tyk, Gravitee, WSO2, Traefik Labs) maintain substantial market share through cloud-native agility and open-source ecosystems.

## SaaS/Hosted Platforms

| Product | Company Valuation / Revenue | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-----------------------------|-------------|-------------------|--------------------------|
| **[Azure API Management](https://azure.microsoft.com/en-us/products/api-management/)** | ~$4.04T (Microsoft Market Cap) | Microsoft's enterprise API gateway supporting hybrid and multi-cloud API orchestration. | Consumption tier: ~$3.50/million calls (after free grant); Developer tier from $48.04/month | **Consumption tier**: 1M API calls/month free forever; 1 active service unit |
| **[Apigee (Google Cloud)](https://cloud.google.com/apigee)** | ~$3.53T (Alphabet Market Cap) | Enterprise API management with gateway, analytics, developer portal, and policy governance. | Pay-as-you-go: $0.50/hour per base environment (~$365/month) + $20/million standard API calls | **60-day free evaluation**: 1 instance, 2 environments, capped at non-production evaluation workloads |
| **[AWS API Gateway](https://aws.amazon.com/api-gateway/)** | ~$2.93T (Amazon Market Cap) | Fully managed gateway for REST, HTTP, and WebSocket APIs with direct AWS service integrations. | HTTP API: $1.00/million calls; REST API: $3.50/million calls | **AWS Free Tier (12 months)**: 1M REST calls + 1M HTTP calls + 1M WebSocket messages + 750K connection minutes/month |
| **[MuleSoft Anypoint](https://www.mulesoft.com/)** | ~$186B (Salesforce Market Cap) | Enterprise integration platform as a service (iPaaS) and full lifecycle API management suite. | Anypoint Starter from $2,000/month ($24,000 billed annually) based on Mule credit consumption | **30-day free trial**: Access to CloudHub, Design Center, and Exchange; 1 virtual core (vCore) max, no credit card required |
| **[Kong Gateway (Konnect)](https://konghq.com/)** | $2.0B Valuation ($100M+ ARR) | Cloud-native API gateway and service connectivity platform built on OpenResty/Envoy. | Konnect Serverless from $25/month (includes 1M API requests); Dedicated Cloud Gateway from $500/month | **30-day free trial**: Full Enterprise functionality, unlimited Gateway instances, analytics retained 30 days |
| **[Druva API Gateway](https://developer.druva.com)** | $2.0B Valuation ($200M+ ARR) | Dedicated REST API layer for Druva's Data Resiliency Cloud, exposing backup, retention, and MSP APIs. | Starts at ~$7–$10/user/month (Endpoint) or ~$200/TB/month (Server Workloads, volume-tiered) | **30-day free trial**: Full access to Data Resiliency Cloud APIs, capped at 100 endpoints or 5 TB backup storage |
| **[WSO2 API Manager](https://wso2.com/api-manager/)** | $600M Valuation (~$130M ARR) | Open-source-driven API management and governance platform with SaaS and self-hosted editions. | Pay-As-You-Go SaaS from $119/month (includes 10 managed API interfaces and 10M monthly gateway events) | **30-day free trial**: 5 managed API interfaces, 1M gateway events, 1 hybrid gateway, and hosted developer portal |
| **[Gravitee.io](https://www.gravitee.io/)** | $300M+ Valuation ($30M ARR) | API management and security platform supporting synchronous (REST/GraphQL) and event-driven (Kafka/MQTT) APIs. | Planet Cloud tier from $2,500/month (1 production gateway); Community Edition OSS is $0 | **Community Edition**: Free forever (Apache 2.0, unlimited gateways); **Gravitee Cloud 14-day free trial** with full enterprise features |
| **[Tyk](https://tyk.io/)** | ~$18M ARR (Private) | High-performance open-source API gateway and management platform supporting REST, GraphQL, and MCP. | Tyk Cloud Starter historically from $600/month (~10M calls); Self-Managed OSS Gateway is $0 | **Tyk Gateway OSS**: Free forever (MPL 2.0, unlimited scale); **Tyk Enterprise 14-day free trial** license on request |
| **[Traefik Hub](https://traefik.io/)** | ~$3M ARR / $11.2M Funding (Private) | Kubernetes-native API gateway and management platform built on the open-source Traefik Proxy engine. | Traefik Hub Team from $99/month; Traefik Proxy OSS is $0 (MIT) | **Traefik Proxy OSS**: Free forever (MIT, unlimited scale); **Traefik Hub 30-day free trial** for API Gateway commercial tier |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Kong Gateway (OSS)](https://github.com/Kong/kong)** | [![Stars](https://img.shields.io/github/stars/Kong/kong?style=social&color=white)](https://github.com/Kong/kong/stargazers) | The most widely deployed open-source API gateway. Lua/OpenResty-based with rich plugin ecosystem for auth, rate limiting, logging, and transformation. Enterprise adds RBAC, SSO, and MCP proxy. |
| **[Traefik Proxy](https://github.com/traefik/traefik)** | [![Stars](https://img.shields.io/github/stars/traefik/traefik?style=social&color=white)](https://github.com/traefik/traefik/stargazers) | Cloud-native reverse proxy and load balancer (MIT). Auto-discovers services from Kubernetes, Docker, and Consul. Commercial Hub tier adds WAF and advanced auth [citation:9]. |
| **[Tyk Gateway](https://github.com/TykTechnologies/tyk)** | [![Stars](https://img.shields.io/github/stars/TykTechnologies/tyk?style=social&color=white)](https://github.com/TykTechnologies/tyk/stargazers) | Open-source API gateway (MPL 2.0). Dashboard, Developer Portal, and MDCB are paid components. Supports REST, GraphQL, TCP, UDP, and MCP Gateway [citation:5]. |
| **[Apache APISIX](https://github.com/apache/apisix)** | [![Stars](https://img.shields.io/github/stars/apache/apisix?style=social&color=white)](https://github.com/apache/apisix/stargazers) | High-performance cloud-native API gateway built on NGINX + etcd. Rich plugin ecosystem for auth, rate-limiting, observability, and traffic splitting. Apache 2.0. |
| **[Gravitee API Management (OSS)](https://github.com/gravitee-io/gravitee-api-management)** | [![Stars](https://img.shields.io/github/stars/gravitee-io/gravitee-api-management?style=social&color=white)](https://github.com/gravitee-io/gravitee-api-management/stargazers) | Apache-2.0 open-core API management covering HTTP and event-driven APIs (Kafka, MQTT). Community Edition free at any scale [citation:7]. |
| **[WSO2 API Manager](https://github.com/wso2/product-apim)** | [![Stars](https://img.shields.io/github/stars/wso2/product-apim?style=social&color=white)](https://github.com/wso2/product-apim/stargazers) | Fully open-source (Apache 2.0) API management with gateway, publisher, and developer portal. Self-hosted free to run; enterprise support via subscription [citation:10]. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[KrakenD](https://github.com/krakend/krakend-ce)** | [![Stars](https://img.shields.io/github/stars/krakend/krakend-ce?style=social&color=white)](https://github.com/krakend/krakend-ce/stargazers) | Ultra-fast stateless API gateway in Go with declarative configuration. Aggregates multiple backend services into a single API endpoint without code. |
| **[Apache Camel](https://github.com/apache/camel)** | [![Stars](https://img.shields.io/github/stars/apache/camel?style=social&color=white)](https://github.com/apache/camel/stargazers) | Integration framework with 300+ connectors (REST, JMS, file, cloud). Can build custom API integration flows as a complement or alternative to a dedicated gateway. |
| **[Envoy Gateway](https://github.com/envoyproxy/gateway)** | [![Stars](https://img.shields.io/github/stars/envoyproxy/gateway?style=social&color=white)](https://github.com/envoyproxy/gateway/stargazers) | Kubernetes-native gateway built on Envoy Proxy, implementing the Gateway API specification. CNCF project with strong community backing. |

**Frameworks for building custom systems**: Combine **Kong OSS** or **Apache APISIX** for API routing and policy enforcement, **Traefik Proxy** for Kubernetes-native ingress, and **Apache Camel** for integration flow orchestration—creating a fully self-hosted API gateway stack for backup service APIs with no per-request billing.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- API gateways handling backup service traffic must enforce strong authentication (OAuth 2.0, token-based), rate limiting per tenant, and audit logging for all API calls.
- Cloud gateway pricing varies by request volume and feature tier; self-hosted open-source gateways require infrastructure provisioning, maintenance, and security hardening.

---

**Made for platform engineers, backup administrators, API architects, and developers building resilient API infrastructure.**  
Let's make cloud backup API gateways more open, secure, and observable.
