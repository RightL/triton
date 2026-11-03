# Triton

Triton is an agent skill for creating and maintaining prompts for large language models (LLMs). It keeps prompts brief and supports stable intent, targeted iteration, and adaptation across models.

## Principles

- **Human maintainability:** keep the prompt brief enough to understand, review, and maintain as a whole.
- **Stable intent:** some parts should remain stable or change less often as the prompt evolves.
- **Targeted iteration:** fix the part responsible for an observed problem while preserving guidance that still works.
- **Adaptability:** keep coupling low so instructions can be added, removed, or replaced for different models without reworking unrelated parts.

## Use

The complete skill is in [SKILL.md](SKILL.md). Add it to your agent's skill library using that agent's installation instructions, or provide the file directly as instructions to an LLM.

Example requests:

> Use Triton to create a prompt for this task: ...

> Use Triton to improve this prompt. The specific problem I observed is: ...

Triton strongly recommends highlighting stable or essential guidance through suitable formatting or structure. Preserve wording that already serves its purpose.
