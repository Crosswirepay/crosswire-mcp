# Crosswire MCP

Crosswire prices, scopes and routes payment infrastructure for high-risk and
cross-border businesses: banking, acquiring, payouts, digital assets, KYC and
cross-border settlement. This MCP server exposes the same engine that powers
crosswirepay.com, so an AI assistant can quote an indicative band, check
coverage, design a stack and request an offer on a client's behalf.

The server is hosted. This repository is the public descriptor; there is no
code to run.

- Endpoint (Streamable HTTP): https://crosswirepay.com/mcp
- Discovery: https://crosswirepay.com/.well-known/mcp.json
- Setup for Claude, ChatGPT and any MCP client: https://crosswirepay.com/connect
- Registry name: com.crosswirepay/crosswire
- Developer docs: https://crosswirepay.com/developers

Tools: get_indicative_price, check_coverage, list_solutions, recommend_stack,
assess_business, design_stack, compare_stack_scenarios, request_offer,
create_solution_offer, book_advisory, submit_partner_application,
ask_integration, get_faq, search, fetch.

Every price is an indicative range, subject to KYC/KYB and provider
underwriting. Providers are selected by Crosswire and named when a client's
application is prepared for signature. Write tools require explicit consent
and are rate-limited.

Not to be confused with other servers named "Crosswire" in the registry; this
one is payment infrastructure, published from the crosswirepay.com domain.

Contact: hello@crosswirepay.com
