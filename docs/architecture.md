# Architecture

## Legacy Architecture Overview

The legacy platform is documented as a PHP procedural business application supported by a MySQL or MariaDB-style relational database. The system appears to have been organized around business workflows rather than a modern service-oriented architecture, which is common for long-lived line-of-business platforms that evolved incrementally over time.

## Application Layer

The application layer is best understood as a server-rendered PHP environment with tightly coupled workflow handling, page-level logic, and direct interaction with the database layer. In this kind of system, feature growth often leads to mixed concerns across presentation, business rules, and persistence logic.

## Database Layer

The database layer is represented as the operational source of record for customers, sales, procurement or acquisition records, inventory or operational tracking, reporting support, and administrative workflows. Legacy relational systems of this kind may accumulate procedural dependencies, ad hoc reporting tables, or tightly coupled query assumptions over time.

## Session And Authentication Considerations

Legacy PHP systems typically depend on session-based access control, page-level role checks, and environment-specific credential handling. For continuity and demo-readiness planning, authentication should be treated as a sensitive boundary requiring explicit review of:

- session handling consistency;
- role-based access enforcement;
- administrative access boundaries; and
- credential storage and rotation practices.

## File And Reporting Dependencies

Business applications in this category frequently rely on generated reports, exported files, printable outputs, or local file dependencies tied to operations and administration. These dependencies require separate review because they often sit outside the core request-response flow while still carrying sensitive or business-critical outputs.

## Deployment And Staging Considerations

The reviewed posture assumes a local Docker-based staging environment for technical inspection and safe demonstration planning. Any future hosted review environment would need separate validation for configuration management, access controls, data masking, file handling, and auditability.

## Constraints Of Legacy PHP Procedural Systems

- application logic can be distributed across page handlers and includes;
- database access patterns may be tightly coupled to UI flows;
- reuse boundaries are often inconsistent;
- upgrade and testing paths can be difficult to isolate;
- security controls may vary by module rather than by a centralized policy layer.

These are typical review concerns rather than claims about specific hidden implementation details.

## Diagram Reference

See [Legacy Architecture Diagram](../diagrams/legacy-architecture.mmd) for a sanitized overview of the reviewed platform structure.
