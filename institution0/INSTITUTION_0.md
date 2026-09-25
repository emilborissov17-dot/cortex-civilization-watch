# Institution 0 — forward rows

> Counts, not causes. Attribution is UCDP's, not ours.
> Each fatality counted here is a person whose life ended in violence that a signed commitment promised would stop; we count the events because dignity itself cannot be scored, and the count is not the goal — the absence of the events is.

## F-001 — Doha Declaration of Principles — Government of the DRC and the AFC/M23 (2025-07-19)

Registered 2026-09-25 by Emil, chat signature 2026-09-25. Liveness: not terminated or superseded as of 2026-09-25 (Emil).
Lane I-1: pre-registered; OPEN; no measurement yet.

**Condition (UCDP GED).** type_of_violence = 1 (state-based armed conflict); dyad "Government of DR Congo (Zaire) - AFC" (dyad_new_id 17740); adm_1 in 'Nord Kivu province', 'Sud Kivu province'; date_start 2026-10-01 .. 2026-10-31; metric sum(best); KEPT if < 25, NOT KEPT if >= 25.

**Resolution.** Appended, never overwritten; OPEN until FINAL.
- PROVISIONAL: UCDP Candidate Events Dataset, monthly release 26.0.10 (expected around 2026-11-20 (UCDP extracts candidate data on the 20th of every month)); resolve by release date + 14 days; SOURCE_LATE if no release by 2026-12-31.
- FINAL: the first UCDP GED annual release whose coverage includes 2026-10 (GED 27.1, around June 2027 - an expectation, not the rule); resolve by release date + 14 days; SOURCE_LATE if no such release by 2027-09-30.

**Baseline (as_of ucdp:26.0.8).** Pre-commitment 2024-07-19 .. 2025-07-18: mean 319.17 fatalities/month (January 2025 alone is 3,425 of 3,830; the mean is dominated by one month.). Post-commitment 2025-08 .. 2026-08 (13 calendar months): 10 of 13 months at or above 25 -> p_not_kept = 0.7692.

## Retrospective rows (method validation, as_of ucdp:26.0.8)

the register's original rule: UCDP one-sided violence (type_of_violence=3) events by each party's verified side_a strings, from the commitment date to 2026-08; KEPT only if 0. This is NOT F-001's metric (state-based fatalities >= 25).

| commitment | party | events | months with event | civilian deaths | verdict |
|---|---|---:|---:|---:|---|
| sudan_jeddah_2023 | Government of Sudan | 54 | 19/40 | 1135 | NOT KEPT |
| sudan_jeddah_2023 | RSF | 300 | 22/40 | 4325 | NOT KEPT |
| drc_washington_2025 | Government of DR Congo (Zaire) | 34 | 13/15 | 148 | NOT KEPT (PROXY - an inter-state commitment measured by one-sided violence) |
| drc_washington_2025 | Government of Rwanda | 1 | 1/15 | 13 | NOT KEPT (PROXY - an inter-state commitment measured by one-sided violence) |
| drc_doha_2025 | Government of DR Congo (Zaire) | 34 | 13/14 | 148 | NOT KEPT |
| drc_doha_2025 | AFC | 73 | 14/14 | 484 | NOT KEPT |
| gaza_ceasefire_2025_01 | Government of Israel | 92 | 20/20 | 109 | NOT KEPT |
| gaza_ceasefire_2025_01 | Hamas | 2 | 2/20 | 0 | NOT KEPT |

## Seal

Merkle root `3d0ac18840bd1f8703737e15f7bd1eb260b50656695728605832cc95d54181c2` over the exact bytes of `experiments/institution/forward/F-001.json` (sha256 `4efc4c3d7fcfb4d188bbe3f5e1db48b72167ee351bfd814d6538a60acab70a60`, 6971 bytes) + previous root `9687c512f6b3b6e1a7c4eab4ab6d6f48ddc89b22f34569bd8a2c13e37a5b7d0f` + writer {"pid": 75904, "process": "register_forward_row.py", "commit": "091edbb67a8d2224740e2deb1733470d962a003d"}.

## Citation

- Provisional source: Hegre, Håvard, Mihai Croicu, Kristine Eck, and Stina Högbladh, July 2020. Introducing the UCDP Candidate Events Dataset Research & Politics doi: 10.1177/2053168020935257
- Final source: Sundberg, Ralph, and Erik Melander, 2013, “Introducing the UCDP Georeferenced Event Dataset”, Journal of Peace Research, vol.50, no.4, 523-532
