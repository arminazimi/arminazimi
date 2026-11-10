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

## Also building

<p align="center">
  <a href="https://github.com/velella-sh/mizzen">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/velella-sh/mizzen/main/.github/assets/mark-night.svg">
      <img src="https://raw.githubusercontent.com/velella-sh/mizzen/main/.github/assets/mark-day.svg" width="72" height="72" alt="Mizzen">
    </picture>
  </a>
</p>

<h3 align="center"><a href="https://github.com/velella-sh/mizzen">Mizzen</a></h3>

<p align="center">
  <strong>Same input. Same site.</strong>
</p>

Mizzen is a deterministic docs engine. It turns a folder of Markdown into a fast, right-to-left-ready static site, and every page keeps its exact source positions, so a person or a coding agent can fix the right line.

```sh
npm install --save-dev @velella/mizzen @velella/lateen
npx mizzen build . --out dist
```

**[Read the docs](https://velella.sh/mizzen/)** · **[GitHub](https://github.com/velella-sh/mizzen)** · **[npm](https://www.npmjs.com/package/@velella/mizzen)**

<p align="center">
  <a href="https://github.com/velella-sh/lateen">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/velella-sh/lateen/main/.github/assets/mark-night.svg">
      <img src="https://raw.githubusercontent.com/velella-sh/lateen/main/.github/assets/mark-day.svg" width="72" height="72" alt="Lateen">
    </picture>
  </a>
</p>

<h3 align="center"><a href="https://github.com/velella-sh/lateen">Lateen</a></h3>

<p align="center">
  <strong>Easy to read. Safe to edit.</strong>
</p>

Lateen is the docs theme for people and agents, built on Mizzen: layouts, components and design tokens that work without JavaScript and are tested against WCAG 2.2 AA.

```yaml
theme:
  name: "@velella/lateen"
```

**[Read the docs](https://velella.sh/lateen/)** · **[GitHub](https://github.com/velella-sh/lateen)** · **[npm](https://www.npmjs.com/package/@velella/lateen)**

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
