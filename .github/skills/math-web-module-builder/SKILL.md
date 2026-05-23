---
name: math-web-module-builder
description: "Use when creating a web-based learning module for math or physics topics, especially when the request asks for visualizations, comprehensive explanations, SMP-friendly language, a dedicated folder per topic, and a root index.html that links into the module."
---

# Math Web Module Builder

Use this skill when the task is to turn a math or physics topic into a web learning module.

## Goal

Create a clear, visual, SMP-friendly module that explains the topic step by step and keeps the project easy to extend.

## Workflow

1. Identify the topic and convert it into a clean folder name.
2. Create one folder per topic or materi.
3. Put the module entry point at `index.html` inside that folder.
4. Keep supporting assets, scripts, and styles inside the same module folder unless there is a strong reason to share them.
5. Update the project root `index.html` so it links to the new module.
6. Write the explanation in Indonesian unless the user asks otherwise.
7. Explain the concept like speaking to an SMP student: simple language, concrete examples, and visual reasoning.
8. Add visualizations, diagrams, or interactive elements whenever they help the lesson.
9. Include at least one pragmatic use case for the topic so the student can see where the idea is used in real life.
10. When the topic supports it, turn the use case into an interactive scene, such as a draggable graph, slider-based demo, step-by-step geometry sketch, or a trigonometry scene for measuring the height of a building or tree.
11. If a library or dependency will make the visualization or interaction clearer, richer, or easier to maintain, use it and install it when needed.

## Structure Rules

- Use one folder per materi, named after the topic.
- Keep each module self-contained.
- Make `index.html` the root file for that module.
- Treat the project root `index.html` as the navigation hub for all modules.
- Prefer modular, easy-to-read files over a large monolithic page.
- Prefer browser-friendly and lightweight libraries when they are enough for the lesson.
- Choose the simplest tool that still gives the student a clear visual or interactive experience.

## Content Rules

- Start from intuition before formulas.
- Show why a formula makes sense, not just the result.
- Keep the tone patient, friendly, and teaching-oriented.
- Use visuals to support the explanation, not to decorate it.
- Keep examples concrete and small enough for SMP learners to follow.
- Prefer a real-world example first, then show the abstract rule it explains.
- If an interaction can help the student explore the idea, build it instead of leaving the lesson static.
- If a library will make the lesson more informative or more interactive, do not avoid it just to keep the implementation plain.

## Quality Check

- The module folder name matches the topic.
- The module has its own `index.html`.
- The root `index.html` links to the module.
- The explanation is understandable for SMP level.
- The visuals and text support the same learning sequence.
- The module includes at least one practical example or scenario.
- Any interactive visualization clearly helps the student inspect or test the concept.
- If a library was introduced, it has a clear teaching purpose and is not added just for decoration.

## When To Reuse

Use this skill again whenever a new topic needs its own web-based learning module, especially for geometry, trigonometry, algebra, or introductory physics.
