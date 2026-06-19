# zeuz — factory of agentic workflow systems

**Zeuz** is a factory: from an idea it births a complete agentic workflow system of the Femida/Mnemozina class. It runs the spec through six inventor-masters (Russian scientists, role = character) and bakes a constitution into every system it produces.

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
