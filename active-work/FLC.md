# FLC — Recurring Development Checklist
Owner: Nana | Implementation: Mana | Status: active planning | Updated 2026-10-14
Source of truth for detailed private roadmap: [FLC master ledger](https://github.com/Naktak00/flc-platform/blob/main/docs/MASTER_DEV_IDEAS_GOALS.md).

## Priority sequence (repeat review each FLC workday)
- [ ] **1. Verify Mana's reconstructed website:** compare approved current site and GitHub version, current Germantown address, responsive layout, accessibility, contact details, navigation, content, functional links and deployability. Log differences; do not assume approved or deployed.
- [ ] **2. Confirm student journey:** find FLC → choose class → access public CMT Zoom joining instructions → open current-student Thinkific link. Confirm URLs and test logged-out/mobile experience.
- [ ] **3. Research Supabase Auth before integration:** verify up-to-date pricing/limits, production reliability, Google/Apple OAuth, passwordless email codes (Yahoo/iCloud/etc.), domain redirects, account linking/recovery, security and privacy. **Decision: Supabase Auth selected as initial platform.**
- [ ] **4. Design Student Passport as core index:** stable internal student ID, profile, contact verification, enrollments, course progress, MBON registration/credential verification provenance, expiration and renewal history. Keep identity separate from course/credential records.
- [ ] **5. Prototype integration in a test environment:** role-based student/instructor/admin access, secure database policies, email confirmation, recovery, audit and backups. Never put student data in GitHub.
- [ ] **6. Create synthetic test Passport accounts:** test Google, Apple (if available), Yahoo/iCloud email-code sign-in, returning after long inactivity, email changes, lost access, and prevention of duplicate records.
- [ ] **7. Review and release gate:** demonstrate usability and privacy protections, record failures, verify recovery; don't deploy real intake until approved.

## Parallel workstream
Secure MBON registration intake and verified CMT expiration tracking, with renewal planning. FLC-issued course completion is **not** an MBON credential. Keep Thinkific as the current learning service until in-house replacement passes testing. Later: quizzes, internal learning, scheduling, 60/14-day renewal notices, AHA First Aid and BLS expansion.

## End-of-session checkpoint
Date / branch / changes / tests / blocker / next exact action: **Not yet recorded**.
