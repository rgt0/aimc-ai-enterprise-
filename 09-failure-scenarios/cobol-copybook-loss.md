# Scenario: Missing COBOL Copybook Context

## Description
AI generates incorrect logic due to incomplete context.

## Root Cause
- Copybook not included
- Chunking splits data structure

## Impact
- Broken business logic
- Incorrect transformation

## Detection
- Mismatch in field lengths
- Invalid test results

## Control
- Include copybooks in RAG
- Validate with domain expert

## Ownership
- AI Engineer → context quality
- Human → validation
