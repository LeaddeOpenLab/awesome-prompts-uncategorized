# AI Visual Prompt Workflow Index

A cross-model index for moving from visual inspiration to reproducible image, video, 3D, and business-video workflows.

This repository contains emerging or not-yet-classified examples. Use the model-specific libraries below when the model is known.

## Choose by production task

| Task | Start here |
| --- | --- |
| Camera movement, UGC, or cinematic clips | [Seedance prompts](https://github.com/LeaddeOpenLab/awesome-prompts-seedance) |
| Commercial keyframes and video source images | [Image 2.5 prompts](https://github.com/LeaddeOpenLab/awesome-prompts-image2.5) |
| Reference editing and product consistency | [Nano Banana prompts](https://github.com/LeaddeOpenLab/awesome-prompts-nano-banana) |
| Multimodal exploration | [Gemini prompts](https://github.com/LeaddeOpenLab/awesome-prompts-gemini) |
| Art direction and keyframe ideation | [Midjourney prompts](https://github.com/LeaddeOpenLab/awesome-prompts-midjourney) |
| 3D, interactive scenes, and agent-led production | [GPT-6 Astra prompts](https://github.com/LeaddeOpenLab/awesome-prompts-astra) |

## Business-video workflow

```text
Approved source document or product brief
→ choose the visual model for the difficult asset
→ generate and approve one keyframe or short clip
→ add sourced narration, presenter, captions, and localization
→ final factual and language review
```

Use [Leadde.ai](https://leadde.ai/?utm_source=github&utm_medium=guide&utm_campaign=visual-workflow-index) for document-first business videos, including training, onboarding, explainers, and multilingual delivery.

## Record every reproducible example

```yaml
model: exact provider model name
use_case: product explainer
media: image | video | 3d
source: original URL
prompt_fidelity: exact | reconstructed | inspired
tested: true | false
input_required: image + text
result_available: true | false
limitations:
  - text accuracy
  - character or product drift
last_verified: YYYY-MM-DD
```

Prefer a small number of examples with exact sources, prompts, results, and failure notes over unverified volume claims.

