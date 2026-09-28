---
name: triton
description: Create and maintain effective LLM prompts for human maintainability, stable intent, targeted iteration, and adaptability across LLM capabilities.
---

# Triton

## Stable core

Create and maintain prompts that help LLMs achieve the user's intended
results, with these qualities:

1. **Human maintainability.** The core is the focus of human maintenance
   and stays brief enough to understand, review, and maintain as a whole.
   The same applies to each module core.
   Additional guidance should not make its meaning and consistency
   unmanageable.

2. **Stable intent.** Higher-level expressions change less often
   as the prompt evolves. The higher the level, the more accurately
   it must express the underlying intent, allowing detailed guidance
   to evolve around a stable foundation.
   Express purposes clearly enough for capable LLMs to infer suitable
   action.

3. **Targeted iteration.** When an LLM misbehaves under an existing
   prompt, improvements can be made at the appropriate level while
   keeping higher-level content stable where it remains valid.

4. **Adaptability across LLM capabilities.** Different LLMs may need
   different amounts or kinds of guidance. Adaptation may involve
   changing or omitting supporting guidance rather than redesigning
   the whole prompt.

## Supporting detail

This file itself is an example of the structure described below.

### Organization

#### Core

Use a short stable core with supporting detail only where useful.
A supporting part may have its own core and further detail.
Named modules are optional. Make roles and relationships clear;
no fixed heading format is required.

Keep necessary requirements available when optional material is omitted.

### Creating a new prompt

Generally, start a new prompt with only its core. Use the prompt and
observe the LLM's behavior and results before adding supporting detail.
Add supporting detail to address a specific misbehavior or unsatisfactory
result, and keep it focused on that observed need.

### How to write a core

When purpose, desired outcomes, and desired qualities sufficiently express
the intent, prefer expressing the core through them. This gives capable
LLMs room to choose suitable actions.

More specific instructions help where important requirements would
otherwise be unclear.

### Revising an existing prompt

#### Core

Improve an existing prompt at the level and location appropriate to
the issue, while keeping valid guidance elsewhere stable. Do not revise
the stable core, local cores, and supporting detail together by default.
Update other parts only when the change affects their meaning or
consistency.

Preserve wording that already serves its purpose; make local edits for
identifiable improvements rather than restating unchanged meaning.
