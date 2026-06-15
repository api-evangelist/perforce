# Perforce (perforce)

Perforce Software provides enterprise-scale development tools, including version control, application lifecycle management, agile planning, and static analysis solutions for development teams.

**APIs.json:** [https://www.perforce.com](https://www.perforce.com)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Perforce Helix Core API

REST API for Helix Core version control system, providing programmatic access to repository operations, file management, and versioning capabilities.

- **Human URL:** [https://www.perforce.com/products/helix-core](https://www.perforce.com/products/helix-core)
- **Base URL:** `https://api.perforce.com/helix-core/v1`

#### Tags

- DevOps
- SCM
- Source Control
- Version Control

#### Properties

- [Documentation](https://www.perforce.com/manuals/p4api/)
- [OpenAPI](https://api.perforce.com/helix-core/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://www.perforce.com/manuals/p4api/Content/P4API/authentication.html)
- [Getting Started](https://www.perforce.com/products/helix-core/learning-resources)
- [Postman Collection](collections/perforce-helix-swarm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/perforce-helix-swarm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Perforce P4 REST API

Technology Preview REST API introduced with P4 Server 2025.2, providing a new way to automate workflows and integrate P4 with other tools via standard HTTP endpoints for server info, depots, files, and changelists.

- **Human URL:** [https://help.perforce.com/helix-core/server-apps/p4sag/current/Content/P4SAG/p4-rest-api.html](https://help.perforce.com/helix-core/server-apps/p4sag/current/Content/P4SAG/p4-rest-api.html)
- **Base URL:** `https://p4server.example.com/api/v0`

#### Tags

- Automation
- DevOps
- REST API
- Version Control

#### Properties

- [Documentation](https://help.perforce.com/helix-core/server-apps/p4sag/current/Content/P4SAG/p4-rest-api.html)
- [Changelog](https://help.perforce.com/helix-core/server-apps/cmdref/2025.2/Content/CmdRef/whats-new-2025-2.html)
- [Postman Collection](collections/perforce-helix-swarm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/perforce-helix-swarm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Perforce Helix Swarm API

REST API for Helix Swarm code review and collaboration platform, enabling automated code review workflows and team collaboration.

- **Human URL:** [https://www.perforce.com/products/helix-swarm](https://www.perforce.com/products/helix-swarm)
- **Base URL:** `https://swarm.example.com/api/v10`

#### Tags

- Code Review
- Collaboration
- Workflow

#### Properties

- [Documentation](https://www.perforce.com/manuals/swarm/Content/Swarm/swarm-apidoc.html)
- [API Reference](https://www.perforce.com/manuals/swarm/api/index.html)
- [Authentication](https://www.perforce.com/manuals/swarm/Content/Swarm/swarm-apidoc_endpoints.html)
- [OpenAPI](openapi/perforce-helix-swarm-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/perforce-helix-swarm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/perforce-helix-swarm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/perforce-review-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/perforce-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Perforce Hansoft API

API for Hansoft agile project management, providing access to project planning, tracking, and reporting capabilities.

- **Human URL:** [https://www.perforce.com/products/hansoft](https://www.perforce.com/products/hansoft)
- **Base URL:** `https://hansoft.example.com/api`

#### Tags

- Agile
- Planning
- Project Management

#### Properties

- [Documentation](https://www.perforce.com/manuals/hansoft-sdk/)
- [SDK](https://www.perforce.com/downloads/hansoft-sdk)
- [Postman Collection](collections/perforce-helix-swarm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/perforce-helix-swarm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Perforce P4 Plan API

GraphQL and REST API for P4 Plan (formerly Hansoft) agile project management, supporting queries, mutations, and real-time subscriptions for planning views, sprints, tasks, and user management.

- **Human URL:** [https://www.perforce.com/products/hansoft](https://www.perforce.com/products/hansoft)
- **Base URL:** `https://p4plan.example.com/api`

#### Tags

- Agile
- GraphQL
- Planning
- Project Management

#### Properties

- [Documentation](https://help.perforce.com/hansoft/current/Content/hansoftapi/index.html)
- [SDK](https://www.perforce.com/downloads/helix-plan-sdk)
- [Release Notes](https://cache.hansoft.com/releasenotes/helix-plan-api.html)
- [Postman Collection](collections/perforce-helix-swarm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/perforce-helix-swarm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Perforce Helix ALM REST API

REST API for Helix ALM application lifecycle management platform, enabling automation of tasks and development of integrations for requirements management, issue tracking, and test case management.

- **Human URL:** [https://www.perforce.com/products/helix-alm](https://www.perforce.com/products/helix-alm)
- **Base URL:** `https://helixalm.example.com/helix-alm/api/v0`

#### Tags

- Application Lifecycle Management
- Issue Tracking
- Requirements Management
- Test Management

#### Properties

- [Documentation](https://help.perforce.com/helix-alm/helixalm/current/restapi/Default.htm)
- [API Reference](https://help.perforce.com/helix-alm/helixalm/current/rest-api/index.html)
- [Getting Started](https://help.perforce.com/helix-alm/helixalm/2019.3.0/restapi/Content/RESTAPI/GettingStarted.htm)
- [Postman Collection](collections/perforce-helix-swarm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/perforce-helix-swarm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Perforce Helix TeamHub API

REST API for Helix TeamHub source code repository management platform, providing access to repositories, projects, users, and company resources across Git, Mercurial, Subversion, and other repository types.

- **Human URL:** [https://www.perforce.com/products/helix-teamhub](https://www.perforce.com/products/helix-teamhub)
- **Base URL:** `https://teamhub.example.com/api/v1`

#### Tags

- Collaboration
- Git
- Repositories
- Source Code Management

#### Properties

- [Documentation](https://help.perforce.com/helix-core/helix-teamhub/current/Content/HTH-API/api-v1.html)
- [Getting Started](https://help.perforce.com/helix-core/helix-teamhub/2025.5.0/Content/HTH-API/getting-started.html)
- [Postman Collection](collections/perforce-helix-swarm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/perforce-helix-swarm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Perforce P4 DAM REST API

REST API for P4 DAM (Digital Asset Management), enabling integration with digital asset workflows for finding, reviewing, sharing, and managing versioned assets stored in Helix Core.

- **Human URL:** [https://www.perforce.com/products/helix-dam](https://www.perforce.com/products/helix-dam)
- **Base URL:** `https://dam.example.com/api`

#### Tags

- Asset Management
- Digital Asset Management
- Media
- Version Control

#### Properties

- [Documentation](https://help.perforce.com/helix-core/helix-dam/current/api/)
- [Postman Collection](collections/perforce-helix-swarm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/perforce-helix-swarm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Perforce P4 Search API

REST API for P4 Search, providing indexing and search capabilities across Helix Core servers to support code review, file content search, and changelist description search.

- **Human URL:** [https://help.perforce.com/helix-core/integrations-plugins/p4search/current/Content/P4Search/overview.html](https://help.perforce.com/helix-core/integrations-plugins/p4search/current/Content/P4Search/overview.html)
- **Base URL:** `https://p4search.example.com/api`

#### Tags

- Code Search
- Indexing
- Search

#### Properties

- [Documentation](https://help.perforce.com/helix-core/integrations-plugins/p4search/current/Content/P4Search/api-endpoints.html)
- [Authentication](https://help.perforce.com/helix-core/integrations-plugins/p4search/current/Content/P4Search/api-authentication.html)
- [Postman Collection](collections/perforce-helix-swarm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/perforce-helix-swarm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Perforce Helix Authentication Service API

REST API for the Helix Authentication Service, a Node.js based authentication protocol integration service supporting OpenID Connect and SAML 2.0 for authenticating users across Perforce products.

- **Human URL:** [https://help.perforce.com/helix-core/integrations-plugins/helix-auth-svc/current/](https://help.perforce.com/helix-core/integrations-plugins/helix-auth-svc/current/)
- **Base URL:** `https://auth.example.com`

#### Tags

- Authentication
- Identity
- OpenID Connect
- SAML
- SSO

#### Properties

- [Documentation](https://help.perforce.com/helix-core/integrations-plugins/helix-auth-svc/current/)
- [API Reference](https://github.com/perforce/helix-authentication-service/blob/main/docs/REST_API.md)
- [GitHub Repository](https://github.com/perforce/helix-authentication-service)
- [Postman Collection](collections/perforce-helix-swarm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/perforce-helix-swarm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/perforce)
- [Portal](https://www.perforce.com/support/developers)
- [Getting Started](https://www.perforce.com/support/self-service-resources)
- [Documentation](https://www.perforce.com/support/self-service-resources/documentation)
- [Blog](https://www.perforce.com/blog)
- [Support](https://www.perforce.com/support)
- [Status Page](https://status.perforce.com)
- [Integrations](https://www.perforce.com/plugins-integrations)
- [GitHub Organization](https://github.com/perforce)
- [Terms of Service](https://www.perforce.com/terms-use)
- [Privacy Policy](https://www.perforce.com/privacy-policy)
- [Contact](https://www.perforce.com/contact-us)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [M C P Server](https://github.com/perforce/p4mcp-server)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
