# Release 2.0 Readiness Checklist

This checklist tracks the surviving work items for the Release 2.0 readiness audit. The community discussion review item was dropped for this cycle and closed as not planned.

## Checklist

1. Confirm the release tag points at the right commit
2. Verify CI is green on the release branch
3. Update the changelog from recent commits

## Reference Data (microsoft/vscode)

Reference data gathered live from the public `microsoft/vscode` repository to ground this checklist:

- **Example tag:** `vsda-v1.39.1` — one of the repository's current git tags (points at commit `2cbf51458e5d74f39c4f19fb69c5c75f6a27529b`). Other recent tags include `v14` and `v1.19.3`.
- **Most recent commit on the default branch:** `151923988b4a90949652f9dac31fc06008847b09` — "chat: fix sandbox trusted CA alert word wrapping (#343065)"
- **CI reference:** The `CodeQL` workflow (`.github/workflows/codeql.yml`) most recent run (run 39716283840, run #20763) completed with status `completed` and conclusion `action_required`.
