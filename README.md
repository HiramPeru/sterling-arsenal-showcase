# Sterling Arsenal Technical Continuity Showcase

Sterling Arsenal is a sanitized public portfolio repository that documents a legacy business application review, technical continuity work, demo-readiness planning, and a modernization path for a legacy PHP platform.

This repository is intended to demonstrate technical judgment in legacy application assessment, documentation discipline, security hardening, sanitization, and phased modernization planning. It does not publish private implementation assets.

## Executive Summary

The original engagement involved replacing an MS Access-oriented workflow with a more modern cloud-oriented business platform. The public record for the original client-facing timeline ends with an open testing and review cycle in October 2023. This repository presents the work afterward as independent technical continuity, security-focused sanitization, demo-readiness preparation, documentation, and modernization alignment for a legacy business application.

## Repository Purpose

This public repository exists to:

- present a professional, sanitized technical showcase;
- document the legacy application at a high level;
- capture continuity and handover-oriented documentation;
- describe safe demo and review constraints; and
- outline a practical modernization path without exposing confidential assets.

## Public Scope Notice

This is a sanitized public portfolio repository. It does not include production source code, credentials, private database content, customer or vendor data, confidential screenshots, deployment secrets, database exports, or internal-only delivery assets.

## Historical Context

- July 2023: a modernization proposal was prepared to replace an MS Access-based workflow with a cloud-oriented business platform.
- September 2023: adoption planning covered database migration, parallel operation, and production transition planning.
- October 2023: the testing and review cycle remained open and was not completed within the original client-facing timeline.
- Subsequent work is framed here as technical continuity, documentation, sanitization, security hardening, demo readiness, and modernization planning.

## Current Technical Positioning

The legacy platform is represented as a PHP procedural application backed by a MySQL or MariaDB-style database, with local staging used for technical review. The documentation in this repository focuses on continuity and review readiness rather than code publication.

## Functional Areas Reviewed

- Customer and account records
- Sales and transaction workflows
- Acquisition and procurement processes
- Inventory or operational record handling
- Reporting and exported outputs
- Administrative access and review controls

## Technical Architecture Summary

At a high level, the reviewed system consists of a legacy PHP application layer, a relational database, operational and reporting views, and a controlled staging environment used for documentation and safe review preparation. See [Architecture](docs/architecture.md) and [Legacy Architecture Diagram](diagrams/legacy-architecture.mmd).

## Security And Sanitization Summary

Public materials are limited to sanitized documentation and diagrams. The portfolio framing assumes no production secrets, no private data, no PII exposure, no destructive actions in a demo context, and no debug or SQL visibility in stakeholder-facing review surfaces. See [Security And Sanitization](docs/security-sanitization.md).

## Demo Readiness Summary

The repository describes a safe review posture based on documentation, controlled staging, and read-only or demo-oriented constraints. It is designed for technical walkthroughs and stakeholder review without disclosing sensitive assets. See [Demo Readiness](docs/demo-readiness.md).

## Modernization Path Summary

The preferred modernization direction is a Laravel plus PostgreSQL backend, with a possible Next.js and TypeScript executive interface for modern reporting and operational visibility. This is presented as a recommended path, not a completed delivery. See [Modernization Path](docs/modernization-path.md).

## Documentation Index

- [Technical Continuity](docs/technical-continuity.md)
- [Architecture](docs/architecture.md)
- [Legacy Application Review](docs/legacy-application-review.md)
- [Security And Sanitization](docs/security-sanitization.md)
- [Demo Readiness](docs/demo-readiness.md)
- [Modernization Path](docs/modernization-path.md)
- [Delivery Scope](docs/delivery-scope.md)
- [Client Handover Notes](docs/client-handover-notes.md)
- [Legacy Architecture Diagram](diagrams/legacy-architecture.mmd)
- [Demo Readiness Flow Diagram](diagrams/demo-readiness-flow.mmd)
- [Modernization Path Diagram](diagrams/modernization-path.mmd)
- [Screenshots Guidance](screenshots/README.md)

## Repository Boundary

This repository is a sanitized public showcase only. It does not include production source code, credentials, private data, database exports, confidential client assets, or internal implementation materials.
