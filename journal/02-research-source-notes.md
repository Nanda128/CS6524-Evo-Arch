# Research source notes — 22 November 2026

| Source | Location | Main relevance |
|---|---|---|
| Ryan, Collins & O'Neill (1998) | Week 4 lecture; https://doi.org/10.1007/BFb0055930 | Original GE: linear genome, BNF grammar, mod-rule mapping |
| Koza (1992) | Week 2–3 lectures | Ramped half-and-half, closure/protected operators, Santa Fe ant and multiplexer tableaus |
| Ryan & Azad (2003) | Knowledge base: `Sensible Initialisation in Chorus.pdf` | RHH-style "sensible" initialisation vs random; random won on Santa Fe |
| Nicolau (2017) | Knowledge base: `Understanding grammatical evolution initialisation.pdf`; https://doi.org/10.1007/s10710-017-9309-9 | Six GE initialisers on 16 problems; full experimental setup; PTC2 variant best |
| Luke (2000) | https://doi.org/10.1109/4235.873237 (abstract only so far) | Original PTC1/PTC2 tree-creation algorithms |
| Harper (2010) | https://doi.org/10.1109/CEC.2010.5586336 (abstract only so far) | PTC2 applied to GE; explosive grammars |
| White et al. (2013) | https://doi.org/10.1007/s10710-012-9177-2 | Benchmark blacklist (quartic, multiplexer, parity, artificial ant) and replacements (Keijzer-6, Vladislavleva-4) |
| Langdon & Poli (1998) | Week 3 lecture reference | Why the Santa Fe ant is hard (deceptive landscape) |

Evidence status: literature scoping only; no implementation or experimental results. Bibliographic details verified against publisher/index records on 22 November 2026.

Questions for next review:
1. What exactly does PTC2 do in Luke (2000), and how did Nicolau adapt it for GE?
2. Which Nicolau grammars and initialiser parameters can we match exactly?
3. Which step limit did each Santa Fe comparison paper use?
4. Which design choices survive the first mapper/initialiser prototype?
