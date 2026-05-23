# Agent Instructions

This workspace is for future math-learning web modules, starting from the existing notebook [geometri_trigonometri_belajar_smp.ipynb](geometri_trigonometri_belajar_smp.ipynb).

## Working Principles

- Keep the teaching style simple, visual, and friendly for SMP-level learners.
- Prefer Indonesian explanations unless the user asks for another language.
- Preserve the notebook's flow: concept first, then visual example, then short explanation.
- Favor small, self-contained modules over large, tightly coupled implementations.
- Use the existing blue/green visual direction when adding UI or illustration work.

## Implementation Guidance

- Start from the nearest existing lesson, notebook cell, or module before introducing new structure.
- Keep examples concrete and easy to follow; avoid advanced abstractions unless they clearly help the lesson.
- When turning notebook material into web content, keep the narrative and visuals aligned with the original learning sequence.
- Do not add tests unless the user explicitly asks for them.
- Prefer minimal, focused changes over broad refactors.

## Validation

- Verify changes with the narrowest useful check for the touched area.
- If a web module is added later, document any new setup or run steps near the relevant code rather than duplicating them here.
