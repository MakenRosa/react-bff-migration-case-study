# React + BFF Migration - Case Study

## Overview
This case study describes the migration of a critical legacy AngularJS module to a modular React/TypeScript architecture integrated through a Backend-for-Frontend (BFF) layer.

## Business outcomes
- **80%+** improvement in time-to-interaction
- **80%+** unit-test coverage in the migrated scope
- Improved maintainability and team delivery speed

## Problem
The legacy module had high coupling, slower rendering, and difficult evolution for new product requirements.

## Solution strategy
1. Decompose legacy screens into modular React components
2. Introduce route-level lazy loading
3. Centralize async data patterns via React Query
4. Move integration details behind a BFF contract
5. Add automated tests on critical paths

## Deliverables in this repository
- Architecture notes (`docs/architecture.md`)
- Migration sequence (`docs/sequence.md`)
- Decision records (`adr/`)
- Security/NDA boundary (`SECURITY.md`)

## Security
No proprietary source code is published here.
