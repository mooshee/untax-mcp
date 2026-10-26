---
name: untax
displayName: Untax
version: 0.4.2
author: Daniel Hallman
description: Source-backed property assessment research and draft assessment comparisons for supported pilot jurisdictions.
keywords:
  - property-tax
  - tax-assessment
  - tax-appeal
  - real-estate
  - veteran-relief
  - tennessee
  - georgia
mcpServers:
  untax:
    type: streamable-http
    url: https://untax.io/mcp
---

# Untax Power (AWS Kiro)

Author: Daniel Hallman

Source-backed property assessment research and draft assessment comparisons for supported pilot jurisdictions. Free private veteran review PDFs use explicitly selected saved reviews and show unanswered questions. Retained county facts, owner reports and optional permitted VA observations remain distinct. Building-model, identity, tax-year, taxable-basis and filing holds remain in force. Drafts do not complete official forms, establish eligibility or authorize filing.

## Quick start

1. Visit [Untax](https://untax.io) or connect Kiro to `https://untax.io/mcp`.

## MCP Server Configuration

```json
{
  "mcpServers": {
    "untax": {
      "type": "streamable-http",
      "url": "https://untax.io/mcp"
    }
  }
}
```

## Tools Available

- `audit_microtransaction`
- `complete_tax_sandbox_order`
- `disconnect_va_connection`
- `find_va_facilities`
- `find_va_forms`
- `generate_veteran_packet`
- `get_appeal_lifecycle`
- `get_microtransactions_catalog`
- `get_owner_review_details`
- `get_owner_workspace`
- `get_property_assessment`
- `get_tax_sandbox_order`
- `get_va_connection`
- `get_va_facility`
- `get_va_form`
- `recheck_property_opportunities`
- `review_veteran_requirements`
- `start_tax_sandbox`
- `start_va_connection`
- `suggest_addresses`
