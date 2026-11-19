# Grbl ESP32 — Claude Development Plan

**Planning document only. First audit; no code changes until explicitly approved.**
Repository: nicewo/Grbl_Esp32

## Mission
Inspect the actual repository and establish a reliable, maintainable working project. Preserve useful functionality and avoid speculative rewrites.
## Phase 0 — Audit only
- Read README, docs, all project files, source tree, history, configs and dependencies.
- Verify README claims against code; classify features implemented/partial/placeholder/broken/unverified.
- Run available build/tests; record exact commands and outcomes. Never claim hardware/deployment verification unless performed.
- Check secrets, .gitignore, dependency/runtime versions, TODOs, duplicate code and unsafe configuration.
- Produce findings with paths/evidence, blockers, risks, quick wins and unknowns. Do not modify files in this phase.
## Project-specific review focus
Upstream farkları, build ortamı, board/driver config, pin mapping, web/Wi-Fi, CNC safety, flash yönergeleri ve fork stratejisi.
## Phase 1 — Hygiene and baseline
After approval: correct docs, configuration, ignore rules, dependency pinning, reproducible build/test baseline and justified CI. Keep changes scoped.
## Phase 2 — Implementation roadmap
Derive prioritized work from audit. For each item state rationale, dependencies, scope, risk/effort and acceptance criteria. Fix critical correctness/security/reliability before polish.
## Phase 3 — Tests and verification
Add regression/unit/integration tests where appropriate. Cover failure paths, edge cases and persistence. Report real results; hardware-only checks remain explicitly unverified.
## Phase 4 — Documentation and release readiness
Update setup/build/run/test/troubleshooting, limitations, release/deployment checklist and known issues. Do not expose secrets or machine/customer data.
## Required Claude workflow
1. First response is audit-only; no code or file edits.
2. Report evidence and prioritized roadmap.
3. Wait for approval before implementation.
4. Implement one milestone at a time; avoid broad rewrites.
5. Run tests/build after each milestone and report exact results.
6. Ask before destructive changes, data/schema migrations, deployment, hardware actions or breaking changes.
7. Update this plan's progress only when work is verified.
## Acceptance criteria
Documented reproducible build/test; project purpose and scope clear; high-risk issues fixed or tracked; core behavior verified; remaining limitations honestly stated.
## Checklist
- [ ] Audit completed
- [ ] Roadmap approved
- [ ] Hygiene/baseline complete
- [ ] Milestones implemented and verified
- [ ] Documentation/release readiness complete

## Claude's first task
Read this plan and the repository. Return an evidence-based audit and implementation roadmap. Make no changes in this first pass.