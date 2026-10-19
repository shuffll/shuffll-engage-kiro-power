# Shuffll Engage — Personalized video at scale

Create personalized video campaigns based on customer interests, behaviors, and audience segments. Tailor content across customer journeys, including e-commerce and product videos, and integrate it into your existing workflows through a robust API and MCP.

This Kiro Power candidate contains the reviewed portable skill from public agent kit v0.2.2 and its hosted MCP connection. Available capabilities depend on your connected organization, permissions, entitlements and live tool catalog. Authorized workflows can orchestrate third-party AI media generation. Generation and sending are separate actions requiring the appropriate access and approval.

## Local installation and verification

In Kiro, open Powers → Add Custom Power → Import power from a folder, and select this directory. Use “Shuffll Engage” or “personalized video” to test activation. Complete your client's supported OAuth flow and select the intended organization and minimum permissions. A paid Shuffll subscription and organization-enabled API/MCP access are required. This package does not grant service access.

Start with “Show my authorized organizations and available capabilities.” Then list templates without generating or sending media. Verify skill activation, authenticated MCP discovery and a permitted read-only business tool in Kiro before treating native compatibility as tested.

For Kiro CLI, clone this repository, run `kiro-cli powers install ./shuffll-engage-kiro-power`, and start `kiro-cli chat`. Activate Shuffll Engage, open `/mcp`, select its server and authenticate with Ctrl+A. Complete the organization and permission consent within the client's connection window. If the CLI reports a 60-second connection timeout, authenticate again and complete fresh consent promptly.

## Verification status

This candidate has not been submitted, approved or listed in the Kiro registry. Native Kiro CLI 2.32.0 installation, Power activation, skill-instruction loading, OAuth and authenticated MCP discovery were verified on October 19, 2026. A user-approved synthetic reviewer connection with only organizations:read and templates:read successfully called capabilities_get, organizations_list and templates_list. A later capabilities_get also succeeded beyond the initial five-minute access-token lifetime without another browser login. Refresh-token rotation metadata was not independently inspected. No generation or sending was tested; the returned template was not render-ready. No beta/preview eligibility attestation has been made for the hosted service. The three skill files match public agent kit v0.2.2 byte-for-byte. Both manifests pass the official Agent Plugins Draft2020-12 schemas. These results verify native read-only operation, not every workflow or marketplace approval.

## Links and support

- MCP: https://engage.shuffll.com/mcp
- API and authentication documentation: https://api-docs.shuffll.com/engage
- Reviewed public skill source: https://github.com/shuffll/shuffll-engage-agent-kit/tree/7e90f5cc9840b88069cdf1b08370e4fef5dddef5
- Support: https://api-docs.shuffll.com/contact
- Technical contact: isaac@shuffll.com
- Privacy policy: https://shuffll.com/privacy-policy/
- Service terms: https://shuffll.com/terms/

## License

The public skill, manifests and documentation are MIT licensed; see LICENSE. Shuffll application source and service access are not included. Service use remains subject to the applicable Shuffll agreement and terms.
