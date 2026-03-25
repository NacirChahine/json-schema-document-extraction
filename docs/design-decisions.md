# Design Decisions

## Invoice Schema

- Used nested objects for vendor to allow extensibility
- Items modeled as array to support repeating structures
- Included "total" per item for extraction use cases (even if derivable)
- Currency restricted using enum for validation

## Contract Schema

- Parties modeled as array for flexibility
- Clauses support deep nesting via subclauses
- Minimal required fields to handle document variability

## General Approach

- Balance strict validation with real-world flexibility
- Prioritize clarity and maintainability
- Use descriptions to document intent