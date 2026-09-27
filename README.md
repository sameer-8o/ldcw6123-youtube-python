# YouTube Video Recommendation Assistant

Python project for **LDCW6123 - Fundamentals of Digital Competence for Programmer**.

## Run the supplied program

Requires Python 3.7 or later and only the standard library.

```bash
python youtube_recommendation_assistant.py
```

The source is preserved byte-for-byte from the supplied `python code.txt`. It contains 30 sample videos, category and mood recommendations, duration filtering, and a Watch Later list stored for the current session.

## Git evidence for the report

- [Report section ready to copy](Git_Development_History.md)
- [Actual local Git log](git-log.txt)
- [Detailed commit dates and changes](git-log-detailed.txt)
- [Complete project including its .git history](youtube-recommendation-assistant-with-git.zip)
- [Portable Git history bundle](youtube-recommendation-assistant.bundle)
- [Arabic instructions](README_AR.md)

The local history starts with the supplied, already-written code and records the subsequent documentation, testing and submission preparation. It does not establish commits during earlier coding stages. Files were uploaded through the website because browser login was available but command-line Git authentication was not; GitHub's upload commits are separate from the local history in the bundle and exported logs.

To inspect the preserved local history, download the bundle, then run:

```bash
git clone youtube-recommendation-assistant.bundle restored-project
git -C restored-project log --oneline --graph
```

The correct flag is `--oneline`, not `--online`.

## Full documentation and tests

Extract the complete project ZIP. It includes source, input/output documentation, test cases and the verification report. From its project folder, run:

```bash
python -m unittest discover -s tests -v
```

Recorded result: **10 passing tests and 1 expected failure**. The expected failure documents an existing bug: the numeric character `²` causes a `ValueError`. The original application has not been changed. Watch Later is not saved between runs; the catalogue is fixed sample data and does not call YouTube.

The repository is private, so the lecturer and group members need access to open its links.
