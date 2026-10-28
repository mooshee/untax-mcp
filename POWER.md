---
name: untax
displayName: Untax
version: 0.4.4
author: Daniel Hallman
description: Research county property assessments and prepare draft comparisons.
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

# Untax for Kiro

Author: Daniel Hallman ([Moosh Works](https://mooshworks.com))

Research county property assessments and prepare draft comparisons from available records. Create a private veteran review PDF from a saved review you select, with unanswered questions shown. County records, your answers and any VA information you choose to share are identified separately. Missing building, identity, tax-year, taxable-value or filing evidence can limit the review. Drafts do not complete official forms, establish eligibility or authorize filing. Built by Moosh Works (https://mooshworks.com).

## Quick start

1. Open [Untax](https://untax.io) for property research and setup instructions.
2. Add `https://untax.io/mcp` as an MCP server in Kiro using the configuration below. Complete any required sign-in.
3. Check that the connection lists the tools before starting a task.

## Server configuration

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

## Available tools

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
