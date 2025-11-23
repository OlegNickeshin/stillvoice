# StillVoice — Architectural Diagrams

This document provides visual representations of the StillVoice system structure without exposing operational code or sensitive infrastructure.

---

## High-Level System Flow
User (Browser)
|
v
Client Interface
|
v
Session Layer
|
v
Ethical Gate + Rate Limiter
|
v
Dialogue Engine (LLM Core)
|
v
Soft Memory Layer
|
v
Response Filter
|
v
Rendered Output
Key properties:
- No direct emotional profiling
- No hard identity dependency
- All responses pass ethical moderation layer

---

## Data Responsibility Flow
User Input
|
v
Temporary Context Buffer
|
v
Short Summary Memory (Optional)
|
v
Response Generation
|
v
Context Expiry

This ensures:
- Emotional data is not stockpiled
- Narrative ownership does not occur
- Memory fades unless explicitly allowed

---

## Scripture Parallel System

Dialogue System <——> Scripture Panel

Two independent spaces
No hierarchy
No coercion
No override

Scripture exists as co-presence, not authority.

---

## Attention & Load Governance

Request
|
v
Rate Gate
|
v
Queue Controller
|
v
Dialogue Engine
|
v
Stability Monitor

When overload risk detected:
- Priority shifts to silence
- Responses slow
- System breathes

---

## Ethical Boundary Layer

User Expression
|
v
Ethical Filter
|
v
Response Construct
|
v
Safety Confirmation

This boundary ensures:
- No manipulation
- No emotional escalation mechanics
- No dependency loops

---

## Summary

StillVoice architecture is decentralised in power, but unified in ethic.

It does not seek performance.
It seeks coherence.

System design is guided not by efficiency alone,
but by moral geometry.
