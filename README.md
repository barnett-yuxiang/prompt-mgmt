# Prompt Magnet

A personal collection of prompts, templates, and strategies for using large
language models (LLMs) effectively.

The repository is organized along two axes:

- **Vendor / tool directories** — material that is specific to a particular
  model or product (e.g. `openai/`, `gemini/`, `cursor/`).
- **`general/`** — model-agnostic prompts and techniques, grouped by purpose.

## Structure

```text
.
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

## Vendor / tool directories

### `cursor/`

Notes and configuration for the Cursor AI editor — how context, rules, and MCP
work, plus a set of custom coding rules.

### `gemini/`

Prompts and templates tailored to Google Gemini models.

### `midjourney/`

Reusable prompt templates for generating images with Midjourney.

### `openai/`

Prompts, reusable templates, and field notes for OpenAI models — including an
image-generation template and directive-style prompts such as the reality
filter used to reduce hallucinations.

### `qodo/`

Prompts and notes for Qodo, focused on code embedding, retrieval, and
repository-aware code assistance.

## `general/`

Model-agnostic material, grouped by purpose.

### `benchmark/`

Tasks and problem sets used to evaluate and compare the performance of
different LLMs (reasoning, coding, and knowledge questions).

### `best-practices/`

Guidelines and recommendations for writing effective prompts and getting the
most out of LLMs.

### `daily-use/`

Ready-to-use prompts and examples for everyday tasks and workflows.

### `exploration/`

A space for experimenting with novel prompt-engineering techniques and probing
the capabilities of different models.

### `methods/`

Explanations of prompting methods such as Chain-of-Thought and ReAct, and when
to use them.

### `thinking/`

Everything related to reasoning and cognition, kept together as one theme:

- **Thinking frameworks (for humans)** — mental models and clear-thinking
  write-ups such as first principles, the golden circle, and the pyramid
  principle.
- **Reasoning / persona prompts (for models)** — prompt patterns that make a
  model reason more deeply or adopt a top-expert persona (for example, a
  "summon an expert" style prompt).

As this directory grows it can be split further, e.g. `thinking/mental-models/`
for the human-oriented frameworks and `thinking/personas/` for the role /
persona prompts.
