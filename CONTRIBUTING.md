# Contributing

Thanks for helping me recover and rebuild Millsberry. Even a single verified asset, archived page, or reproducible bug report can move the project forward.

## What I'm Looking For

- Recovered assets that close a known gap.
- Better route handling for missing pages and old process endpoints.
- Verification against preserved captures or archived references.
- Replay fixes with clear steps to reproduce the original problem.
- Documentation that makes the recovery scope, limitations, or provenance easier to understand.

## Before Opening a Pull Request

- Avoid adding runtime state such as local account files or generated missing-request logs.
- Keep recovered data clearly separated from generated fallback files.
- Update `app/STATUS.md` or the relevant note in `recovery-osint/` when your change affects documented behavior.
- Identify the source of recovered material as precisely as you can.
- If you add a fallback or reconstruction, label it clearly so it cannot be mistaken for an original recovered file.
- Leave existing license, notice, and attribution files in place.

## A Practical Workflow

1. Pick a missing route or asset from the reports in `recovery-osint/` or from your local `app/output/missing-requests.jsonl`.
2. Recover or reconstruct the smallest piece needed to close the gap.
3. Test it in the replay app.
4. Update the relevant status note.
5. Open a pull request explaining what was missing, what you changed, where the material came from, and how you verified it.

If you are unsure whether something belongs in the repository, ask in the [Millsberry Reborn Discord](https://discord.gg/p8H9Dtajgz) before spending a lot of time on it.
