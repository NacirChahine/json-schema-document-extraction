# JSON Schema Document Extraction Examples

This repository demonstrates my experience designing JSON Schemas for extracting structured data from complex, unstructured documents such as invoices and contracts.

## Key Features

- Deeply nested JSON structures
- Field-level validation (types, constraints, required fields)
- Handling optional vs required data
- Reusable schema components
- Real-world document modeling

## Schemas

### Invoice Schema
Models a typical invoice with:
- Vendor information
- Line items (repeating structure)
- Totals and validation logic

### Contract Schema
Models a legal agreement with:
- Parties
- Clauses (nested + repeatable)
- Dates and conditions

## Examples

- Valid and invalid JSON samples included to demonstrate schema validation

## Notes

These examples reflect how I approach:
- Translating unstructured documents into structured formats
- Designing scalable and maintainable schemas
- Embedding validation logic directly into schemas