# SafeRoute — Project Brief

## What it is

SafeRoute is a real-time indoor evacuation routing system for schools. It uses a school's
**existing CCTV cameras** combined with **AI threat detection** to give teachers live,
room-by-room **evacuate / shelter directives** during active threats.

- **Product status:** working product (web + mobile), cloud-deployed
- **Stage:** pre-revenue, raising a first round (pre-seed/seed)
- **Market:** K-12 schools (B2B SaaS), safety-critical / dual-use technology

## Investor targeting thesis

We are looking for **pre-seed/seed investors — VC partners and angels** — who:

- Invest in **public safety, security tech, govtech, or K-12-focused B2B SaaS**
- Ideally hold portfolio companies in **physical security, emergency response,
  or computer vision / CCTV analytics**
- **Lead or join early rounds** in safety-critical or dual-use tech
- Are based in (or actively invest in) the **US and Europe**

## Comparable companies (for portfolio-overlap sourcing)

Weapon/threat detection on CCTV: ZeroEyes, Omnilert, Actuate AI, Evolv Technology
Video AI / physical security: Ambient.ai, Coram AI, Spot AI, HiveWatch, Flock Safety, Verkada
Emergency response: RapidSOS, Prepared (911), CrisisGo
K-12 safety SaaS: Bark, Securly, Gaggle, Raptor Technologies, CENTEGIX, Navigate360

## Lead-generation tooling notes

- `.mcp.json` configures the **Anysite MCP** (has a `crunchbase` source: `search` +
  `company` endpoints; company profiles include `investors[]` and `funding_rounds[]`).
  Subject to a 5-hour usage quota.
- The **official Crunchbase MCP** (`https://mcp.crunchbase.com`, OAuth login, no API key)
  can be added as a server, but this remote environment's egress proxy must allowlist
  `mcp.crunchbase.com` first.
