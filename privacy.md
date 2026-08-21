---
layout: default
title: Privacy Policy
---

# Privacy Policy

Last updated: August 21, 2026

**What Went Wrong?** (“WWW”) is an independent product and is not affiliated
with or endorsed by the AI providers referenced in it.

## No account or sign-in

The app does not require an account. During onboarding, you may enter a first
name, nickname, or username so the app can address you. That name is stored on
your device only. It is not included in requests to OpenAI, analytics, or
payment systems. We do not ask for your email address or phone number and do
not create an account profile.

## What is sent when you use the AI feature

When you submit a case for diagnosis, WWW sends the following through our
secure server relay to OpenAI:

- the goal and instructions you enter;
- the AI result and your description of what went wrong;
- any screenshot you choose to attach;
- relevant work preferences and observations saved in WWW memory; and
- later retry results or chat messages you choose to send about that case.

This information is used only to provide the diagnosis, comparison, or
case-related answer you requested. Your local display name is not sent.

Please do not include confidential information or personal information that
is not needed for the diagnosis. Do not submit a case if you do not want its
contents processed by OpenAI.

## What we keep on our own servers

We keep the case so the diagnosis gets better over time: what you entered, the
AI result you pasted, the diagnosis produced, and how you rate each fix. Chat
messages and screenshots are not kept.

It is held in a private database hosted by Supabase, keyed by the one-way
installation hash described below rather than by any account or name, and kept
until you delete it.

## Service providers and retention

Our server relay is hosted by Netlify. It processes requests and standard
network metadata needed to deliver and protect the service. Supabase hosts the
database described above.

OpenAI processes the content to generate the requested response. API response
storage is disabled in our request. OpenAI states that API data is not used to
train its models by default, although abuse-monitoring logs may be retained for
up to 30 days under its [API data controls](https://platform.openai.com/docs/guides/your-data).

The app sends a one-way hash derived from a random installation identifier for
abuse prevention. It is not your Apple ID, advertising identifier, name, or
account ID. Deleting the app removes the identifier from your device.

Our service providers are required to handle data consistently with their
applicable terms, privacy commitments, and protections at least equal to those
described here.

## Analytics

WWW sends a small set of product events to PostHog: which steps you reach, how
many cases you run, which verdict came back, whether a fix helped, and whether
a purchase completed. These are counts and fixed choices. No text you typed, no
case content, and no screenshot reaches the analytics provider. Events carry a
random identifier created on your device — not your Apple ID, your name, or an
advertising identifier.

## What stays on your device

Your display name, case history, drafts, and WWW memory are stored on your
device and read from there. They are not synchronized to an account, and the
server copy described above is never sent back to the app. Relevant memory
excerpts are sent to OpenAI only when you submit an AI request.

You can review and remove individual memory items in the app.

## Deleting your data

- **Delete a case** removes it from your device and from our servers.
- **Reset app data** removes everything from that installation from our
  servers, along with your cases, memory, and onboarding answers on the device.

Both work offline; the request is sent the next time the app can reach us.
Deleting the app also removes the identifier those requests need, so delete
your cases or reset first if you want the stored copy gone.

## Your choices

The AI diagnosis cannot be produced without sending the submitted case to
OpenAI. You can avoid this processing by not submitting a case. Deleting your
data does not recall content already processed by OpenAI for a request.

For privacy or deletion questions, contact us at the address below.

## Payments

Subscriptions are processed by Apple. We do not receive or store your payment
card details. Apple provides the app with the subscription status needed to
unlock paid features.

## What we do not do

- No advertising
- No cross-app or cross-site tracking
- No sale of personal data

## Children

The app is not intended for children under 13.

## Changes

If this policy changes, the updated version will be posted on this page with a
new date.

## Contact

**eymnshln@icloud.com**
