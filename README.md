# zeuz — factory of agentic workflow systems

**Zeuz** is a factory: from an idea it births a complete agentic workflow system of the Femida/Mnemozina class. It runs the spec through six inventor-masters (Russian scientists, role = character) and bakes a constitution into every system it produces.

## Why

Building a multi-agent system by hand is slow and easy to get wrong: one step skips the gate before an irreversible action, another burns tokens where Haiku would do, a third leaves a hole in coverage. Zeuz takes that off your plate. You bring an idea — it interrogates it into a full spec, casts the roles, draws the architecture with gates, budgets the tokens, writes the files, and tests the result before handoff. What you get is a working system under one constitution, not a pile of loose prompts.

Who it's for: anyone building not a single workflow but a family of them, who wants every new system born to the same standard — observability, replay, and control over irreversible actions baked in.

## Flow

```
"need a new workflow/system"
   → Stage 0: Lobachevsky + /grill-me  (spec: goal · input+volume · completeness invariant · constraints)
   → Workflow({ name: 'zeuz-pipeline', args: spec })
       0 Observe (abtop, CTX gate) → 1 Markov (cast souls) → 2 Shukhov (architecture + gates)
       → 3 Kotelnikov (token economy + model-per-function) → 4 DAG artifact
       → 5 Lebedev (write files) → 6 Zvorykin (test → verdict)
   → Zeuz: Graphify (if knowledge) · mirror Codex+VPS · deliver
```

## Layout (Athena schema)

| Path | What |
|---|---|
| `CLAUDE.md` | thin router: map, autostart, conventions |
| `rules/best-practices.md` | **constitution** — baked into every birthed system |
| `specs/00-roadmap.md` | factory flow + team (read first) |
| `agents/*.md` | 6 master souls + `zeuz.md` overseer |
| `workflows/zeuz-pipeline.js` | active workflow with code-enforced gates |
| `docs/decisions/` | ADRs |
| `smoke/smoke.sh` | gate: `node --check` + grep invariants |
| `runs/` | runtime (observability, DAG; gitignored) |

## Gate

```bash
smoke/smoke.sh   # node --check pipeline + grep gates/observability/souls/schema
```

See [README.ru.md](README.ru.md) for the Russian version.
