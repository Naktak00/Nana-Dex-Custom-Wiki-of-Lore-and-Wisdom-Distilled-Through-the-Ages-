# Lightning Pong — Recurring Development Checklist
Owner: Nana (creative approval) | Builder: Mana | Updated 2026-10-14
**Priority:** complete and verify Lightning Pong v1.0 before beginning NyNy development.

## Every LP workday
- [ ] **1. Read current build evidence:** find the authoritative LP implementation repo, current branch, latest commit, test results, and last work order. Do not confuse the separate public lightning-pong-site repo with the Android game's verified source.
- [ ] **2. Pick one branch and one deliverable:** bug fix, gameplay, UI, audio, stability, or release task. Write acceptance criteria before editing.
- [ ] **3. Preserve existing playability:** confirm levels 1–9 and current mechanics from actual build evidence; avoid introducing reserved later-game features accidentally.
- [ ] **4. Review known Alpha issues:** level pacing and AI fairness, Mirror/Shadow behavior, menu navigation/preview close, orb mastery, cosmetics equip, and soundtrack settings. Revalidate current status rather than assuming bugs remain.
- [ ] **5. Verify audio/Janus work:** test Falx/True selection, reactive cues and baseline Janus behavior where implemented; use actual assets and reproducible tests.
- [ ] **6. Smoke test on device/build:** launch, play relevant levels, regression checks, performance, offline/privacy requirements and Android packaging. Record pass/fail with evidence.
- [ ] **7. Close the branch/day:** commit or checkpoint, record exact build/version, tests, open blockers, next action and whether Nana's creative approval is needed.
- [ ] **8. Release readiness:** complete v1.0 stability and approval before recruiting the planned 14 players/testers; defer NyNy and later mechanics until gates are met.

## Guardrails
Do not treat historical alpha reports as current test results. Never commit private player data, secrets or unlicensed media. Changes to AI mistake rates, soundtrack mapping, or scope require current verified design direction; avoid assuming older notes are authoritative.

## End-of-session checkpoint
Date / branch / commit / build / tests / blocker / next exact action: **Not yet recorded**.
