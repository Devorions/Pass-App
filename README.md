# PASS — Smart Proximity-Based Connection App

PASS helps people connect instantly with others nearby without phone numbers or awkward introductions.
Using a radar-based discovery model, PASS enables secure, consent-driven connections while giving users full control over what they share and when they share it.

PASS is a modern, privacy-first mobile application designed for real-world, moment-based interactions without exposing personal contact details upfront.

---

## Problem Statement

In real-world environments, people often want to connect but hesitate due to:

- Awkwardness in asking for phone numbers
- Privacy risks associated with sharing personal information upfront
- Existing social platforms relying on usernames, numbers, or public profiles
- The lack of a simple way to connect only with nearby people, in the moment

---

## Solution

PASS introduces a radar-based proximity system that allows users to discover nearby PASS users within an approximate range of around 100 meters and initiate secure connection requests without revealing personal information.

Connections are established only after both users explicitly accept, ensuring privacy, consent, and user control at every step.

---

## Core Features

### Smart Radar Discovery

- Discovers nearby PASS users within an approximate 100-meter range
- No public profiles or searchable usernames
- Visibility is session-based and temporary
- Precise location data is never displayed or stored

---

### Privacy-First Connections

- No phone numbers required
- No email or personal identifiers shared by default
- Users control what information is shared and when
- Location signals are processed ephemerally for discovery only

---

### Consent-Based Requests

- Users can initiate connection requests with nearby users
- Requests must be explicitly accepted or rejected
- Limited profile data is shared only after mutual consent

---

### Real-Time Interaction

- Live radar updates during discovery
- Instant delivery of connection requests and responses
- Low-latency, session-scoped interactions

---

### User Control

- Users can enable or disable discoverability at any time
- Connections can be revoked by either party
- Full control over shared data and active sessions

---

## Architecture Overview

A detailed system design and component breakdown is available in  
[`docs/architecture.md`](docs/architecture.md).

---
## Use Cases

- Campus and university networking
- Events, meetups, and conferences
- Co-working spaces
- Casual social discovery
- Professional introductions without pressure

---


## Platform Support

- Android (Play Store ready)
- iOS (planned and supported)

---

## Product Demo

See the demo video here:  

[`View The Video`](https://github.com/Devorions/Pass-App/issues/1)
[`demo/pass-interaction-demo.mp4`](demo/pass-interaction-demo.mp4)