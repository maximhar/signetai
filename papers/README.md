# Signet Papers

Research papers, formal analyses, and foundational theory documents for the Signet project.

---

## Academic Research

| File | Description | Status |
|------|-------------|--------|
| [RESEARCH-PAPER-OUTLINE.md](./RESEARCH-PAPER-OUTLINE.md) | Formal academic paper: *"Structured Traversal Over Knowledge Graphs as a Retrieval Floor for LLM Agent Memory"* — targeting EMNLP 2026 / NeurIPS workshop | Collecting data |
| [RESEARCH-LCM-ACP.md](./RESEARCH-LCM-ACP.md) | Research notes on Lossless Context Management (LCM), acpx (Agent Client Protocol CLI), and lossless-claw. Includes Volt benchmark results vs Claude Code across context lengths. | Complete |
| [RESEARCH-GITNEXUS-PATTERNS.md](./RESEARCH-GITNEXUS-PATTERNS.md) | Engineering pattern analysis from GitNexus (code intelligence system) — 9 patterns adapted for Signet's knowledge architecture. | Complete |

---

## Core Theory & Architecture

| File | Description |
|------|-------------|
| [VISION.md](./VISION.md) | The Signet thesis — what Signet is 6 months from now, its core purpose, and why it matters |
| [IDEAL-SIGNET.md](./IDEAL-SIGNET.md) | End-to-end monolithic engineering specification for the ideal Signet system — the implementation contract |
| [KNOWLEDGE-ARCHITECTURE.md](./KNOWLEDGE-ARCHITECTURE.md) | How Signet turns experience into understanding — entity/aspect/attribute hierarchy, knowledge lifecycle, structural retrieval theory |
| [KNOWLEDGE-GRAPH.md](./KNOWLEDGE-GRAPH.md) | Knowledge graph schema, traversal design, entity relationship modeling |

---

## Applied Research

| File | Description |
|------|-------------|
| [LCM-PATTERNS.md](./LCM-PATTERNS.md) | Five LCM patterns adapted for Signet's memory architecture (derived from RESEARCH-LCM-ACP) |
| [ACP-INTEGRATION.md](./ACP-INTEGRATION.md) | Phased integration plan for acpx and Agent Client Protocol (derived from RESEARCH-LCM-ACP) |
| [DESIRE-PATHS.md](./DESIRE-PATHS.md) | Desire Paths — learned traversal topology and the exploration/exploitation mechanism |
| [PROCEDURAL-MEMORY.md](./PROCEDURAL-MEMORY.md) | Procedural memory design — how Signet encodes repeatable workflows and agent behaviors |

---

## Research Specifications

| File | Description |
|------|-------------|
| [predictive-memory-scorer.md](./predictive-memory-scorer.md) | Signet Predictive Memory Scorer — the feature that transforms Signet from a memory system into a predictive mind |

---

## Notes

- Papers in this folder are copies of documents that may also appear in `docs/` or other locations in the repo.
- The canonical source is always the path listed in the frontmatter.
- `RESEARCH-PAPER-OUTLINE.md` is a living document — update it as architecture evolves and data accumulates.
- Target venue for the main paper: EMNLP 2026 or NeurIPS Workshop on Agents.
