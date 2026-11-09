<div align="center">

# Armin Azimi

### Building calm tools for noisy systems.

Software engineer · Open-source builder

[![LinkedIn](https://img.shields.io/badge/LinkedIn-111111?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/armin-azimi/)
[![Velella](https://img.shields.io/badge/org-velella--sh-3F6E66?style=flat-square&labelColor=1F1F28)](https://github.com/velella-sh)

</div>

---

## Now building

<p align="center">
  <a href="https://github.com/velella-sh/ebb">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/velella-sh/ebb/main/.github/assets/mark-night.svg">
      <img src="https://raw.githubusercontent.com/velella-sh/ebb/main/.github/assets/mark-day.svg" width="72" height="72" alt="Ebb">
    </picture>
  </a>
</p>

<h3 align="center"><a href="https://github.com/velella-sh/ebb">Ebb</a></h3>

<p align="center">
  <strong>Nothing ships forever. Everything ebbs.</strong><br>
  The open almanac of software end-of-life.
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/@velella/ebb"><img alt="npm" src="https://img.shields.io/npm/v/@velella/ebb?label=npm&logo=npm&logoColor=white&labelColor=1F1F28&color=3F6E66&style=flat"></a>
  <a href="https://github.com/velella-sh/ebb/stargazers"><img alt="stars" src="https://img.shields.io/github/stars/velella-sh/ebb?logo=github&logoColor=white&labelColor=1F1F28&color=3F6E66&style=flat"></a>
  <a href="https://github.com/velella-sh/ebb/tree/main/registry"><img alt="rules: 752" src="https://img.shields.io/badge/rules-752-3F6E66?labelColor=1F1F28&style=flat"></a>
</p>

Libraries die quietly. A runtime reaches end-of-life, a package gets deprecated, an Action is retired, and nobody tells the code that depends on it. Ebb is the tide table: an open, sourced dataset of what is ending, since when, and what to move to. Every rule cites where it came from, so a tool or a coding agent can answer **"is this still safe to depend on?"** with evidence instead of a guess.

```ts
import { lookupProduct } from "@velella/ebb/lookup";

const request = await lookupProduct("pkg:npm/request", "2.88.2");
request.status;      // "deprecated"
request.replacement; // "Native fetch or a maintained HTTP client"
```

> Your agent's knowledge has a cutoff. Ebb doesn't.

**752 rules · 25 ecosystems · works offline · TypeScript, ESM** — [**Read more →**](https://github.com/velella-sh/ebb#readme)

---

## How I build

- **Evidence over opinion.** If a tool claims something, it should show where the claim came from.
- **Honest about the unknown.** Nothing unknown is reported as safe.
- **Local-first.** Runs on your machine. No account needed.
- **Built for people and their agents.** Output a human can read and a coding agent can act on.
- **Small, with one job.** Standard identifiers, no private formats.

## Come help

Ebb is open and the data is the product. The best way in is a single rule: pick something that is about to end, find the authoritative source, and open a pull request. Start with the [contributing guide](https://github.com/velella-sh/ebb/blob/main/CONTRIBUTING.md).

<h2 align="center"><em>If it can fail, it should explain why.</em></h2>
