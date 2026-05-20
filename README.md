# Communications (communications)
An index and topic collection covering Communications Platform as a Service (CPaaS) and messaging-and-voice infrastructure APIs. This network gathers providers offering programmable SMS, MMS, voice, video, transactional and marketing email, chat, push notifications, in-app messaging, and deliverability services. It includes leading CPaaS platforms (Twilio, Vonage, MessageBird/Bird, Sinch, Plivo, Bandwidth, Telnyx, Infobip), transactional email providers (SendGrid, Mailgun, Postmark, Resend, SparkPost, Mailjet, MailerSend, Mailtrap), video and real-time platforms (Agora, Daily.co, LiveKit, Zoom, Dolby), push and in-app messaging (OneSignal, Pusher, Ably, PubNub, Sendbird, Airship, CleverTap), and notification orchestration layers (Courier, Knock, Customer.io, Braze, Iterable). It is distinct from the Bots topic, which covers conversational scripting and chatbot frameworks.

**URL:** [https://apievangelist.com](https://apievangelist.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - CPaaS, SMS, MMS, Voice, Email, Push Notifications, Video, Chat, Messaging, Deliverability

## Timestamps

- **Created:** 2026-05-19
- **Modified:** 2026-05-19

## Common Properties

- [Portal](https://apievangelist.com)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - Message Schema](https://raw.githubusercontent.com/api-evangelist/communications/refs/heads/main/json-schema/communications-message-schema.json)
- [JSONSchema - Delivery Receipt Schema](https://raw.githubusercontent.com/api-evangelist/communications/refs/heads/main/json-schema/communications-delivery-receipt-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/communications/refs/heads/main/json-ld/communications-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/communications/refs/heads/main/vocabulary/communications-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Programmable SMS, MMS, and Voice | CPaaS providers expose programmable APIs for sending and receiving SMS and MMS messages, placing and routing voice calls, and managing phone number inventory across the global PSTN. |
| Transactional and Marketing Email | Email APIs handle high-volume transactional sends, marketing campaigns, template rendering, list management, and deliverability monitoring through ESP infrastructure. |
| Real-Time Video and Audio | Video and real-time platforms expose APIs and SDKs for embedding live video calls, broadcasts, conferences, and low-latency audio rooms into applications. |
| Push Notifications and In-App Messaging | Push providers deliver native iOS and Android push notifications, web push, and in-app messages at scale across FCM, APNs, and proprietary delivery infrastructure. |
| Realtime Chat and Pub/Sub | Realtime APIs provide WebSocket-based pub/sub channels, chat rooms, presence, and message history for collaborative and social applications. |
| Notification Orchestration and Multi-Channel Delivery | Orchestration platforms unify SMS, email, push, chat, and in-app channels behind a single API with templating, preference management, and routing logic. |
| Deliverability and Reputation Management | Deliverability tooling covers IP warmup, SPF/DKIM/DMARC, bounce and spam handling, suppression lists, and engagement-based sender reputation analytics. |
| Number Provisioning and Verification | Communications APIs manage phone number purchase, porting, regulatory compliance, and verification flows like one-time passwords and silent network auth. |

## Use Cases

| Name | Description |
|------|-------------|
| Two-Factor Authentication and OTP Delivery | Applications use SMS, voice, and email APIs to deliver one-time passcodes and verification messages for login, signup, and high-risk action confirmation. |
| Transactional Notifications | Platforms send order confirmations, shipping updates, password resets, and account alerts through email, SMS, and push APIs as part of core product workflows. |
| Customer Engagement Campaigns | Marketing teams orchestrate multi-channel email, SMS, and push campaigns using providers like Braze, Iterable, Customer.io, and Klaviyo to drive retention and lifecycle messaging. |
| Live Video and Audio Embeds | Telehealth, education, and collaboration apps embed branded live video and audio experiences using Daily.co, Agora, LiveKit, Zoom SDKs, and Dolby. |
| Contact Center and Programmable Voice | Support and sales teams build programmable IVRs, click-to-call, call tracking, and conversational voice flows on Twilio, Vonage, Dialpad, and RingCentral. |
| Realtime Chat and Social Features | Apps add direct messaging, group chat, presence, and live commenting using Sendbird, Stream, PubNub, Ably, and Pusher. |
| Operational and Incident Alerting | Engineering and SRE teams page on-call staff and broadcast incident status via SMS, voice, push, and email through Knock, Courier, and CPaaS providers. |

## Integrations

| Name | Description |
|------|-------------|
| Twilio | Leading CPaaS provider offering programmable SMS, MMS, voice, video, email (via SendGrid), and verification APIs at global scale. |
| Vonage | CPaaS platform covering SMS, voice, video, verify, and conversation APIs across messaging channels including WhatsApp and Viber. |
| SendGrid | Transactional and marketing email API owned by Twilio, handling high-volume sends, templates, and deliverability. |
| MessageBird | Omnichannel CPaaS provider (Bird) offering SMS, voice, email, WhatsApp, and conversational messaging APIs across global carriers. |
| Sinch | Global CPaaS platform delivering SMS, voice, email (Mailgun, Mailjet), verification, and conversational messaging APIs. |
| OneSignal | Push notification, in-app messaging, email, and SMS platform with a unified messaging API used by mobile and web applications. |
| Sendbird | In-app chat, messaging, and calls API powering customer support and social experiences inside mobile and web applications. |
| Daily.co | WebRTC-based video and audio API for embedding live calls, broadcasts, and recording into web and mobile applications. |
| Mailgun | Transactional email and email validation API focused on deliverability for developers and high-volume senders. |

## Artifacts

Machine-readable definitions for the core entities used across the Communications topic.

### JSON Schema

- [Message Schema](json-schema/communications-message-schema.json)
- [Delivery Receipt Schema](json-schema/communications-delivery-receipt-schema.json)

### JSON Structure

- [Message Structure](json-structure/communications-message-structure.json)
- [Delivery Receipt Structure](json-structure/communications-delivery-receipt-structure.json)

### JSON-LD

- [Communications Context](json-ld/communications-context.jsonld)

## Vocabulary

- [Communications Vocabulary](vocabulary/communications-vocabulary.yaml) — Unified taxonomy of channels, resources, actions, workflows, and personas across CPaaS, email, push, chat, and video providers.

## Network

This index references the following Communications provider repositories:

- [Ably](https://github.com/api-evangelist/ably)
- [Aircall](https://github.com/api-evangelist/aircall)
- [Airship](https://github.com/api-evangelist/airship)
- [Amazon Pinpoint](https://github.com/api-evangelist/amazon-pinpoint)
- [Amazon SES](https://github.com/api-evangelist/amazon-ses)
- [Amazon SNS](https://github.com/api-evangelist/amazon-sns)
- [api.video](https://github.com/api-evangelist/api-video)
- [Bandwidth](https://github.com/api-evangelist/bandwidth)
- [Braze](https://github.com/api-evangelist/braze)
- [CallRail](https://github.com/api-evangelist/callrail)
- [CleverTap](https://github.com/api-evangelist/clevertap)
- [ClickSend SMS](https://github.com/api-evangelist/clicksend-sms)
- [Courier](https://github.com/api-evangelist/courier)
- [Crisp](https://github.com/api-evangelist/crisp)
- [Customer.io](https://github.com/api-evangelist/customer-io)
- [Daily.co](https://github.com/api-evangelist/daily-co)
- [Dialpad](https://github.com/api-evangelist/dialpad)
- [Dolby](https://github.com/api-evangelist/dolby)
- [Iterable](https://github.com/api-evangelist/iterable)
- [JustCall](https://github.com/api-evangelist/justcall)
- [Klaviyo](https://github.com/api-evangelist/klaviyo)
- [Knock](https://github.com/api-evangelist/knock)
- [LiveKit](https://github.com/api-evangelist/livekit)
- [Loops](https://github.com/api-evangelist/loops)
- [Mailchimp](https://github.com/api-evangelist/mailchimp)
- [MailerLite](https://github.com/api-evangelist/mailerlite)
- [MailerSend](https://github.com/api-evangelist/mailersend)
- [Mailgun](https://github.com/api-evangelist/mailgun)
- [Mailjet](https://github.com/api-evangelist/mailjet)
- [Mailtrap](https://github.com/api-evangelist/mailtrap)
- [MessageBird](https://github.com/api-evangelist/messagebird)
- [Mux](https://github.com/api-evangelist/mux)
- [OneSignal](https://github.com/api-evangelist/onesignal)
- [Plivo](https://github.com/api-evangelist/plivo)
- [Postmark](https://github.com/api-evangelist/postmark)
- [PubNub](https://github.com/api-evangelist/pubnub)
- [Pusher](https://github.com/api-evangelist/pusher)
- [Resend](https://github.com/api-evangelist/resend)
- [RingCentral](https://github.com/api-evangelist/ringcentral)
- [Sendbird](https://github.com/api-evangelist/sendbird)
- [SendGrid](https://github.com/api-evangelist/sendgrid)
- [Sinch](https://github.com/api-evangelist/sinch)
- [Stream](https://github.com/api-evangelist/stream-io)
- [Telesign](https://github.com/api-evangelist/telesign)
- [Telnyx](https://github.com/api-evangelist/telnyx)
- [Twilio](https://github.com/api-evangelist/twilio)
- [Vonage](https://github.com/api-evangelist/vonage)
- [Zoom](https://github.com/api-evangelist/zoom)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
