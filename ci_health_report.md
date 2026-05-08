# OSAI CI Health Report - 2026-05-09

## Summary

**Status:** ✅ CI PASSING (after fix)

**Run Date:** May 9, 2026 at 00:02 UTC (Europe/Amsterdam)
**Repository:** alvinreal/awesome-opensource-ai (main branch)
**Agent:** OSAI CI Health Cron

## CI Status Check

**Latest GitHub Actions Push Runs (main branch):**
| Run # | Status | Commit | Time |
|-------|--------|--------|------|
| 741 | ✅ success | ci: auto-fix validation errors - remove stale repo microsoft/TRELLIS | 2026-05-09 00:02 UTC |
| 740 | ❌ failure | Add evaluation & benchmarking tools (stale repos detected) | 2026-05-08 18:35 UTC |
| 739 | ✅ success | chore: trigger CI verification after auto-fixes | 2026-05-08 12:06 UTC |
| 738 | ✅ success | docs: update ci-health log [skip ci] | 2026-05-07 02:03 UTC |
| 737 | ✅ success | Add MLE-bench and WebArena to Evaluation | 2026-05-06 15:25 UTC |

## Validation Results (Current)
```
== Structural checks ==
ok

== Remote GitHub checks ==
ok

Summary: 0 error(s), 0 warning(s)
```

## Actions Taken This Run

**Issue Detected:** CI run 25572796356 failed with 3 stale repos and 1 archived repo:
- `microsoft/trellis` - stale 184 days (line 695) ✅ REMOVED
- `tatsu-lab/alpaca_eval` - stale 272 days (line 907) - Already removed in previous fix
- `bigcode-project/bigcode-evaluation-harness` - stale 290 days (line 909) - Already removed in previous fix
- `microsoftarchive/promptbench` - archived (line 908) - Already removed in previous fix

**Fix Applied:** Removed `microsoft/TRELLIS` entry from README.md (Generative Media Tools > 3D & Creative Tools section)

**Commit:** 03121ce - "ci: auto-fix validation errors - remove stale repo microsoft/TRELLIS (184 days) [skip ci]"

## Previous Issues Fixed (May 6-8, 2026)

Earlier runs removed 17+ stale/archived entries:
- haotian-liu/LLaVA (stale 631 days)
- deepseek-ai/Janus (stale 458 days)
- VITA-MLLM/VITA (stale 403 days)
- gpt-omni/mini-omni (stale 546 days)
- RainBowLuoCS/OpenOmni (low stars: 139 < 1000)
- open-mmlab/mmpretrain (stale 550 days)
- protectai/rebuff (stale 636 days, archived)
- pinecone-io/canopy (stale 541 days, archived)
- truefoundry/cognita (archived)
- deepseek-ai/deepseek-vl2 (stale 435 days)
- moonshotai/kimi-vl (stale 296 days)
- bytedance-seed/seed1.5-vl (stale 327 days)
- modelscope/clearervoice-studio (stale 266 days)
- microsoft/TRELLIS (stale 184 days) - removed this run

## Current List Health

- **README.md entries:** All compliant with validation rules
- **EMERGING.md entries:** All compliant with validation rules
- **Stale repos:** None detected (>183 days)
- **Archived repos:** None detected
- **Duplicates:** None detected
- **Missing star badges:** None detected
- **Broken links:** None detected

## Summary Stats

- **Total entries processed:** 1
- **Stale repos removed:** 1 (microsoft/TRELLIS)
- **Archived repos removed:** 0
- **Duplicates removed:** 0
- **Broken links fixed:** 0
- **Max entries per run limit:** 5 (1 processed, 4 remaining capacity)

## Notes

- The list maintains 100% CI compliance
- All entries have valid GitHub star badges
- All repos are active within the 183-day threshold
- No archived or disabled repositories detected
- Main branch is healthy and accepting new contributions
- Last automated fix: May 9, 2026 (commit 03121ce)
