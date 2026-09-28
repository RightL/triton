# Triton

Triton is an agent skill for creating and maintaining prompts for large language models (LLMs). It keeps the prompt's intent clear and its core small enough for people to understand and maintain.

## Principles

- **Human maintainability:** keep the core brief and add supporting detail only where it helps.
- **Stable intent:** express purposes and desired outcomes clearly so detailed guidance can evolve around them.
- **Targeted iteration:** fix the part responsible for an observed problem while preserving guidance that still works.
- **Adaptability:** adjust supporting guidance to suit the model's capabilities.

## Use

The complete skill is in [SKILL.md](SKILL.md). Add it to your agent's skill library using that agent's installation instructions, or provide the file directly as instructions to an LLM.

Example requests:

> Use Triton to create a prompt for this task: ...

> Use Triton to improve this prompt. The specific problem I observed is: ...

Start new prompts with a concise core. Add supporting detail when observed behavior shows it is needed. When revising a prompt, keep valid wording and higher-level intent stable.
