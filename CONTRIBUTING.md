# Contributing

Thanks for helping maintain this list. Please keep entries focused on long-horizon robot manipulation rather than general robot learning.

## What Belongs Here

Good fits include:

- Methods that explicitly model long-horizon structure, memory, progress, failure detection, recovery, task graphs, or world-model foresight.
- Benchmarks or datasets with sequential instructions, long-horizon household tasks, memory-dependent evaluation, recovery protocols, or cross-embodiment robot data useful for VLA training.
- Survey papers, project pages, code releases, or resource lists directly relevant to long-horizon manipulation.

Less suitable entries include:

- Pure grasping or single-step manipulation without long-horizon evaluation.
- Navigation-only work without manipulation.
- General VLM/LLM papers without an embodied manipulation interface.

## Entry Format

For README entries, use:

```markdown
- [Name](URL) - one concise sentence explaining why it matters.
```

For `resources.csv`, fill:

```csv
name,year,category,type,venue,url,mechanism_tags,benchmark_tags,notes
```

Preferred mechanism tags:

- `planning`
- `skill abstraction`
- `language`
- `VLA`
- `diffusion`
- `flow matching`
- `memory`
- `progress`
- `verification`
- `replanning`
- `world model`
- `household`
- `cross embodiment`
- `real robot`

## Quality Rules

- Prefer official paper, project, dataset, or code URLs.
- Include arXiv links for preprints.
- Do not report benchmark numbers unless they are directly stated by the original paper.
- Mark cross-paper performance comparisons as non-comparable unless the same benchmark protocol and split are used.
