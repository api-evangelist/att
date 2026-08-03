# AT&T (att)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

AT&T Inc. is a multinational telecommunications holding company providing wireless and wireline communications, broadband, and business networking to consumers and enterprises. Its developer surface spans four programs: the legacy AT&T Developer Program (SMS, MMS, in-app messaging, speech and OAuth), the MVNX APIs for mobile virtual network operators, the Alliance enterprise wireline APIs for service qualification and ordering, and the invite-only Network API Accelerator Program exposing GSMA CAMARA network APIs — SIM swap, device status, number verification, quality on demand, network insights and mobility threat detection.

**URL:** [https://raw.githubusercontent.com/api-evangelist/att/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/att/refs/heads/main/apis.yml)

## Tags:

 - 5G, Broadband, CAMARA, Connectivity, Device Status, Edge Computing, Enterprise, Fortune 100, Messaging, Mobile, Network, Network APIs, SIM Swap, Speech, Telecommunications, Wireless, Wireline

## Timestamps

- **Created:** 2025-05-02
- **Modified:** 2026-07-25

## APIs

### AT&T OAuth 2.0 API
AT&T OAuth 2.0 authentication API providing access tokens for all AT&T REST APIs. Supports Authorization Code, Client Credentials, and Refresh Token grant types. Scopes include ADS, MMS, SMS, SPEECH, STTC, and TTS.

**Human URL:** [https://developer.att.com/oauth-2](https://developer.att.com/oauth-2)

**Base URL:** https://api.att.com

#### Tags:

 - OAuth, Authentication, Authorization, Security

#### Properties

- [Documentation](https://developer.att.com/oauth-2/docs)
- [Authentication](https://developer.att.com/oauth-2/docs)

### AT&T Alliance Wireline APIs
Wireline business APIs enabling partners to expedite quoting, service qualification, and ordering of AT&T wireline products. Includes Quick Quote, Product Catalog, Service Qualification, Price Offer, Wireline Ordering, Order Status, AIAB (AT&T Internet Air for Business) Ordering, and Address Search APIs.

**Human URL:** [https://devex-web.att.com/alliance](https://devex-web.att.com/alliance)

**Base URL:** https://devex-web.att.com

#### Tags:

 - Wireline, Enterprise, Ordering, Service Qualification, Quoting

#### Properties

- [Documentation](https://devex-web.att.com/alliance)
- [GettingStarted](https://devex-web.att.com/order/docs/get-started-with-ordering-api)

### AT&T Authentication API
The Authentication API from AT&T — 1 operation(s) for authentication.

**Human URL:** [https://developer.att.com/sms](https://developer.att.com/sms)

**Base URL:** https://api.att.com

#### Tags:

 - Authentication

#### Properties

- [OpenAPI](openapi/att-authentication-api-openapi.yml)
- [Documentation](https://developer.att.com/sms/docs)
- [APIReference](https://developer.att.com/sms/docs/v2)
- [Authentication](https://developer.att.com/oauth-2/docs)
- [GettingStarted](https://developer.att.com/sms)

### AT&T Balance Management API
The Balance Management API from AT&T — 1 operation(s) for balance management.

**Human URL:** [https://devex-web.att.com/mvnx](https://devex-web.att.com/mvnx)

**Base URL:** https://devex-web.att.com

#### Tags:

 - Balance Management

#### Properties

- [OpenAPI](openapi/att-balance-management-api-openapi.yml)
- [Documentation](https://devex-web.att.com/mvnx/docs/mvnx-quickstart)
- [GettingStarted](https://devex-web.att.com/mvnx/docs/mvnx-quickstart)
- [Authentication](https://developer.att.com/oauth-2/docs)

### AT&T Device Management API
The Device Management API from AT&T — 2 operation(s) for device management.

**Human URL:** [https://devex-web.att.com/mvnx](https://devex-web.att.com/mvnx)

**Base URL:** https://devex-web.att.com

#### Tags:

 - Device Management

#### Properties

- [OpenAPI](openapi/att-device-management-api-openapi.yml)
- [Documentation](https://devex-web.att.com/mvnx/docs/mvnx-quickstart)
- [GettingStarted](https://devex-web.att.com/mvnx/docs/mvnx-quickstart)
- [Authentication](https://developer.att.com/oauth-2/docs)

### AT&T Geographic Sites API
The Geographic Sites API from AT&T — 1 operation(s) for geographic sites.

**Human URL:** [https://devex-web.att.com/mvnx](https://devex-web.att.com/mvnx)

**Base URL:** https://devex-web.att.com

#### Tags:

 - Geographic Sites

#### Properties

- [OpenAPI](openapi/att-geographic-sites-api-openapi.yml)
- [Documentation](https://devex-web.att.com/mvnx/docs/mvnx-quickstart)
- [GettingStarted](https://devex-web.att.com/mvnx/docs/mvnx-quickstart)
- [Authentication](https://developer.att.com/oauth-2/docs)

### AT&T Inbox Management API
The Inbox Management API from AT&T — 2 operation(s) for inbox management.

**Human URL:** [https://developer.att.com/in-app-messaging/docs](https://developer.att.com/in-app-messaging/docs)

**Base URL:** https://api.att.com

#### Tags:

 - Inbox Management

#### Properties

- [OpenAPI](openapi/att-inbox-management-api-openapi.yml)
- [Documentation](https://developer.att.com/in-app-messaging/docs)
- [Authentication](https://developer.att.com/oauth-2/docs)

### AT&T Messages API
The Messages API from AT&T — 2 operation(s) for messages.

**Human URL:** [https://developer.att.com/in-app-messaging/docs](https://developer.att.com/in-app-messaging/docs)

**Base URL:** https://api.att.com

#### Tags:

 - Messages

#### Properties

- [OpenAPI](openapi/att-messages-api-openapi.yml)
- [Documentation](https://developer.att.com/in-app-messaging/docs)
- [Authentication](https://developer.att.com/oauth-2/docs)

### AT&T Number Management API
The Number Management API from AT&T — 2 operation(s) for number management.

**Human URL:** [https://devex-web.att.com/mvnx](https://devex-web.att.com/mvnx)

**Base URL:** https://devex-web.att.com

#### Tags:

 - Number Management

#### Properties

- [OpenAPI](openapi/att-number-management-api-openapi.yml)
- [Documentation](https://devex-web.att.com/mvnx/docs/mvnx-quickstart)
- [GettingStarted](https://devex-web.att.com/mvnx/docs/mvnx-quickstart)
- [Authentication](https://developer.att.com/oauth-2/docs)

### AT&T Porting API
The Porting API from AT&T — 3 operation(s) for porting.

**Human URL:** [https://devex-web.att.com/mvnx](https://devex-web.att.com/mvnx)

**Base URL:** https://devex-web.att.com

#### Tags:

 - Porting

#### Properties

- [OpenAPI](openapi/att-porting-api-openapi.yml)
- [Documentation](https://devex-web.att.com/mvnx/docs/mvnx-quickstart)
- [GettingStarted](https://devex-web.att.com/mvnx/docs/mvnx-quickstart)
- [Authentication](https://developer.att.com/oauth-2/docs)

### AT&T Product Orders API
The Product Orders API from AT&T — 1 operation(s) for product orders.

**Human URL:** [https://devex-web.att.com/mvnx](https://devex-web.att.com/mvnx)

**Base URL:** https://devex-web.att.com

#### Tags:

 - Product Orders

#### Properties

- [OpenAPI](openapi/att-product-orders-api-openapi.yml)
- [Documentation](https://devex-web.att.com/mvnx/docs/mvnx-quickstart)
- [GettingStarted](https://devex-web.att.com/mvnx/docs/mvnx-quickstart)
- [Authentication](https://developer.att.com/oauth-2/docs)

### AT&T Service Management API
The Service Management API from AT&T — 1 operation(s) for service management.

**Human URL:** [https://devex-web.att.com/mvnx](https://devex-web.att.com/mvnx)

**Base URL:** https://devex-web.att.com

#### Tags:

 - Service Management

#### Properties

- [OpenAPI](openapi/att-service-management-api-openapi.yml)
- [Documentation](https://devex-web.att.com/mvnx/docs/mvnx-quickstart)
- [GettingStarted](https://devex-web.att.com/mvnx/docs/mvnx-quickstart)
- [Authentication](https://developer.att.com/oauth-2/docs)

### AT&T SMS Messaging API
The SMS Messaging API from AT&T — 3 operation(s) for sms messaging.

**Human URL:** [https://developer.att.com/sms](https://developer.att.com/sms)

**Base URL:** https://api.att.com

#### Tags:

 - SMS Messaging

#### Properties

- [OpenAPI](openapi/att-sms-messaging-api-openapi.yml)
- [Documentation](https://developer.att.com/sms/docs)
- [APIReference](https://developer.att.com/sms/docs/v2)
- [Authentication](https://developer.att.com/oauth-2/docs)
- [GettingStarted](https://developer.att.com/sms)

### AT&T Subscriber Management API
The Subscriber Management API from AT&T — 1 operation(s) for subscriber management.

**Human URL:** [https://devex-web.att.com/mvnx](https://devex-web.att.com/mvnx)

**Base URL:** https://devex-web.att.com

#### Tags:

 - Subscriber Management

#### Properties

- [OpenAPI](openapi/att-subscriber-management-api-openapi.yml)
- [Documentation](https://devex-web.att.com/mvnx/docs/mvnx-quickstart)
- [GettingStarted](https://devex-web.att.com/mvnx/docs/mvnx-quickstart)
- [Authentication](https://developer.att.com/oauth-2/docs)

### AT&T MVNO APIs
TM Forum-aligned APIs for mobile virtual network operators (MVNOs) on the AT&T network. The MVNX API suite covers subscriber activation, number portability, device management, service lifecycle management, and balance management following TMF open standards.

**Human URL:** [https://devex-web.att.com/mvnx](https://devex-web.att.com/mvnx)

**Base URL:** https://devex-web.att.com

#### Tags:

 - MVNO, TM Forum, Subscriber Management, Porting

#### Properties

- [Documentation](https://devex-web.att.com/mvnx/docs/mvnx-quickstart)
- [GettingStarted](https://devex-web.att.com/mvnx/docs/mvnx-quickstart)

### AT&T Cloud Voice APIs
REST APIs for AT&T Business Voice and Cloud Voice services enabling partners to manage service ordering, provisioning, and administration for AT&T's enterprise voice and cloud communication products.

**Human URL:** [https://devex-web.att.com/business-voice-cloud-voice](https://devex-web.att.com/business-voice-cloud-voice)

**Base URL:** https://devex-web.att.com

#### Tags:

 - Voice, Cloud, Business, UCaaS

#### Properties

- [Documentation](https://devex-web.att.com/business-voice-cloud-voice)

### AT&T eBonding APIs
Seamless API integration with AT&T's wireless and wireline IT and ordering systems. eBonding APIs enable enterprise partners and resellers to integrate their BSS/OSS systems directly with AT&T's backend systems for automated order management and status updates.

**Human URL:** [https://devex-web.att.com/ebonding-common](https://devex-web.att.com/ebonding-common)

**Base URL:** https://devex-web.att.com

#### Tags:

 - eBonding, Enterprise, BSS, OSS, Integration

#### Properties

- [Documentation](https://devex-web.att.com/ebonding-common)

### AT&T Order Management API
Track and manage existing orders

**Human URL:** [https://devex-web.att.com/alliance](https://devex-web.att.com/alliance)

**Base URL:** https://devex-web.att.com

#### Tags:

 - Order Management

#### Properties

- [OpenAPI](openapi/att-order-management-api-openapi.yml)
- [Documentation](https://devex-web.att.com/alliance)
- [GettingStarted](https://devex-web.att.com/order/docs/get-started-with-ordering-api)
- [Authentication](https://developer.att.com/oauth-2/docs)

### AT&T Product Ordering API
Place and manage service orders

**Human URL:** [https://devex-web.att.com/alliance](https://devex-web.att.com/alliance)

**Base URL:** https://devex-web.att.com

#### Tags:

 - Product Ordering

#### Properties

- [OpenAPI](openapi/att-product-ordering-api-openapi.yml)
- [Documentation](https://devex-web.att.com/alliance)
- [GettingStarted](https://devex-web.att.com/order/docs/get-started-with-ordering-api)
- [Authentication](https://developer.att.com/oauth-2/docs)

### AT&T Service Qualification API
Check service availability at a location

**Human URL:** [https://devex-web.att.com/alliance](https://devex-web.att.com/alliance)

**Base URL:** https://devex-web.att.com

#### Tags:

 - Service Qualification

#### Properties

- [OpenAPI](openapi/att-service-qualification-api-openapi.yml)
- [Documentation](https://devex-web.att.com/alliance)
- [GettingStarted](https://devex-web.att.com/order/docs/get-started-with-ordering-api)
- [Authentication](https://developer.att.com/oauth-2/docs)

### AT&T Device Connectivity API
The Device Connectivity API from AT&T — 1 operation(s) for device connectivity.

**Human URL:** [https://devex-web.att.com/developer-hub/](https://devex-web.att.com/developer-hub/)

**Base URL:** https://api.att.com/camara/device-status/v1

#### Tags:

 - Device Connectivity

#### Properties

- [OpenAPI](openapi/att-device-connectivity-api-openapi.yml)
- [Documentation](https://devex-web.att.com/developer-hub/)
- [GettingStarted](https://devex-web.att.com/developer-hub/docs/network-api-accelerator-program)

### AT&T Device Roaming API
The Device Roaming API from AT&T — 1 operation(s) for device roaming.

**Human URL:** [https://devex-web.att.com/developer-hub/](https://devex-web.att.com/developer-hub/)

**Base URL:** https://api.att.com/camara/device-status/v1

#### Tags:

 - Device Roaming

#### Properties

- [OpenAPI](openapi/att-device-roaming-api-openapi.yml)
- [Documentation](https://devex-web.att.com/developer-hub/)
- [GettingStarted](https://devex-web.att.com/developer-hub/docs/network-api-accelerator-program)

### AT&T Network Metrics API
The Network Metrics API from AT&T — 1 operation(s) for network metrics.

**Human URL:** [https://devex-web.att.com/developer-hub/](https://devex-web.att.com/developer-hub/)

**Base URL:** https://api.att.com/network/insights/v1

#### Tags:

 - Network Metrics

#### Properties

- [OpenAPI](openapi/att-network-metrics-api-openapi.yml)
- [Documentation](https://devex-web.att.com/developer-hub/)
- [GettingStarted](https://devex-web.att.com/developer-hub/docs/network-api-accelerator-program)

### AT&T Number Verification API
The Number Verification API from AT&T — 1 operation(s) for number verification.

**Human URL:** [https://devex-web.att.com/developer-hub/](https://devex-web.att.com/developer-hub/)

**Base URL:** https://api.att.com/camara/number-verification/v1

#### Tags:

 - Number Verification

#### Properties

- [OpenAPI](openapi/att-number-verification-api-openapi.yml)
- [Documentation](https://devex-web.att.com/developer-hub/)
- [GettingStarted](https://devex-web.att.com/developer-hub/docs/network-api-accelerator-program)

### AT&T Quality on Demand API
The QoD Sessions API from AT&T — 2 operation(s) for qod sessions.

**Human URL:** [https://devex-web.att.com/developer-hub/](https://devex-web.att.com/developer-hub/)

**Base URL:** https://api.att.com/camara/qod/v1

#### Tags:

 - QoD Sessions

#### Properties

- [OpenAPI](openapi/att-qod-sessions-api-openapi.yml)
- [Documentation](https://devex-web.att.com/developer-hub/)
- [GettingStarted](https://devex-web.att.com/developer-hub/docs/network-api-accelerator-program)

### AT&T SIM Swap API
The SIM Swap API from AT&T — 2 operation(s) for sim swap.

**Human URL:** [https://devex-web.att.com/developer-hub/](https://devex-web.att.com/developer-hub/)

**Base URL:** https://api.att.com/camara/sim-swap/v1

#### Tags:

 - SIM Swap

#### Properties

- [OpenAPI](openapi/att-sim-swap-api-openapi.yml)
- [Documentation](https://devex-web.att.com/developer-hub/)
- [GettingStarted](https://devex-web.att.com/developer-hub/docs/network-api-accelerator-program)

### AT&T Threat Detection API
The Threat Detection API from AT&T — 1 operation(s) for threat detection.

**Human URL:** [https://devex-web.att.com/developer-hub/](https://devex-web.att.com/developer-hub/)

**Base URL:** https://api.att.com/network/threat-detection/v1

#### Tags:

 - Threat Detection

#### Properties

- [OpenAPI](openapi/att-threat-detection-api-openapi.yml)
- [Documentation](https://devex-web.att.com/developer-hub/)
- [GettingStarted](https://devex-web.att.com/developer-hub/docs/network-api-accelerator-program)

### AT&T Threat Subscriptions API
The Threat Subscriptions API from AT&T — 1 operation(s) for threat subscriptions.

**Human URL:** [https://devex-web.att.com/developer-hub/](https://devex-web.att.com/developer-hub/)

**Base URL:** https://api.att.com/network/threat-detection/v1

#### Tags:

 - Threat Subscriptions

#### Properties

- [OpenAPI](openapi/att-threat-subscriptions-api-openapi.yml)
- [Documentation](https://devex-web.att.com/developer-hub/)
- [GettingStarted](https://devex-web.att.com/developer-hub/docs/network-api-accelerator-program)

## Common Properties

- [AgenticAccess](agentic-access/att-agentic-access.yml)
- [DomainSecurity](security/att-domain-security.yml)
- [Authentication](authentication/att-authentication.yml)
- [OAuthScopes](scopes/att-scopes.yml)
- [SpectralRules](rules/att-spectral-rules.yml)
- [Vocabulary](vocabulary/att-vocabulary.yaml)
- [GraphQL](graphql/att-graphql.md)
- [Website](https://www.att.com/)
- [Portal](https://developer.att.com/s/)
- [DeveloperPortal](https://devex-web.att.com/)
- [DeveloperPortal](https://devex-web.att.com/developer-hub/)
- [Documentation](https://developer.att.com/s/)
- [Documentation](https://devex-web.att.com/developer-hub/)
- [GettingStarted](https://devex-web.att.com/developer-hub/docs/network-api-accelerator-program)
- [Authentication](https://developer.att.com/oauth-2/docs)
- [Support](https://developer.att.com/support)
- [FAQ](https://developer.att.com/support/faqs/att-developer-program-and-api-platform-faqs)
- [Signup](https://developer.att.com/developer/manageMyAccount.jsp)
- [Signup](https://devex-web.att.com/developer-hub/docs/network-api-accelerator-program)
- [TermsOfService](https://www.att.com/gen/general?pid=11561)
- [PrivacyPolicy](https://www.att.com/gen/privacy-policy?pid=2506)
- [Blog](https://about.att.com/blogs)
- [StatusPage](https://www.att.com/support/article/wireless/KM1000428)
- [GitHubOrganization](https://github.com/att)
- [GitHubOrganization](https://github.com/attdevsupport)
- [X](https://x.com/att)
- [LinkedIn](https://www.linkedin.com/company/att)
- [YouTube](https://www.youtube.com/att)
- **Features** — 4 entries
- **UseCases** — 14 entries
- **Integrations** — 10 entries
- **Solutions** — 3 entries
