# Git Development History

## Repository

Source code: https://github.com/sameer-8o/ldcw6123-youtube-python

GitHub upload history: https://github.com/sameer-8o/ldcw6123-youtube-python/commits/main/

The log below is the local Git development history. Website uploads have a separate GitHub commit history. The uploaded ZIP contains the local `.git` directory, and the Git bundle preserves the full local history for verification. This upload method was used because the browser was signed in but command-line Git authentication was unavailable.

## Recorded development work

Git tracking began by importing the existing Python YouTube Recommendation Assistant supplied by the group. The following commits record that baseline, documentation of its inputs, outputs and logic, and verification performed while preparing the repository.

1. **Baseline import:** preserve the supplied program as a Python source file and add ignore rules.
2. **Documentation:** explain program usage, inputs, outputs, implemented logic and the scope of the recorded history.
3. **Verification:** add repeatable command-line checks, record their results and document the repository links.
4. **Submission packaging:** document the website upload method and how to inspect the preserved local history.

The source file is unchanged from the supplied version. This history records the work above; it does not establish regular commits during the original coding stages, because earlier versions and commits were not supplied.

## Git log output

Command executed in the project repository:

```bash
git log --oneline --graph
```

Captured output:

```text
* 2d59bf7 Document browser upload and portable Git history
* 5fb7e7d Add CLI verification and document GitHub submission evidence
* 3e0a972 Document usage, inputs, outputs and available Git history
* f5e62e8 Import supplied Python recommendation assistant as baseline
```

Snapshot exported: 2026-09-27T21:18:25+08:00

Full final commit: `2d59bf7a96f23849bae1da9717673574a8707346`

The correct Git option is `--oneline`; `--online` in the assignment brief appears to be a typographical error.

## Verification evidence

The test suite ran 11 tests: 10 passed and one expected failure documented an existing numeric-input defect. Entering `²` at a numeric prompt causes a `ValueError`. The supplied application was preserved without changes.

Full results are in `docs/verification.md` in the repository. Detailed commit dates and changed files are supplied in `git-log-detailed.txt`.

The repository is private. Readers need repository access to view the links.
