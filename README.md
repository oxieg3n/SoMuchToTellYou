# So Much to Tell You

Interactive first-use prototype, build **1110-FixedBlankScreen**, created for design review.

## Live preview

https://smty-homecoming-demo.jamesahastings810.workers.dev/

## What you can test

### Family and friends

- Switch to **View family** on the top bar (including on phones).
- Browse example family memories.
- Create text-based sample memories with title, date, contributor, and story.
- Select a photo, audio, or video file to test the picker interface. **No file contents are uploaded, saved, or playable in this demo.**
- Mark a memory sensitive and see the separate confirmation flow.
- Add mock contributor names, without sending real invitations.

### Returning person

- Switch to **View homecoming** on the top bar.
- Explore memories left by friends/family and choose when to reveal sensitive stories.
- Set a starting year for sample historical catch-up.
- Navigate the step-by-step everyday-life lessons.
- Choose a help category or describe a problem and see topic-matched organization links. These are *general entry points*, not personalized referrals or a counselor.

## Important: public prototype, no security backend

This preview intentionally contains **fictional content only**. There are no accounts, actual private family spaces, invitations, media uploads, messaging, shared timelines, verified real-time resource availability, or AI counseling. Text added in this browser is stored in that browser's **localStorage** and never sent to another person's account. Do not enter private family stories or upload sensitive media for design review.

Website deployment and GitHub design branch are previews only. Real Android development is intentionally deferred until screen and navigation approval. The family web experience is designed to work for Android/iPhone/desktop browsers; the final Android app should have the same workflows.

## Architecture handoff later

Following design approval: native Android (family/friends); responsive family web experience with feature parity for iOS users; returning-person website; authenticated collaboration and media storage; invitation consent and contributor ownership; sensitive-milestone controls; resource verification; accessible tutorials and usability testing with technology novices; privacy/security threat model.

## Design requirements

1. Dignity first and adult language.
2. Privacy and explicit consent.
3. Sensitive memories revealed only on user choice.
4. Human help reachable without diagnosis or invented resources.
5. Accessible from the beginning.
6. Usable by someone unfamiliar with modern smartphones.

Brand: deep green **#172734**, white **#FFFFFF**, cream **#FBF1E3**, signature orange **#F47721**. The book-spine outline uses a brighter orange highlight **#F6A51B**, confined to the icon. The top bar is orange with green readable text; the content background is cream. Main logo: `assets/logo.svg`; icon-only: `assets/book-spine-mark.svg`. These are editable vectors based on the approved visual reference; the wordmark's font remains live SVG text for the prototype.

## Branch

`design/1110-first-homecoming-demo`. This branch is deliberately separate from `main`.

## 2026-11-10 demo repair

Fixed a blank-screen regression caused by calling a removed `name()` helper after switching the sidebar to the complete SVG logo. The interface now uses `logo()` alone. Added a visible fallback if a future render unexpectedly throws an exception. Tested live mobile browser rendering and the family memory creation workflow after redeployment.
