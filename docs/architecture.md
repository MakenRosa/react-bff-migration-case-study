# Frontend and BFF responsibilities

These are conceptual notes about common engineering patterns, not a diagram of a company's production architecture.

## Frontend

Components and screens present information and consume an API contract. Separating presentation from integration concerns can make each responsibility easier to understand and change.

## BFF

A Backend-for-Frontend can adapt backend data to a particular interface. Validation and response shaping help establish what frontend consumers may expect.

## Tradeoff

A tailored contract can simplify frontend consumers, while adding a layer whose behavior and validation need maintenance. This is a general tradeoff, not a measured result for a specific system.

No upstream service map, private route, real payload, data schema, infrastructure identifier or implementation is included. See the [portfolio account](../README.md).
