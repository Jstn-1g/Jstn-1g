# Verified open-source contribution record

Last verified: 2026-08-28.

This ledger links primary evidence and uses conservative status labels:

- **Shipped** means an official release contains and credits the work.
- **Merged** means an independently maintained repository merged the authored pull request.
- **Downstream adoption** means another contributor applied or extended a reference outside the official upstream.
- **Reference** means a tested public implementation, not an upstream merge or maintainer endorsement.
- **Under review** means open and unmerged.

## Shipped and merged work

### DeepSeek Harness Desktop

[DeepSeek Harness Desktop v0.9.0](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/releases/tag/v0.9.0) explicitly credits **@Jstn-1g** for five shipped changes:

- persistent desktop zoom controls;
- mise-managed pnpm discovery;
- direct-pnpm repair binding;
- serialized zoom operations;
- native macOS clipboard handling.

The directly merged pull requests include [#148](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/pull/148), [#156](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/pull/156), and [#159](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/pull/159).

### DSH ecosystem

Fourteen authored fixes were merged across ten independently maintained repositories:

| Project | Merged pull requests | Release evidence |
| --- | --- | --- |
| DeepSeek Harness Desktop | [#148](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/pull/148), [#156](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/pull/156), [#159](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/pull/159) | [v0.9.0](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/releases/tag/v0.9.0) |
| DSH Tauri plugins | [#4](https://github.com/dsh-tauri-desk/dsh-tauri-plugins/pull/4) | [v0.4.9](https://github.com/dsh-tauri-desk/dsh-tauri-plugins/releases/tag/v0.4.9) |
| DSH plugin hub | [#302](https://github.com/wingsky-1/dsh-plugin-hub/pull/302) | Merged upstream |
| dsh-better-edit | [#30](https://github.com/Rianico/dsh-better-edit/pull/30) | [v0.4.1](https://github.com/Rianico/dsh-better-edit/releases/tag/v0.4.1) |
| dsh-mneme | [#27](https://github.com/modusensus/dsh-mneme/pull/27) | Merged upstream |
| billion-context-dsh | [#64](https://github.com/Tyan66666/billion-context-dsh/pull/64) | Merged upstream |
| dsh-memory-evolve | [#26](https://github.com/csyangwen/dsh-memory-evolve/pull/26) | Merged upstream |
| dsh-plugin-subscriptions | [#31](https://github.com/V1ki/dsh-plugin-subscriptions/pull/31) | Merged upstream |
| dsh-plugins-store | [#4](https://github.com/ZASENJC/dsh-plugins-store/pull/4) | Merged upstream |
| dsh-market | [#279](https://github.com/dsh-market/dsh-market/pull/279), [#280](https://github.com/dsh-market/dsh-market/pull/280), [#282](https://github.com/dsh-market/dsh-market/pull/282) | [Contributor record](https://github.com/dsh-market/dsh-market/graphs/contributors?all=1) |

### Guarded HCL integration and review

[Guarded HCL v0.1.0](https://github.com/Jstn-1g/dsh-guarded-hcl/releases/tag/v0.1.0) was pinned into merged [asm-spec PR #14](https://github.com/YE-YI7/asm-spec/pull/14). My [exact-head review](https://github.com/YE-YI7/asm-spec/pull/14#pullrequestreview-5006174944) found a fail-closed artifact-kind binding gap; the author fixed it before I [reverified and approved](https://github.com/YE-YI7/asm-spec/pull/14#pullrequestreview-5006611289) the merged head.

## Tested references

- **Parent-scope subagent teardown:** the original [reference implementation](https://github.com/deepseek-ai/deepseek-harness/discussions/4239#discussioncomment-18129742) was independently cherry-picked, mutation-tested, and [adopted downstream](https://github.com/deepseek-ai/deepseek-harness/discussions/4239#discussioncomment-18134046). This is downstream adoption, not an official upstream merge.
- **Current-alpha lifecycle port:** the [v0.1.2-alpha.1 implementation receipt](https://github.com/deepseek-ai/deepseek-harness/discussions/4793#discussioncomment-18179764) records 146 focused tests. An [independent source review](https://github.com/deepseek-ai/deepseek-harness/discussions/4793#discussioncomment-18181946) and the [discussion author's follow-up](https://github.com/deepseek-ai/deepseek-harness/discussions/4793#discussioncomment-18183115) confirmed the lifecycle boundary. This remains a tested reference, not an upstream merge or maintainer endorsement.

## Under review

- [DeepSeek Harness Desktop PR #186](https://github.com/dsh-tauri-desk/deepseek-harness-desktop/pull/186) fixes repeated Git setup caused by the official MinGit helper layout. At the last verification, the frontend and Rust matrices on Windows, macOS, and Linux were green. The PR remains open and unmerged.
