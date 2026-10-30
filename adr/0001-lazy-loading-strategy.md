# Technical note: route-level loading

## Scope

This note discusses a common frontend pattern. It is not an internal decision record or a statement about a company's implementation.

## Pattern

Load route-specific code when it is needed instead of including every route in the initial download.

## Tradeoffs

This can reduce initial work, while requiring suitable loading and failure states. The benefit depends on the application and must be measured in its own context. No internal benchmark or result is included.
