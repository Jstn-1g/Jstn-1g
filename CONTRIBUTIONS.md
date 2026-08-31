# Verified open-source contribution record

Last verified: 2026-08-31.

This ledger links primary evidence and uses conservative status labels:

- **Shipped** means an official release contains the work.
- **Merged** means an independently maintained repository merged the authored pull request.
- **Downstream adoption** means another contributor applied, integrated, or documented the work outside its source repository.
- **Reference** means a tested public implementation, not an upstream merge or maintainer endorsement.
- **Preview** means usable public work with explicitly open validation gates.
- **Under review** means open and unmerged.

## Snapshot

- **35 authored pull requests merged across 11 independently maintained DSH repositories:** 33 engineering patches across 10 code repositories and two accepted catalog updates.
- **26 changes explicitly credit `@Jstn-1g` across nine stable releases, plus two credits in one prerelease.**
- **800+ GitHub contributions in the current profile year**, spanning commits, pull requests, issues, and reviews.
- **DSH Live Voice** is public, independently documented, and accepted into the curated ecosystem catalog. Its current release is **v0.3.0-preview.5**; the catalog's [Preview.5 artifact and description update is under review](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin/pull/3885).

## Shipped work

### DeepSeek Harness Desktop

Eleven authored pull requests are merged. Eleven changes are named in stable release notes and two more in a prerelease:

