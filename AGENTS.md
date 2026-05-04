## Graphify Knowledge Graph Guide

This repository includes a Graphify-generated knowledge graph in `graphify-out/`.

### Purpose

Use Graphify as the primary navigation layer for architecture understanding, cross-module reasoning, and codebase relationship analysis.

### Required Workflow

1. Before answering architecture or codebase-structure questions, read `graphify-out/GRAPH_REPORT.md` first to identify community structure and high-centrality nodes.
2. If `graphify-out/wiki/index.md` exists, use it as the primary entry point instead of reading raw source files first.
3. For cross-module relationship questions (for example, "How does X relate to Y?"), prefer graph traversal commands over text search:
   - `graphify query "<question>"`
   - `graphify path "<A>" "<B>"`
   - `graphify explain "<concept>"`
4. After modifying any code file in the current session, run:

```bash
graphify update .
```

This refreshes the graph using AST updates only and does not incur API cost.

### Language and Communication Policy

- All generated or modified documentation and files must be written in English.
- Conversational explanations, reviews, and interactive guidance related to these files should be provided in Chinese.
- Preserve technical terminology accuracy when switching interaction language.

### Quality Standard

Documentation updates should follow professional technical writing standards:

- Clear structure and sectioning
- Unambiguous instructions
- Actionable command examples
- Terminology consistency for both technical and non-technical audiences
