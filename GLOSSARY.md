# Glossary (Repo Excerpt)

For the full glossary, see: https://github.com/instance001/Whatisthisgithub/blob/main/GLOSSARY.md

This file contains only the glossary entries for this repository. Mapping tag legends and global notes live in the full glossary.

## Janet-MCM-Core
| Term | Alternate term(s) | Alt map | External map | Relation to existing terminology | What it is | What it is not | Source |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Janet (MCM) | Janet, Modest Cognition Model | = | ~ | Deterministic cognition architecture | Open reference implementation of MCM: deterministic selectors, modular skills, typed explicit memory, schema validation, human-gated curriculum | Not an LLM; not probabilistic next-token model | Janet-MCM-Core/Readme-Janet-MCM-Core.md |
| Typed Memory Spine | memory spine | ~ | ~ | Structured memory ledger | Three-stage memory pipeline: Candidate (raw/untrusted) → Reviewed (human inspected) → Stable (trusted, versioned); no direct runtime writes to Stable | Not unvetted log; not embedding store | Janet-MCM-Core/janet_memory_spine_assets_v0.1.zip:memory_spine_diagram_ascii.txt |
| Skill-based cognition | skills | ~ | ~ | Modular capability design | Knowledge encapsulated in explicit skills chosen by selectors; growth via human-approved curriculum | Not hidden weights; not autonomous skill creation | Janet-MCM-Core/Readme-Janet-MCM-Core.md |
| Deterministic selectors | selectors | ~ | ~ | Routing mechanism | Schema-based routing to pick skills with inspectable steps | Not stochastic sampling; not opaque | Janet-MCM-Core/Readme-Janet-MCM-Core.md |
| Zero-hallucination stance | zero hallucination | ~ | ~ | Safety rule | Ambiguity rejected; system refuses rather than guessing | Not permissive generation; not probabilistic bluffing | Janet-MCM-Core/Readme-Janet-MCM-Core.md |