| Release | Credited work | Pull requests |
| --- | --- | --- |
| [v0.9.0](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/releases/tag/v0.9.0) | Persistent zoom controls, mise-managed pnpm discovery, direct-pnpm repair binding, serialized zoom operations, and native macOS clipboard handling | [#148](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/pull/148), [#156](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/pull/156), [#159](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/pull/159) |
| [v0.9.2](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/releases/tag/v0.9.2) | Official MinGit HTTPS-helper recognition and internal plugin-manifest validation | [#186](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/pull/186), [#189](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/pull/189) |
| [v0.9.3](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/releases/tag/v0.9.3) | Release-version identity validation, locked-revision cache invalidation, explicit Git update-target handling, and reporting unexpected owned Harness child exits while Desktop remains alive | [#193](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/pull/193), [#200](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/pull/200), [#206](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/pull/206), [#213](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/pull/213) |
| [v0.9.5-beta.2](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/releases/tag/v0.9.5-beta.2) | Official-leaf recovery extraction and Node runtime compatibility aligned with DSH alpha | [#215](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/pull/215), [#231](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/pull/231) |

### DSH Market

Thirteen authored fixes are merged and explicitly credited in stable releases:

| Release | Shipped work | Pull requests |
| --- | --- | --- |
| [v1.19.0](https://github.com/dsh-market/dsh-market/releases/tag/v1.19.0) | Complex profile-name support, masonry plugin layout, and Git-subpath preservation during updates | [#279](https://github.com/dsh-market/dsh-market/pull/279), [#280](https://github.com/dsh-market/dsh-market/pull/280), [#282](https://github.com/dsh-market/dsh-market/pull/282) |
| [v1.36.0](https://github.com/dsh-market/dsh-market/releases/tag/v1.36.0) | Integrity-safe mirrored installs, Windows restart handling, and distinct note actions | [#392](https://github.com/dsh-market/dsh-market/pull/392), [#398](https://github.com/dsh-market/dsh-market/pull/398), [#400](https://github.com/dsh-market/dsh-market/pull/400) |
| [v1.37.0](https://github.com/dsh-market/dsh-market/releases/tag/v1.37.0) | Bundled Desktop host diagnostics, subpath-safe note requests, accurate rollback reporting, and normalized DSH-home resolution | [#406](https://github.com/dsh-market/dsh-market/pull/406), [#407](https://github.com/dsh-market/dsh-market/pull/407), [#408](https://github.com/dsh-market/dsh-market/pull/408), [#424](https://github.com/dsh-market/dsh-market/pull/424) |
| [v1.38.0](https://github.com/dsh-market/dsh-market/releases/tag/v1.38.0) | Real Web E2E coverage against DSH alpha, exact-composition snapshot restoration, and rollback to the previous build after failed updates | [#421](https://github.com/dsh-market/dsh-market/pull/421), [#418](https://github.com/dsh-market/dsh-market/pull/418), [#428](https://github.com/dsh-market/dsh-market/pull/428) |

### Additional shipped ecosystem work

- **DSH Tauri Plugins:** [PR #4](https://github.com/dsh-tauri-desk/dsh-tauri-plugins/pull/4) keeps external sidebars behind docked settings and is credited in [v0.4.9](https://github.com/dsh-tauri-desk/dsh-tauri-plugins/releases/tag/v0.4.9). [PR #27](https://github.com/dsh-tauri-desk/dsh-tauri-plugins/pull/27) authenticates all 29 direct plugin routes against the current DSH alpha host contract and is explicitly credited in [v0.6.2](https://github.com/dsh-tauri-desk/dsh-tauri-plugins/releases/tag/v0.6.2).
- **dsh-better-edit:** [PR #30](https://github.com/Rianico/dsh-better-edit/pull/30) blocks served hash echoes from entering writes and is included in [v0.4.1](https://github.com/Rianico/dsh-better-edit/releases/tag/v0.4.1); that release body describes the fix but does not name the author.

## Other merged upstream fixes

| Project | Merged pull request | Outcome |
| --- | --- | --- |
| DSH plugin hub | [#302](https://github.com/wingsky-1/dsh-plugin-hub/pull/302) | Hardened provider-usage adapter state persistence. |
| dsh-mneme | [#27](https://github.com/modusensus/dsh-mneme/pull/27) | Exposed memory IDs through list and search tools. |
| billion-context-dsh | [#64](https://github.com/Tyan66666/billion-context-dsh/pull/64) | Used the detected context window for status and compression. |
| dsh-memory-evolve | [#26](https://github.com/csyangwen/dsh-memory-evolve/pull/26) | Synchronized review tools with the runtime toggle. |
| dsh-plugin-subscriptions | [#31](https://github.com/V1ki/dsh-plugin-subscriptions/pull/31) | Bounded replayed Codex tool-call IDs. |
| dsh-plugins-store | [#4](https://github.com/ZASENJC/dsh-plugins-store/pull/4) | Retained recognized plugins during pending reclassification. |

## Original systems and downstream adoption

### DSH Live Voice

[DSH Live Voice v0.3.0-preview.5](https://github.com/Jstn-1g/dsh-live-voice/releases/tag/v0.3.0-preview.5) provides an exact-session, consent-bound one-turn voice experience with a credential-free local synthetic demo, an optional Qwen Audio path, and explicit transcript-to-draft handoff without automatic submission. Its immutable-release verification records 30 test files and 263 passing tests, typechecks, builds, package lint, protected Node 22.19/current-24 CI, and a sanitized exact-alpha.2 synthetic receipt bound to the release commit and tarball.

The preview was:

- announced in the official Harness repository's [Show Your Plugins discussion #4958](https://github.com/deepseek-ai/deepseek-harness/discussions/4958);
- accepted into the curated ecosystem catalog through [awesome-dsh-plugin PR #3633](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin/pull/3633), then updated through merged [PR #3747](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin/pull/3747), with the [Preview.5 pointer and description update](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin/pull/3885) under review;
- independently included in the [DeepSeek Harness Handbook v0.5.396](https://github.com/sandbaseai/deepseek-harness-handbook/releases/tag/v0.5.396), with its consent and preview boundaries preserved;
- kept explicitly labeled as a preview with its open validation gates visible; and
- opened a bounded [five-person Windows Chrome/Edge founding-tester cohort](https://github.com/Jstn-1g/dsh-live-voice/issues/58) that requests sanitized stopping-point evidence rather than recordings or credentials.

Preview.5 proves only its fixed local synthetic path on the authenticated localhost DSH Web carrier. Maintainer-run served-Web BFCache evidence remains bound to older exact artifacts. Credential-backed Qwen, a live provider, physical microphone and speaker, Preview.5 BFCache, independent reproduction, and packaged-Desktop validation remain open in [release gate #5](https://github.com/Jstn-1g/dsh-live-voice/issues/5). Downloads, clones, listings, CI, and maintainer runs are not counted as users; no stable, marketplace-accepted, production-ready, official-inclusion, or endorsement claim is made.

### Guarded HCL integration and review

[Guarded HCL v0.1.0](https://github.com/Jstn-1g/dsh-guarded-hcl/releases/tag/v0.1.0) was pinned into merged [asm-spec PR #14](https://github.com/YE-YI7/asm-spec/pull/14). My [exact-head review](https://github.com/YE-YI7/asm-spec/pull/14#pullrequestreview-5006174944) found a fail-closed artifact-kind binding gap; the author fixed it before I [reverified and approved](https://github.com/YE-YI7/asm-spec/pull/14#pullrequestreview-5006611289) the merged head.

## Tested references

- **Parent-scope subagent teardown:** the original [reference implementation](https://github.com/deepseek-ai/deepseek-harness/discussions/4239#discussioncomment-18129742) was independently cherry-picked, mutation-tested, and [adopted downstream](https://github.com/deepseek-ai/deepseek-harness/discussions/4239#discussioncomment-18134046). This is downstream adoption, not an official upstream merge.
- **Current-alpha lifecycle port:** the [v0.1.2-alpha.1 implementation receipt](https://github.com/deepseek-ai/deepseek-harness/discussions/4793#discussioncomment-18179764) records 146 focused tests. An [independent source review](https://github.com/deepseek-ai/deepseek-harness/discussions/4793#discussioncomment-18181946) and the [discussion author's follow-up](https://github.com/deepseek-ai/deepseek-harness/discussions/4793#discussioncomment-18183115) confirmed the lifecycle boundary. This remains a tested reference, not an upstream merge or maintainer endorsement.

## Under review

- **DSH Market:** [#434](https://github.com/dsh-market/dsh-market/pull/434) makes post-update rollback source-exact. It is cleanly mergeable and all six public checks pass.
- **DSH Tauri Plugins:** [#26](https://github.com/dsh-tauri-desk/dsh-tauri-plugins/pull/26) fails closed permanent session deletion. It is cleanly mergeable and all eight public checks pass.
- **DSH TUI plugin:** [#2](https://github.com/JimLuan/dsh-tui-plugin/pull/2) hardens compatibility with DSH v0.1.2 alpha. It is cleanly mergeable and awaits upstream review and release ownership.
