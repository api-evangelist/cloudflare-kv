# Cloudflare KV

Cloudflare Workers KV is a globally distributed key-value store that allows developers to store and retrieve data at low latency from Cloudflare's edge network. It provides a REST API for reading, writing, deleting, and listing key-value pairs across namespaces, making it ideal for caching, configuration management, session storage, API authorization, and dynamic routing. KV supports eventual consistency across Cloudflare's global network with read latencies under 5ms, and is accessible both via Workers bindings and external REST API calls.

## Links

- [Website](https://www.cloudflare.com/products/kv/)
- [Documentation](https://developers.cloudflare.com/kv/)
- [Getting Started](https://developers.cloudflare.com/kv/get-started/)
- [REST API Reference](https://developers.cloudflare.com/api/resources/kv/)
- [OpenAPI Schema](https://raw.githubusercontent.com/cloudflare/api-schemas/main/openapi.yaml)
- [Pricing](https://developers.cloudflare.com/kv/platform/pricing/)
- [Limits](https://developers.cloudflare.com/kv/platform/limits/)
- [Release Notes](https://developers.cloudflare.com/kv/platform/release-notes/)
- [Status Page](https://www.cloudflarestatus.com/)
- [Blog](https://blog.cloudflare.com/)
- [GitHub Org](https://github.com/cloudflare)
- [LinkedIn](https://www.linkedin.com/company/cloudflare/)
- [X](https://x.com/Cloudflare)

## SDKs

- [TypeScript SDK](https://github.com/cloudflare/cloudflare-typescript)
- [Python SDK](https://github.com/cloudflare/cloudflare-python)
- [Go SDK](https://github.com/cloudflare/cloudflare-go)

## APIs.json

This repository is an [APIs.json](https://apisjson.org/) provider profile for Cloudflare KV maintained by [API Evangelist](https://apievangelist.com/).

- [apis.yml](apis.yml)
- [Plans and Pricing](plans/cloudflare-kv-plans-pricing.yml)
- [Rate Limits](rate-limits/cloudflare-kv-rate-limits.yml)
- [FinOps](finops/cloudflare-kv-finops.yml)
