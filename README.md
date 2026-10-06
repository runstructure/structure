# Structure

**Your company, compiled.** Structure turns a company written down as plain documents into something agents can read, check and act on: a typed folder of canon, departments and work, a `check` that reports where the documents disagree with their own rules, and a review door that decides what reaches the company.

This repository holds the downloads. The site is [runstructure.com](https://runstructure.com).

## Install

**The command line tool**, with Homebrew on macOS or Linux:

```
brew install runstructure/tap/structure
```

That installs `structure`, with `runstructure` as a second name for the same command.

**The app for macOS**: download `Structure-mac-<date>.zip` from the [latest release](https://github.com/runstructure/structure/releases/latest), unzip it, and move `Structure.app` to your Applications folder. It needs macOS 13 or later on Apple silicon, and it is signed and notarized.

**Without Homebrew**: each release also carries the command as a tarball for macOS (Apple silicon) and Linux (x86_64 and arm64). Unpack it and put the `structure` binary on your path. Every asset has a `.sha256` beside it.

## What you get

- **`structure new`** starts a company or a project from a conversation: what it is for, who is in it, how it works, then the documents that say so.
- **`structure check`** reads the folder as the company and says what it found, in plain words: a missing type, a broken link, a document that no longer matches its rules.
- **`structure serve`** runs a local server for one company and serves a document IDE in your browser: read and edit documents, review changes as track changes or side by side, and propose them to the company.
- **The app** sits in the menu bar. It starts, stops and opens your companies and projects; **Open** takes you to that company's IDE.
- **`structure compile`** writes the files your agents read, `AGENTS.md` first, from the company itself. Edit the company, not those files.

## Releases

Each release lists what changed. The release notes are the record; the assets are the app zip, the CLI tarballs, their checksums, and a software bill of materials for each.

## Questions

Open an issue here. For anything security-related, see the site rather than an issue.
