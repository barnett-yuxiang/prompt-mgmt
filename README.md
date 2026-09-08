# Prompt Magnet

A personal collection of prompts, templates, and strategies for using large
language models (LLMs) effectively.

The repository is organized along two axes:

- **Active directories** — actively maintained prompt collections, grouped by
  purpose (e.g. `image/`).
- **`legacy/`** — earlier vendor- and tool-specific material kept for
  reference (e.g. `openai/`, `gemini/`, `cursor/`).

## Structure

```text
.
├── image/        # Image-generation / photo-editing / style-transfer prompts
└── legacy/       # Archived vendor- and tool-specific collections
    ├── cursor/       # Notes and custom rules for the Cursor AI editor
    ├── gemini/       # Prompts specific to Google Gemini models
    ├── midjourney/   # Midjourney image-generation prompt templates
    ├── openai/       # Prompts, templates, and notes for OpenAI models
    ├── qodo/         # Prompts and notes for Qodo (code AI)
    └── general/      # Model-agnostic prompts and techniques
        ├── benchmark/        # Tasks for evaluating and comparing models
        ├── best-practices/   # Guidelines for writing effective prompts
        ├── daily-use/        # Ready-to-use prompts for everyday tasks
        ├── exploration/      # Experiments with new techniques and models
        ├── methods/          # Prompting methods (Chain-of-Thought, ReAct, ...)
        └── thinking/         # Thinking frameworks and reasoning/persona prompts
```

## `image/`

Prompts for image generation, photo editing, and restyling — including travel
posters, watercolor art prints, realistic portraits, and photo restoration.

- [旅行海报生成](image/旅行海报生成.md) — Generate travel posters from a location name.
- [照片艺术化风格转换](image/照片艺术化风格转换.md) — Restyle photos as posters, watercolor prints, or painted portraits.
- [写实人像摄影与修图](image/写实人像摄影与修图.md) — Prompts for realistic portraits, scene changes, and old-photo restoration.

## `legacy/`

Archived material from the previous repository layout, kept for reference.

### Vendor / tool directories

- **`cursor/`** — Notes and configuration for the Cursor AI editor — how
  context, rules, and MCP work, plus a set of custom coding rules.
- **`gemini/`** — Prompts and templates tailored to Google Gemini models.
- **`midjourney/`** — Reusable prompt templates for generating images with
  Midjourney.
- **`openai/`** — Prompts, reusable templates, and field notes for OpenAI
  models — including an image-generation template and directive-style prompts
  such as the reality filter used to reduce hallucinations.
- **`qodo/`** — Prompts and notes for Qodo, focused on code embedding,
  retrieval, and repository-aware code assistance.

### `general/`

Model-agnostic material, grouped by purpose:

- **`benchmark/`** — Tasks and problem sets used to evaluate and compare the
  performance of different LLMs (reasoning, coding, and knowledge questions).
- **`best-practices/`** — Guidelines and recommendations for writing effective
  prompts and getting the most out of LLMs.
- **`daily-use/`** — Ready-to-use prompts and examples for everyday tasks and
  workflows.
- **`exploration/`** — Experiments with novel prompt-engineering techniques and
  probing the capabilities of different models.
- **`methods/`** — Explanations of prompting methods such as Chain-of-Thought
  and ReAct, and when to use them.
- **`thinking/`** — Thinking frameworks for humans (first principles, the
  golden circle, the pyramid principle) and reasoning / persona prompts for
  models.
