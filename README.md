<p align="center">
  <img src="assets/mark.svg" width="72" height="72" alt="AI Prompt Library mark">
</p>

<h1 align="center">AI Prompt Library</h1>

<p align="center"><strong>Full-discipline prompt contracts, not vibe snippets.</strong></p>

<p align="center">
  Battle-tested suites for AI-assisted software and game development.<br>
  Paste one as the system / opening message and drive a coding agent through a whole job.
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-7b8cff?labelColor=0d0f11" alt="MIT License"></a>
  <img src="https://img.shields.io/badge/format-markdown%20%2B%20PDF-8f9aa6?labelColor=0d0f11" alt="Markdown + PDF">
</p>

<p align="center">
  <a href="#contents">Contents</a>
  ·
  <a href="#how-to-use">How to use</a>
  ·
  <a href="#honest-status">Status</a>
</p>

## Why it exists

A one-line "act as a game designer" prompt produces a pitch deck. These files are role/method contracts: scope, refusals, toolchain constraints, and a finish line. Each one is self-contained.

## What you get

### [`game-making/`](game-making/)

The **Game Forge** suite — end-to-end native game creation with AI agents.

| Prompt | What it does |
| --- | --- |
| [Universal Game Forge Master Prompt](game-making/universal-game-forge-master-prompt.md) | Full-cycle game direction, systems design, implementation, validation and distribution |
| [Final Diamond Polish](game-making/final-diamond-polish-prompt.md) | Hostile audit, bug hunt, balance review, optimization and gold-master packaging |
| [Follow-Up Prompt Toolkit](game-making/game-dev-follow-up-toolkit.md) | Modular follow-ups: retheme / spiritual successor, porting, DLC scope, post-mortems |

Markdown is canonical. PDFs in the same folder are print copies of those files.

### [`skyrim-skse/`](skyrim-skse/)

| Prompt | What it does |
| --- | --- |
| [SKSE Native Plugin Review Prompt](skyrim-skse/skse-native-plugin-review-prompt.txt) | Senior C++ reviewer for Skyrim SE / AE SKSE plugin modernization (VS2022 / MSVC v143 / x64, legacy-header include rules, no-build review) |

## How to use

Copy a prompt verbatim into the system or first message of the session, then attach the project. No hidden dependencies between files.

Replace bracketed fields in Game Forge before you start. The SKSE prompt assumes the user compiles; the agent does not.

## Project map

```text
game-making/     Game Forge markdown + matching PDFs
skyrim-skse/     SKSE native-plugin review prompt
LICENSE          MIT
```

## Honest status

Verified in this tree:

- Three Game Forge prompts (`.md` + `.pdf` pairs)
- One SKSE review prompt (`.txt`)
- MIT license file

Not claimed:

- A CI workflow (there is none in this repository)
- A versioned GitHub release
- That a given model will obey the contract without retries
- Runtime tests; these are prompts, not programs

## License

[MIT](LICENSE)
