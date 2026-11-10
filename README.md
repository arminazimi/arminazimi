<div align="center">

# Armin Azimi

### Building calm tools for noisy systems.

Software engineer · Open-source builder

[![LinkedIn](https://img.shields.io/badge/LinkedIn-111111?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/armin-azimi/)
[![Velella](https://img.shields.io/badge/org-velella--sh-3F6E66?style=flat-square&labelColor=1F1F28)](https://github.com/velella-sh)

</div>

---

## Now building

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/velella-sh/ebb"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/velella-sh/ebb/main/.github/assets/mark-night.svg"><img src="https://raw.githubusercontent.com/velella-sh/ebb/main/.github/assets/mark-day.svg" width="48" height="48" alt="Ebb"></picture></a>
      <h3><a href="https://github.com/velella-sh/ebb">Ebb</a></h3>
      <p><em>Nothing ships forever. Everything ebbs.</em></p>
      <p>The open almanac of software end-of-life. 752 rules across 25 ecosystems say what is deprecated, unsupported or removed, since when, and what to move to. Every rule cites its source, and it all works offline.</p>
      <p><a href="https://velella.sh/ebb/">Docs</a> · <a href="https://github.com/velella-sh/ebb">GitHub</a> · <a href="https://www.npmjs.com/package/@velella/ebb">npm</a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/velella-sh/mizzen"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/velella-sh/mizzen/main/.github/assets/mark-night.svg"><img src="https://raw.githubusercontent.com/velella-sh/mizzen/main/.github/assets/mark-day.svg" width="48" height="48" alt="Mizzen"></picture></a>
      <h3><a href="https://github.com/velella-sh/mizzen">Mizzen</a></h3>
      <p><em>Same input. Same site.</em></p>
      <p>A deterministic docs engine. It turns a folder of Markdown into a fast, right-to-left-ready static site, and every page keeps its exact source positions.</p>
      <p><a href="https://velella.sh/mizzen/">Docs</a> · <a href="https://github.com/velella-sh/mizzen">GitHub</a> · <a href="https://www.npmjs.com/package/@velella/mizzen">npm</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/velella-sh/lateen"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/velella-sh/lateen/main/.github/assets/mark-night.svg"><img src="https://raw.githubusercontent.com/velella-sh/lateen/main/.github/assets/mark-day.svg" width="48" height="48" alt="Lateen"></picture></a>
      <h3><a href="https://github.com/velella-sh/lateen">Lateen</a></h3>
      <p><em>Easy to read. Safe to edit.</em></p>
      <p>A docs theme for people and agents, built on Mizzen. It works without JavaScript, mirrors for right-to-left languages, and is tested against WCAG 2.2 AA.</p>
      <p><a href="https://velella.sh/lateen/">Docs</a> · <a href="https://github.com/velella-sh/lateen">GitHub</a> · <a href="https://www.npmjs.com/package/@velella/lateen">npm</a></p>
    </td>
    <td width="50%"></td>
  </tr>
</table>

```ts
import { lookupProduct } from "@velella/ebb/lookup";

const request = await lookupProduct("pkg:npm/request", "2.88.2");
request.status;      // "deprecated"
request.replacement; // "Native fetch or a maintained HTTP client"
```

> Your agent's knowledge has a cutoff. Ebb doesn't.

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
