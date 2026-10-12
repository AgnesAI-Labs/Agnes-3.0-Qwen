# Agnes-3.0-Qwen

Official GitHub landing page for **Agnes-3.0-Qwen**, an open-weight multimodal reasoning model from Agnes AI. The complete checkpoint and authoritative model card are hosted on Hugging Face:

**[Model card, weights, and files — Agnes-AI/Agnes-3.0-Qwen](https://huggingface.co/Agnes-AI/Agnes-3.0-Qwen)**

This GitHub repository provides a concise discovery and documentation entry point. It does **not** mirror the approximately 360 GB BF16 checkpoint. For the latest files, setup instructions, and usage conditions, follow the Hugging Face release.

## Model at a glance

| Property | Published model-card information |
| --- | --- |
| Base model | [Qwen3.8-Flash-Next](https://huggingface.co/Qwen/Qwen3.8-Flash-Next), further post-trained by Agnes AI |
| Architecture | Hybrid-attention Mixture-of-Experts; approximately 180B total parameters, 512 experts, 10 active per token |
| Context window | 1,048,576 tokens |
| Maximum output | 65,536 tokens |
| Inputs / output | Text, image, and video / text |
| Languages | English and Chinese |
| Checkpoint precision | BF16 |
| License | [Qwen Community License 1.0](https://huggingface.co/Agnes-AI/Agnes-3.0-Qwen/blob/main/LICENSE) |

The model card describes reasoning-effort controls, tool calling, streaming, and OpenAI-compatible API usage. Its benchmark figures are self-reported and the cross-model comparison draws on public reports; see the model card for the evaluation notes rather than treating the table as a controlled head-to-head result.

## Get started

- [Open-weight checkpoint and full model card](https://huggingface.co/Agnes-AI/Agnes-3.0-Qwen)
- [Local deployment and API examples](https://huggingface.co/Agnes-AI/Agnes-3.0-Qwen#quickstart)
- [Agnes API documentation](https://wiki.agnes-ai.com/en/docs/agnes-30-qwen)

The published local-deployment guidance uses eight-GPU tensor parallelism and recommends roughly 500 GB of free fast storage for weights and cache. Check the current model card and your serving stack before allocating hardware.

## License and release scope

These weights are **not** Apache-2.0 licensed. They are a derivative release under the [Qwen Community License 1.0](https://huggingface.co/Agnes-AI/Agnes-3.0-Qwen/blob/main/LICENSE), with an accompanying [NOTICE](https://huggingface.co/Agnes-AI/Agnes-3.0-Qwen/blob/main/NOTICE). Read the full terms before use or redistribution; the model card summarizes additional commercial-use conditions. This repository does not grant separate rights to the model or upstream artifacts.

Source checked against Hugging Face model revision [`42cff3b`](https://huggingface.co/Agnes-AI/Agnes-3.0-Qwen/tree/42cff3b81955e68c5e6c308b1fb8a59b6229f416) on October 12, 2026. The Hugging Face model card remains the source of truth for later updates.
