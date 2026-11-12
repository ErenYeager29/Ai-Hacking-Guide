# Changelog

## 2026 Edition - October 2026

**Approach:** original text, voice and filenames are preserved. Each chapter gains one new numbered section titled "... in 2026" (techniques and developments, defenses, testing and measurement), placed before the chapter's Summary (or "Looking Ahead" in Chapter 01). The Summary keeps its place and is renumbered by +1. Appendices gain a 2026 section. Use `git diff` to see exactly what was added.

### Per-chapter changes
| Chapter | New section | Summary |
|---|---|---|
| 01 | 1.10 Prompt Injection in 2026 | Agents raise blast radius; lethal trifecta; Rule of Two; taxonomy additions. "Looking Ahead" is now 1.11 |
| 02 | 2.8 Architecture in 2026 | Long context, compaction, MCP, memory, multimodal, reasoning, output handling |
| 03 | 3.10 Trust Boundaries in 2026 | Instruction hierarchy, spotlighting, CaMeL/dual-LLM, gateways, human approval |
| 04 | 4.10 System Prompts in 2026 | OWASP LLM07, operator/user layers, prompt hygiene |
| 05 | 5.10 LLM Psychology in 2026 | Reasoning models, persona vectors, emergent misalignment, constitutional classifiers |
| 06 | 6.10 Basic Injection in 2026 | Baseline tests, adaptive attacks, structural separation |
| 07 | 7.10 Role Hijacks in 2026 | Persona robustness and drift |
| 08 | 8.10 System Prompt Extraction in 2026 | Secrets in prompts, tool schema leakage, exfiltration channels |
| 09 | 9.10 Obfuscation in 2026 | Hidden Unicode, multimodal carriers, normalization |
| 10 | 10.10 Direct Override in 2026 | Hierarchy, prompt builders, multi-agent, many-shot |
| 11 | 11.10 Multi-Turn and Memory in 2026 | Escalation, persistent memory, compaction laundering |
| 12 | 12.10 Recursive and Echo in 2026 | Agent loops, handoffs, unbounded consumption |
| 13 | 13.9 Indirect Injection in 2026 | Zero-click, browser/coding agents, MCP, RAG poisoning, defenses |
| 14 | 14.10 Chaining in 2026 | MCP chains, skills, agent protocols, gateways |
| 15 | 15.10 Style and Tone in 2026 | Persuasion, sycophancy, drift |
| 16 | 16.11 Recon in 2026 | Mapping agents, tools, trust paths |
| 17 | 17.10 Payload Libraries in 2026 | Decay, automation, responsible corpora (no new payloads added) |
| 18 | 18.10 Fuzzing and Tooling in 2026 | garak, PyRIT, Promptfoo, Spikee, agent benchmarks |
| 19 | 19.10 Exploit Reporting in 2026 | Agent-era report contents, success rates, mapping |
| 20 | 20.7 Ethics and Disclosure in 2026 | Side effects, programs, regulation |
| App. A-D | A.7, B.8, C additions, D corrections and 2024-2026 timeline | |

### Corrections and flags
- "Prompt injection" was coined in **September 2022**, not 2021.
- **arXiv:2311.16119** is the HackAPrompt paper (Schulhoff et al.), not a Greshake survey; Greshake et al. is **arXiv:2302.12173**. Original entries were kept and annotated; correct entries added under each chapter's References.
- Many "Internal Memo" and "Internal Documentation" references could not be verified; flagged, not removed.
- README linked Chapter 10 to a non-existent `10-direct-override.md`; fixed to `10-jailbreaks.md`. (The chapter title is "Direct Override"; consider renaming the file in a separate commit.)
- `SUMMARY.md` was empty; now a table of contents.

### Caveats
2025-2026 items come from vendor posts and secondary sources found through web search. Verify each against its primary source before publication. The 2026 sections describe attacks at research and standards level and add no new working payloads; Chapters 17 and 18 add testing guidance only.
