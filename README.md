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
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Druva API Gateway](https://developer.druva.com)** | REST API layer for Druva's Data Resiliency Cloud, exposing Cyber Resilience, Endpoint Data Governance, Enterprise Workloads, CloudRanger, MSP, and Legal Hold APIs. Token-based authentication over HTTPS with base URL `https://apis.druva.com` [citation:1]. | Druva subscription required (quote-only, credit-based on deduplicated TB) | No public free tier; API access included with Druva subscription |
| **[Kong Gateway (Konnect)](https://konghq.com/)** | Cloud-native API gateway with Konnect managed control plane. Free trial offers 30 days of Enterprise functionality with no Gateway limits; Plus tier starts at $500/month per Dedicated Cloud Gateway control plane or $25/month for Serverless, including 1M API requests [citation:2]. | Konnect Plus: $500/month per Dedicated Cloud Gateway control plane; Serverless control plane $25/month [citation:2] | **30-day free trial**: $0, full Enterprise functionality, no Gateway limits, analytics retained 30 days [citation:2] |
| **[AWS API Gateway](https://aws.amazon.com/api-gateway/)** | Fully managed gateway for REST, HTTP, and WebSocket APIs. Pay-per-request with no minimum fees. New AWS customers receive up to $200 in Free Tier credits valid for 6 months, plus 1M API calls/month per API type for 12 months [citation:3][citation:14]. | HTTP API: ~$1.00/million requests; REST API: ~$3.50/million requests | **New customers**: 1M REST + 1M HTTP API calls/month + 1M WebSocket messages + 750K connection minutes for 12 months; $200 credits for 6 months [citation:3][citation:14] |
| **[Apigee (Google Cloud)](https://cloud.google.com/apigee)** | Enterprise API management with gateway, analytics, developer portal, and monetization. Evaluation organizations limited to 60 days, 1 runtime instance, 2 environments, and no production use or sensitive data [citation:4][citation:15]. | Subscription or pay-as-you-go (quote-only) | **60-day free evaluation**: 1 instance, 2 environments, no production workloads, organization deleted after 60 days [citation:4][citation:15] |
| **[Tyk](https://tyk.io/)** | Open-core API gateway (MPL 2.0 for Gateway and Pump) with Dashboard, Developer Portal, and MDCB as paid components. No public list prices—quoted by sales. Self-managed trial license available on request [citation:5]. | Quote-only (Core usage-based; Professional flat unlimited) | **Self-Managed trial license** available via request (license key by email); Tyk Gateway OSS free forever (MPL 2.0) [citation:5] |
| **[Azure API Management](https://azure.microsoft.com/en-us/products/api-management/)** | Microsoft's API gateway with Consumption, Developer, Basic, Standard, Premium, and v2 tiers. Consumption tier: first 1M calls/month free, then ~$3.50/million (region-varying) [citation:6]. | Consumption: pay-per-call (~$3.50/million after free tier) | **Consumption tier**: first 1M API calls/month free [citation:6] |
| **[Gravitee.io](https://www.gravitee.io/)** | API management supporting REST, SOAP, and event-driven APIs. Planet tier starts at ~$2,500/month for one production gateway. Community Edition under Apache 2.0 is free at any scale with no usage limits [citation:7]. | Planet: ~$2,500/month (1 production gateway); Galaxy/Universe: custom | **Community Edition**: Apache 2.0, free at any scale, no usage limits; **Cloud free trial** available via website [citation:7] |
| **[MuleSoft Anypoint](https://www.mulesoft.com/)** | Enterprise iPaaS and API management platform. Pricing quote-only; Salesforce lists a 30-day free trial with no credit card required [citation:8]. | Quote-only (enterprise contract) | **30-day free trial**: no credit card, no installation required [citation:8] |
| **[Traefik Hub](https://traefik.io/)** | Kubernetes-native API gateway built on open-source Traefik Proxy (MIT). Commercial tiers add WAF, advanced auth, multi-cluster management. Pricing gated behind sales contact; 30-day free trial available for API Gateway tier [citation:9]. | Quote-only (commercial tiers); Traefik Proxy OSS free (MIT) | **30-day free trial** for API Gateway tier; Traefik Proxy OSS free forever (MIT) [citation:9] |
| **[WSO2 API Manager](https://wso2.com/api-manager/)** | Fully open-source API management with SaaS and self-hosted options. Pay-As-You-Go from $119/month (10 interfaces, 10M events). Enterprise custom-priced with self-hosted available [citation:10]. | Pay-As-You-Go: from $119/month (10 interfaces, 10M events) [citation:10] | **30-day free trial**: 5 managed interfaces, 1M gateway events, 1 hybrid gateway, 1 developer portal, no credit card [citation:10] |

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
