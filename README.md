# Learn — ChatGPT-native port

This repository contains a ChatGPT-friendly adaptation of the teaching workflow from
`amosblomqvist/learn`.

It keeps the core pedagogy while removing Pi-specific dependencies such as popup extensions,
tmux subagents, and Obsidian logging.

## Invoke it

In a ChatGPT conversation where this repository is available through the GitHub connector, use:

```
learn: <topic or question>
```

Examples:

```
learn: teach me how TCP achieves reliability
learn: help me understand derivatives from first principles
learn: explain transformers at my current level
```

The canonical behavior is defined in `SKILL.md`.

## Teaching contract

The adapted workflow is:

1. **Probe** — identify what you already know and the exact goal.
2. **Plan** — show the dependency path from foundational facts to the target idea.
3. **Teach** — build one concept at a time, explicitly connecting each new idea to prior ones.
4. **Check** — use short questions to confirm each important concept landed.
5. **Verify** — use current sources when factual accuracy is uncertain or time-sensitive.
6. **Visualize when useful** — use Mermaid or a compact diagram only when structure is clearer visually.

The focus is understanding and derivation, not memorization.

## Upstream

Inspired by: https://github.com/amosblomqvist/learn

This is an independent ChatGPT-oriented adaptation, not a verbatim copy of the upstream Pi configuration.
