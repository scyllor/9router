## 9router Guide

9router is an LLM API aggregator. Prioritize product requirements, correctness, and reliability.

### Graphify (Auxiliary)

- For architecture questions, read `graphify-out/GRAPH_REPORT.md` first.
- If present, start from `graphify-out/wiki/index.md`.
- For cross-module relations, prefer:
  - `graphify query "<question>"`
  - `graphify path "<A>" "<B>"`
  - `graphify explain "<concept>"`
- After code changes, run `graphify update .`.

### Priority

1. 9router product/engineering goals
2. Correctness and reliability
3. Graphify convenience

### Language Policy

- All generated/modified files must be in English.
- Conversational explanations about these files should be in Chinese.
