# Hyperbolic (hyperbolic)

Hyperbolic Labs is an open-access AI cloud offering on-demand GPU rentals and serverless LLM inference. Hosts 25+ open-source models with OpenAI-compatible chat, vision, image generation (FLUX, Stable Diffusion, LoRA), and audio (Melo TTS) APIs. Reserved-cluster pricing available with 3-12 month commitments and up to 40% discount.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/hyperbolic/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=hyperbolic-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## Tags
- AI, LLM, Inference, GPU, Open Source, Serverless, Image Generation, Audio

## APIs
- **Hyperbolic Serverless Inference API** — OpenAI-compatible chat, vision, image (FLUX/SD/LoRA), audio (Melo TTS). Base URL `https://api.hyperbolic.xyz/v1`. From $0.0001/1K tokens. [Docs](https://docs.hyperbolic.ai/docs/inference/overview)
- **Hyperbolic On-Demand GPU API** — Bare-metal GPU rental with SSH. $1.39-$1.99/hr; reserved clusters with up to 40% discount.

## Plans, Rate Limits, FinOps
- [Plans](plans/hyperbolic-plans-pricing.yml) — PAYG inference + hourly GPU + reserved clusters.
- [RateLimits](rate-limits/hyperbolic-rate-limits.yml) — Service-tier limits documented at docs.hyperbolic.ai.
- [FinOps](finops/hyperbolic-finops.yml) — FOCUS-aligned, billed via Hyperbolic console.

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://hyperbolic.xyz/)
- [Documentation](https://docs.hyperbolic.ai/)

## Notes
- A documented OpenAPI URL exists (`https://docs.hyperbolic.ai/docs/api-reference/openapi.json`) but currently returns "Asset not found"; spec not copied locally.

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
