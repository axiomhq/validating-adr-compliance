# Validating ADR Compliance

A skill for validating PR code against Architecture Decision Records (ADRs).

## Description

Uses oracle for deep analysis of implementation compliance. This skill helps ensure code changes properly implement architectural decisions documented in ADRs.

## When to Use

- Validating a PR implements an ADR correctly
- Checking if code changes align with documented architectural decisions
- Reviewing implementation details against ADR specifications
- Identifying deviations from accepted architecture

## Installation

### Amp

```bash
amp skill install github.com/axiomhq/validating-adr-compliance
```

### Claude Code (via marketplace)

```bash
/plugin install validating-adr-compliance@axiom-marketplace
```

## Usage

Ask to validate a PR against an ADR:
- "Validate this PR against ADR-0052"
- "Check ADR compliance for the current branch"
- "Review if this implementation follows the architecture decision"

## License

MIT
