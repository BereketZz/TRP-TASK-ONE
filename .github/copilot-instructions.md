# Copilot Instructions
Use best practices and provide clear, structured explanations.
# Copilot Rules File
# Purpose: Guide AI agent to behave safely and predictably

## 1. Validate Input
- Pattern: Guard Clauses (Boris Cherny)
- Rule: Check all inputs before processing. Reject null or invalid inputs.
- Example:
```ts
if (!input) throw new Error("Input cannot be null");
