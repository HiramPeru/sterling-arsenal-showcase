# Public Showcase Security Review

## 1. Objective

This document defines the security and privacy rules for making the Sterling Arsenal project visible without exposing the private client codebase.

## 2. Public Repository Must Not Include

- Source code from the private repository.
- `.env` files.
- API keys.
- Tokens.
- Passwords.
- Deployment URLs.
- Database connection strings.
- Customer records.
- User records.
- Payment records.
- Operational exports.
- Internal messages.
- Private client documents.
- Commit history from the delivery repository.
- Screenshots with real client data.
- Local machine paths.
- Developer-specific paths.

## 3. Safe Public Content

The public repository may include:

- Sanitized project summary.
- Role and contribution statement.
- High-level delivery model.
- Generic architecture diagram.
- Roadmap without client-sensitive details.
- Placeholder screenshots.
- Public portfolio positioning.

## 4. Current Security Position

The public showcase is documentation-only and does not contain production code or sensitive client data.
