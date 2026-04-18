# Perforce (perforce)
Perforce Software provides enterprise-scale development tools, including version control, application lifecycle management, agile planning, and static analysis solutions for development teams.

**URL:** [Visit APIs.json URL](https://www.perforce.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Code Review, Collaboration, DevOps, Version Control

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-18

## APIs

### Perforce Helix Core API
REST API for Helix Core version control system, providing programmatic access to repository operations, file management, and versioning capabilities.

**Human URL:** [https://www.perforce.com/products/helix-core](https://www.perforce.com/products/helix-core)

#### Tags:

 - DevOps, SCM, Source Control, Version Control

#### Properties

- [Documentation](https://www.perforce.com/manuals/p4api/)
- [OpenAPI](https://api.perforce.com/helix-core/openapi.json)
- [Authentication](https://www.perforce.com/manuals/p4api/Content/P4API/authentication.html)
- [GettingStarted](https://www.perforce.com/products/helix-core/learning-resources)

### Perforce Helix Swarm API
REST API for Helix Swarm code review and collaboration platform, enabling automated code review workflows and team collaboration.

**Human URL:** [https://www.perforce.com/products/helix-swarm](https://www.perforce.com/products/helix-swarm)

#### Tags:

 - Code Review, Collaboration, Workflow

#### Properties

- [Documentation](https://www.perforce.com/manuals/swarm/Content/Swarm/swarm-apidoc.html)
- [APIReference](https://www.perforce.com/manuals/swarm/api/index.html)
- [Authentication](https://www.perforce.com/manuals/swarm/Content/Swarm/swarm-apidoc_endpoints.html)
- [OpenAPI](openapi/perforce-helix-swarm-openapi.yml)
- [JSONSchema](json-schema/perforce-review-schema.json)
- [JSONLD](json-ld/perforce-context.jsonld)

### Perforce Helix ALM REST API
REST API for Helix ALM application lifecycle management platform, enabling automation of tasks and development of integrations for requirements management, issue tracking, and test case management.

**Human URL:** [https://www.perforce.com/products/helix-alm](https://www.perforce.com/products/helix-alm)

#### Tags:

 - Application Lifecycle Management, Issue Tracking, Requirements Management, Test Management

#### Properties

- [Documentation](https://help.perforce.com/helix-alm/helixalm/current/restapi/Default.htm)
- [APIReference](https://help.perforce.com/helix-alm/helixalm/current/rest-api/index.html)
- [GettingStarted](https://help.perforce.com/helix-alm/helixalm/2019.3.0/restapi/Content/RESTAPI/GettingStarted.htm)

### Perforce Helix Authentication Service API
REST API for the Helix Authentication Service, a Node.js based authentication protocol integration service supporting OpenID Connect and SAML 2.0 for authenticating users across Perforce products.

**Human URL:** [https://help.perforce.com/helix-core/integrations-plugins/helix-auth-svc/current/](https://help.perforce.com/helix-core/integrations-plugins/helix-auth-svc/current/)

#### Tags:

 - Authentication, Identity, OpenID Connect, SAML, SSO

#### Properties

- [Documentation](https://help.perforce.com/helix-core/integrations-plugins/helix-auth-svc/current/)
- [APIReference](https://github.com/perforce/helix-authentication-service/blob/main/docs/REST_API.md)
- [GitHubRepository](https://github.com/perforce/helix-authentication-service)

## Common Properties

- [Portal](https://www.perforce.com/support/developers)
- [GettingStarted](https://www.perforce.com/support/self-service-resources)
- [Documentation](https://www.perforce.com/support/self-service-resources/documentation)
- [Blog](https://www.perforce.com/blog)
- [Support](https://www.perforce.com/support)
- [StatusPage](https://status.perforce.com)
- [Integrations](https://www.perforce.com/plugins-integrations)
- [GitHubOrganization](https://github.com/perforce)
- [TermsOfService](https://www.perforce.com/terms-use)
- [PrivacyPolicy](https://www.perforce.com/privacy-policy)
- [Contact](https://www.perforce.com/contact-us)

## Features

| Name | Description |
|------|-------------|
| Code Review | Collaborative code review workflows with Helix Swarm supporting inline comments, voting, tasks, and approval gates. |
| Version Control | Enterprise-scale version control with Helix Core supporting large binary files, distributed development, and atomic changelists. |
| Digital Asset Management | Versioned digital asset workflows with P4 DAM for reviewing, sharing, and managing creative assets stored in Helix Core. |
| Application Lifecycle Management | End-to-end ALM with Helix ALM for requirements traceability, issue tracking, and test case management. |
| Agile Planning | Agile project management with P4 Plan supporting sprints, backlogs, Gantt charts, and resource planning. |
| Authentication Services | Single sign-on across Perforce products with Helix Authentication Service supporting OpenID Connect and SAML 2.0. |

## Use Cases

| Name | Description |
|------|-------------|
| Game Development | Manage large game assets and source code with Helix Core providing fast file transfers and atomic changelists for game studios. |
| Semiconductor Design | Version control for chip design files with support for large binary IP blocks and strict access controls. |
| Automotive Software | Manage safety-critical automotive software with full traceability from requirements through testing using Helix ALM. |
| DevOps Automation | Automate CI/CD pipelines with Helix Core triggers, Swarm review gates, and REST API integrations. |

## Integrations

| Name | Description |
|------|-------------|
| Jenkins | Trigger builds and report results through Helix Core and Swarm integration plugins for Jenkins CI/CD. |
| Visual Studio | Native Visual Studio integration with P4VS plugin for source control operations from within the IDE. |
| Unity | Helix Core plugin for Unity game engine enabling version control of game projects directly within the editor. |
| Unreal Engine | Native Helix Core integration with Unreal Engine for versioning game assets and source code. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Perforce Helix Swarm API](openapi/perforce-helix-swarm-openapi.yml)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Perforce Helix Swarm API](capabilities/shared/helix-swarm.yaml) — 12 operations for code review and collaboration

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Code Review and Collaboration](capabilities/code-review-collaboration.yaml) | Helix Swarm | 12 | Development Team |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
