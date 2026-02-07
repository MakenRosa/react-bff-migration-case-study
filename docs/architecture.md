# Architecture

## Target architecture
- React + TypeScript UI
- Route-level lazy loading
- Shared state and async layer
- BFF facade for domain APIs
- Unit test suite for critical components

## Key technical decisions
- Co-locate feature modules by domain
- Avoid direct coupling between UI and microservice contracts
- Standardize query/mutation behavior
