### Hi, I'm Chunxiao Wang

Solo developer building **[nautilus-compass](https://github.com/chunxiaoxx/nautilus-compass)** — a local-first memory layer for AI agents.

- **Zero LLM calls at write time.** Verbatim storage + local BGE-m3 embedding; all intelligence lives at read time (utterance-type routing, hybrid BM25/dense retrieval, date anchoring).
- **Sealed benchmarks.** Every number ships as a signed, byte-recomputable evidence pack — [verify without trusting us](https://github.com/chunxiaoxx/nautilus-compass/blob/main/docs/REPRODUCIBILITY_WALL.md).
- Head-to-head vs mem0 2.0.19 on LongMemEval-S (full 500, same questions & criteria): retrieval **P@1 0.890 vs 0.774**.
- Also: pre-action drift detection (AUC 0.83, p95 <50ms) and cross-agent contract tracking.

130 days, 771 commits — most of them landed by my own agent fleet. The tool is its own best demo.

**Get it**: `pip install nautilus-compass` | [hosted open beta](https://compass.nautilus.social)
