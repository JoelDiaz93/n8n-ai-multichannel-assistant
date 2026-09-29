# AI Multichannel Assistant — Architecture

## Purpose

Multimodal customer assistant for WhatsApp and Telegram using n8n, LLM agents, conversational memory, image analysis, speech transcription and text-to-speech.

## Design principles

- Keep n8n focused on orchestration.
- Isolate external integrations behind explicit nodes/tools.
- Keep credentials outside exported workflows.
- Make mutations explicit and auditable.
- Prefer deterministic validation for authorization and business rules.
- Add retries, idempotency and observability before production use.
