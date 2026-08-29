# Verified open-source contribution record

Last verified: 2026-08-29.

This ledger links primary evidence and uses conservative status labels:

- **Shipped** means an official release contains the work.
- **Merged** means an independently maintained repository merged the authored pull request.
- **Downstream adoption** means another contributor applied, integrated, or documented the work outside its source repository.
- **Reference** means a tested public implementation, not an upstream merge or maintainer endorsement.
- **Preview** means usable public work with explicitly open validation gates.
- **Under review** means open and unmerged.

## Snapshot

- **23 authored pull requests merged across 10 independently maintained DSH repositories.**
- **18 changes explicitly credit `@Jstn-1g` across six non-prerelease releases.**
- **800+ GitHub contributions in the current profile year**, spanning commits, pull requests, issues, and reviews.
- **DSH Live Voice v0.3.0-preview.1** is public, independently documented, and still accurately gated as a preview.

## Shipped work

### DeepSeek Harness Desktop

Nine authored pull requests are merged. Eleven changes are named in public release notes:

| Release | Credited work | Pull requests |
| --- | --- | --- |
| [v0.9.0](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/releases/tag/v0.9.0) | Persistent zoom controls, mise-managed pnpm discovery, direct-pnpm repair binding, serialized zoom operations, and native macOS clipboard handling | [#148](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/pull/148), [#156](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/pull/156), [#159](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/pull/159) |
| [v0.9.2](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/releases/tag/v0.9.2) | Official MinGit HTTPS-helper recognition and internal plugin-manifest validation | [#186](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/pull/186), [#189](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/pull/189) |
| [v0.9.3](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/releases/tag/v0.9.3) | Release-version identity validation, locked-revision cache invalidation, explicit Git update-target handling, and reporting unexpected owned Harness child exits while Desktop remains alive | [#193](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/pull/193), [#200](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/pull/200), [#206](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/pull/206), [#213](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/pull/213) |

### DSH Market

Six authored fixes are merged and included in non-prerelease releases:

| Release | Shipped work | Pull requests |
| --- | --- | --- |
| [v1.19.0](https://github.com/dsh-market/dsh-market/releases/tag/v1.19.0) | Complex profile-name support, masonry plugin layout, and Git-subpath preservation during updates | [#279](https://github.com/dsh-market/dsh-market/pull/279), [#280](https://github.com/dsh-market/dsh-market/pull/280), [#282](https://github.com/dsh-market/dsh-market/pull/282) |
| [v1.36.0](https://github.com/dsh-market/dsh-market/releases/tag/v1.36.0) | Integrity-safe mirrored installs, Windows restart handling, and distinct note actions | [#392](https://github.com/dsh-market/dsh-market/pull/392), [#398](https://github.com/dsh-market/dsh-market/pull/398), [#400](https://github.com/dsh-market/dsh-market/pull/400) |

### Additional shipped ecosystem work

- **DSH Tauri Plugins:** [PR #4](https://github.com/dsh-tauri-desk/dsh-tauri-plugins/pull/4) keeps external sidebars behind docked settings and is credited in [v0.4.9](https://github.com/dsh-tauri-desk/dsh-tauri-plugins/releases/tag/v0.4.9).
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

[DSH Live Voice v0.3.0-preview.1](https://github.com/Jstn-1g/dsh-live-voice/releases/tag/v0.3.0-preview.1) provides an exact-session, consent-bound manual Qwen audio turn. Its public verification records 20 test files and 191 passing tests, typechecks, builds, package lint, packed Harness fake-Qwen verification, and controlled Chrome teardown verification.

The preview was:

- announced in the official Harness repository's [Show Your Plugins discussion #4958](https://github.com/deepseek-ai/deepseek-harness/discussions/4958);
- independently included in the [DeepSeek Harness Handbook v0.5.396](https://github.com/sandbaseai/deepseek-harness-handbook/releases/tag/v0.5.396), with its consent and preview boundaries preserved;
- submitted to the curated plugin list in [awesome-dsh-plugin PR #3633](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin/pull/3633), currently under review with both checks passing.

Credential-backed Qwen, physical microphone and speaker, BFCache, and packaged-Desktop validation remain open in [release gate #5](https://github.com/Jstn-1g/dsh-live-voice/issues/5). No stable, marketplace-accepted, or production-ready claim is made.

### Guarded HCL integration and review

[Guarded HCL v0.1.0](https://github.com/Jstn-1g/dsh-guarded-hcl/releases/tag/v0.1.0) was pinned into merged [asm-spec PR #14](https://github.com/YE-YI7/asm-spec/pull/14). My [exact-head review](https://github.com/YE-YI7/asm-spec/pull/14#pullrequestreview-5006174944) found a fail-closed artifact-kind binding gap; the author fixed it before I [reverified and approved](https://github.com/YE-YI7/asm-spec/pull/14#pullrequestreview-5006611289) the merged head.

## Tested references

- **Parent-scope subagent teardown:** the original [reference implementation](https://github.com/deepseek-ai/deepseek-harness/discussions/4239#discussioncomment-18129742) was independently cherry-picked, mutation-tested, and [adopted downstream](https://github.com/deepseek-ai/deepseek-harness/discussions/4239#discussioncomment-18134046). This is downstream adoption, not an official upstream merge.
- **Current-alpha lifecycle port:** the [v0.1.2-alpha.1 implementation receipt](https://github.com/deepseek-ai/deepseek-harness/discussions/4793#discussioncomment-18179764) records 146 focused tests. An [independent source review](https://github.com/deepseek-ai/deepseek-harness/discussions/4793#discussioncomment-18181946) and the [discussion author's follow-up](https://github.com/deepseek-ai/deepseek-harness/discussions/4793#discussioncomment-18183115) confirmed the lifecycle boundary. This remains a tested reference, not an upstream merge or maintainer endorsement.

## Under review

- **DeepSeek Harness Desktop:** [#215](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/pull/215) is open and narrowly fixes official-leaf recovery extraction. Frontend, macOS, Windows, pre-job, and CodeRabbit are green; Ubuntu is red on a documented pre-existing `ETXTBSY` shim-test flake.
- **DSH Market:** [#406](https://github.com/dsh-market/dsh-market/pull/406), [#407](https://github.com/dsh-market/dsh-market/pull/407), and [#408](https://github.com/dsh-market/dsh-market/pull/408) are open and passing all six checks at this snapshot.
- **Curated DSH Live Voice listing:** [awesome-dsh-plugin #3633](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin/pull/3633) is open, cleanly mergeable, and passing both submission checks at this snapshot.
