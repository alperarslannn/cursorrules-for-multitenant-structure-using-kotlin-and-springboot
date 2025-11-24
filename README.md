# cursorrules-for-multitenant-structure-using-kotlin-and-springboot

This repository contains a rule set and supporting checklist used by an AI assistant ("Cursor") to guide code generation and reviews for a Kotlin + Spring Boot 3 multi-tenant backend. The rules cover architecture patterns (multi-schema Postgres tenancy), security (OAuth2 + JWT), migrations (Liquibase), project layout, and testing / CI expectations.

The authoritative rule set is in the file `.cursorrules` and implementation improvements are tracked in `.cursorrules-improvements-checklist.md`.

Created by `alperarslannn`. These materials may be freely used, adapted, and redistributed. If you plan to modify the canonical `.cursorrules` file, please follow the update process documented inside that file (explicit approval is required for changes to the rules).

For questions or suggested improvements, please open an issue in this repository or contact the repository owner.
