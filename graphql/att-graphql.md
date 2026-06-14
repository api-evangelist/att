# AT&T GraphQL Schema

## Overview

This conceptual GraphQL schema models the AT&T telecommunications and network services platform, covering wireless accounts, device management, voice and messaging services, data usage, billing, network infrastructure, IoT connectivity, and enterprise offerings.

AT&T provides API access to developers through its Developer Portal at https://developer.att.com/, exposing capabilities across wireless, broadband, FirstNet, and business networking domains.

## Domain Coverage

### Account and Subscriber Management

- **Account** — top-level billing and service account for a customer
- **AccountProfile** — contact details, preferences, and identity for an account holder
- **Subscriber** — an individual line or service user under an account
- **PhoneNumber** / **MSISDN** — the assigned number and mobile subscriber identifier
- **IMEI** — device hardware identifier tied to a subscriber

### Device and SIM

- **Device** — a physical handset or connected device on the network
- **SIMCard** — the SIM associated with a subscriber and device
- **IoTDevice** — a connected IoT endpoint (sensor, tracker, asset tag)
- **IoTSIM** — a SIM provisioned for IoT or machine-to-machine use
- **FleetSIM** — a SIM used in fleet or transportation management
- **ConnectedCar** — automotive connectivity profile with telematics

### Plans and Features

- **Plan** — a base service plan for a subscriber
- **ServicePlan** — a configured plan combining voice, data, and messaging tiers
- **DataPlan** — the data allocation component of a plan
- **VoicePlan** — voice minutes and calling allowances
- **MessagePlan** — SMS/MMS messaging allocations
- **AddOn** — optional service additions to a base plan
- **Feature** — a specific capability enabled on an account or line
- **EnterprisePlan** — a group or corporate service plan with shared pools

### Voice Services

- **VoiceCall** — a live or completed voice call event
- **CallRecord** — a stored summary of a completed call
- **CallDetail** — itemized call data including duration, cost, and parties
- **Voicemail** — a voicemail message left for a subscriber
- **VoicemailGreeting** — the recorded greeting for a subscriber's mailbox
- **CallForwarding** — rules for redirecting incoming calls
- **CallerId** — caller identification settings and data
- **Conference** — a multi-party audio conference session
- **ConferenceCall** — a specific conference call instance
- **Participant** — an individual party in a conference call

### Messaging Services

- **SMS** — a short message service text
- **MMSMessage** — a multimedia message with attachments
- **MessageThread** — a conversation thread grouping messages
- **MessageAttachment** — a media file or document attached to an MMS

### Data and Roaming

- **DataSession** — an active or historical mobile data session
- **DataUsage** — consumed data metrics for a period or session
- **DataBalance** — remaining data allowance on a plan
- **RoamingProfile** — roaming configuration for international use
- **RoamingZone** — a geographic zone with specific roaming rates
- **InternationalData** — international data add-on or usage record
- **InternationalCall** — a call made to or from an international number

### Network Infrastructure

- **NetworkService** — a logical network service instance
- **NetworkSlice** — a 5G network slice with dedicated QoS parameters
- **FiveG** — 5G service availability and capability for a subscriber
- **LTE** — LTE connectivity profile and signal data
- **Band** — a radio frequency band in use or available
- **Tower** — a cell tower with location and coverage data
- **CoverageArea** — a geographic region with defined network coverage
- **NetworkEvent** — a logged network incident, outage, or status change

### Location Services

- **Location** — a geographic location point (lat/lon)
- **Geofence** — a defined geographic boundary for alerts or tracking

### Number Portability

- **NumberPorting** — a number porting transaction
- **PortRequest** — a submitted request to port a number in or out

### Billing and Payments

- **Invoice** — a billing statement for an account period
- **BillingPeriod** — the date range covered by a billing cycle
- **Charge** — an individual charge item on an invoice
- **Payment** — a payment transaction applied to an account
- **PaymentMethod** — a stored payment instrument (card, bank, autopay)
- **Contract** — a service agreement with terms and commitment period
- **EquipmentInstallment** — an installment plan for device financing

### Device Programs

- **DeviceUpgrade** — an upgrade eligibility and transaction record
- **TradeIn** — a device trade-in assessment and credit

### Customer Support

- **CustomerService** — a customer service interaction record
- **SupportTicket** — a logged support case or trouble ticket

### FirstNet

- **FirstNet** — FirstNet public safety broadband account or service

### Security and Access

- **APIKey** — an API credential key for developer access
- **Token** — an OAuth or session token for authenticated API calls

## GraphQL Capabilities

The schema supports:

- Querying account, subscriber, device, and plan data
- Retrieving call records, usage history, and billing details
- Managing voicemail, call forwarding, and messaging preferences
- Accessing network coverage, tower, and slice information
- Tracking IoT device status and fleet SIM assignments
- Initiating number porting and device upgrade requests
- Managing roaming profiles and international service add-ons

## Reference

- Developer Portal: https://developer.att.com/
- AT&T Website: https://www.att.com/
- GitHub: https://github.com/att
