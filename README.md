<h1 align="center">Jamal Kamaladdin</h1>

<p align="center">
Technical enough to understand the problem, experienced enough to manage the solution.
</p>

<p align="center">
  <a href="https://camalali.com"><img alt="camalali.com" src="https://img.shields.io/badge/camalali.com-3584e4?style=flat-square&logo=readthedocs&logoColor=white"></a>
  <a href="https://www.npmjs.com/package/zero-dep-devtools"><img alt="npm" src="https://img.shields.io/npm/v/zero-dep-devtools?style=flat-square&color=cb3837&label=npm&logo=npm&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/camalali/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0a66c2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="https://orcid.org/0009-0002-9513-0512"><img alt="ORCID" src="https://img.shields.io/badge/ORCID-a6ce39?style=flat-square&logo=orcid&logoColor=white"></a>
  <a href="README.az.md"><img alt="Azərbaycanca" src="https://img.shields.io/badge/Az%C9%99rbaycanca-30363d?style=flat-square&logo=googletranslate&logoColor=white"></a>
</p>

---

Most of what I do sits between the business and the system: working out what is
actually being asked for, then finding the answer the existing constraints will
tolerate.

The interesting question is usually not *how do we build this*. It is *why are
we building it this way*, and what that choice will cost in a year.

## Azerbaijani, upstream

Azerbaijani is missing from most developer tooling. Not because it is difficult,
but because nobody sends the file. A locale is code: it ships with tests, sort
order, plural forms and placeholder contracts, and it stays in the repository
long after the person who wrote it has moved on.

Every entry below was written by hand, checked against a source locale for key
and placeholder parity, and reviewed by the project maintainers before it landed.
Sixteen pull requests have been merged into nine projects so far.

| | Project | Stars | Contribution |
|---|---|---|---|
| <img src="https://github.com/usememos.png?size=32" width="18"> | [usememos/memos](https://github.com/usememos/memos) | <img alt="stars" src="https://img.shields.io/github/stars/usememos/memos?style=flat-square&labelColor=0d1117&color=30363d"> | Full Azerbaijani interface, 1,126 lines <br> [#6278](https://github.com/usememos/memos/pull/6278) |
| <img src="https://github.com/freescout-help-desk.png?size=32" width="18"> | [freescout-help-desk/freescout](https://github.com/freescout-help-desk/freescout) | <img alt="stars" src="https://img.shields.io/github/stars/freescout-help-desk/freescout?style=flat-square&labelColor=0d1117&color=30363d"> | Interface plus PHP validation messages, 1,051 lines <br> [#5619](https://github.com/freescout-help-desk/freescout/pull/5619) |
| <img src="https://github.com/Lissy93.png?size=32" width="18"> | [Lissy93/dashy](https://github.com/Lissy93/dashy) | <img alt="stars" src="https://img.shields.io/github/stars/Lissy93/dashy?style=flat-square&labelColor=0d1117&color=30363d"> | Azerbaijani translation, 594 lines <br> [#2334](https://github.com/Lissy93/dashy/pull/2334) |
| <img src="https://github.com/faker-js.png?size=32" width="18"> | [faker-js/faker](https://github.com/faker-js/faker) | <img alt="stars" src="https://img.shields.io/github/stars/faker-js/faker?style=flat-square&labelColor=0d1117&color=30363d"> | `az` locale modules: airline, food, science <br> [#4036](https://github.com/faker-js/faker/pull/4036) · [#4037](https://github.com/faker-js/faker/pull/4037) · [#4035](https://github.com/faker-js/faker/pull/4035) |
| <img src="https://github.com/alefragnani.png?size=32" width="18"> | [alefragnani/vscode-project-manager](https://github.com/alefragnani/vscode-project-manager) | <img alt="stars" src="https://img.shields.io/github/stars/alefragnani/vscode-project-manager?style=flat-square&labelColor=0d1117&color=30363d"> | Editor extension localization, 253 lines <br> [#975](https://github.com/alefragnani/vscode-project-manager/pull/975) |
| <img src="https://github.com/maplibre.png?size=32" width="18"> | [maplibre/maputnik](https://github.com/maplibre/maputnik) | <img alt="stars" src="https://img.shields.io/github/stars/maplibre/maputnik?style=flat-square&labelColor=0d1117&color=30363d"> | Language support and translations, 207 lines <br> [#2134](https://github.com/maplibre/maputnik/pull/2134) |
| <img src="https://github.com/primefaces.png?size=32" width="18"> | [primefaces/primelocale](https://github.com/primefaces/primelocale) | <img alt="stars" src="https://img.shields.io/github/stars/primefaces/primelocale?style=flat-square&labelColor=0d1117&color=30363d"> | Locale shared by every PrimeFaces UI library <br> [#268](https://github.com/primefaces/primelocale/pull/268) |
| <img src="https://github.com/linuxserver.png?size=32" width="18"> | [linuxserver/Heimdall](https://github.com/linuxserver/Heimdall) | <img alt="stars" src="https://img.shields.io/github/stars/linuxserver/Heimdall?style=flat-square&labelColor=0d1117&color=30363d"> | Azerbaijani translation, 131 lines <br> [#1598](https://github.com/linuxserver/Heimdall/pull/1598) |
| <img src="https://github.com/apexcharts.png?size=32" width="18"> | [apexcharts/apexcharts.js](https://github.com/apexcharts/apexcharts.js) | <img alt="stars" src="https://img.shields.io/github/stars/apexcharts/apexcharts.js?style=flat-square&labelColor=0d1117&color=30363d"> | Chart locale: months, days, toolbar labels <br> [#5289](https://github.com/apexcharts/apexcharts.js/pull/5289) |

## Fixes found along the way

Reading a codebase closely enough to translate it tends to surface real bugs.
These were reported and fixed in the same repositories.

| Project | Fix | PR |
|---|---|---|
| apexcharts | Selection resize handles could be dragged outside the data range | [#5291](https://github.com/apexcharts/apexcharts.js/pull/5291) |
| apexcharts | Long point annotation labels were clipped by the grid edge | [#5292](https://github.com/apexcharts/apexcharts.js/pull/5292) |
| apexcharts | Combo columns stacked on the axis instead of the layer below | [#5293](https://github.com/apexcharts/apexcharts.js/pull/5293) |
| apexcharts | Heatmap and treemap tooltips escaped the plot area | [#5290](https://github.com/apexcharts/apexcharts.js/pull/5290) |
| tsx | `tsx file.ts \| head` crashed with EPIPE instead of exiting quietly | [#840](https://github.com/privatenumber/tsx/pull/840) |
| maputnik | Layer visibility button label did not match the action it performed | [#2135](https://github.com/maplibre/maputnik/pull/2135) |
| dashy | Weather widget details stayed hidden until a manual toggle | [#2335](https://github.com/Lissy93/dashy/pull/2335) |

## My own projects

<table>
<tr>
<td width="50%" valign="top">

### [camalali-tools](https://github.com/jamalkamaladdin/camalali-tools)

166 developer tools that run entirely in the browser. JWT decoder, cron parser,
regex tester, DNS and SSL lookups, CIDR maths, JSON and Base64 work. Nothing is
uploaded, because nothing leaves the tab.

<img alt="tools" src="https://img.shields.io/badge/tools-166-3584e4?style=flat-square">
<img alt="test cases" src="https://img.shields.io/badge/test_cases-2350%2B-12a5a5?style=flat-square">
<img alt="dependency free" src="https://img.shields.io/badge/dependency--free-160_tools-6c5ce7?style=flat-square">
<img alt="license" src="https://img.shields.io/badge/license-MIT-2ec27e?style=flat-square">

The same 166 tools ship as a library with nothing underneath them:

```bash
npm i zero-dep-devtools
```

</td>
<td width="50%" valign="top">

### [agent-ready-templates](https://github.com/jamalkamaladdin/agent-ready-templates)

The documents a project has to produce anyway, packaged so a coding agent can
act on them. Each template carries the instruction that says which job it is:
fill it in, adapt it to the repository, or audit a project against it.

### [camalali.com](https://camalali.com)

520 long-form articles on system design, a 1,000 term technical glossary in
Azerbaijani, role by role learning paths, and the tools above running live. The
language has almost no engineering writing at this depth, which is the whole
reason the site exists.

[Articles](https://camalali.com/bloq) ·
[Tools](https://camalali.com/alet) ·
[Glossary](https://camalali.com/luget) ·
[Templates](https://camalali.com/sablonlar)

</td>
</tr>
</table>

## Built with

<p>
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-0d1117?style=flat-square&logo=typescript&logoColor=3178c6">
  <img alt="React" src="https://img.shields.io/badge/React-0d1117?style=flat-square&logo=react&logoColor=61dafb">
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-0d1117?style=flat-square&logo=nextdotjs&logoColor=ffffff">
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-0d1117?style=flat-square&logo=nodedotjs&logoColor=5fa04e">
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind-0d1117?style=flat-square&logo=tailwindcss&logoColor=38bdf8">
  <img alt="PHP" src="https://img.shields.io/badge/PHP-0d1117?style=flat-square&logo=php&logoColor=777bb4">
  <img alt="WordPress" src="https://img.shields.io/badge/WordPress-0d1117?style=flat-square&logo=wordpress&logoColor=ffffff">
  <img alt="Python" src="https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=ffd43b">
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-0d1117?style=flat-square&logo=postgresql&logoColor=4169e1">
  <img alt="Docker" src="https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=2496ed">
  <img alt="Linux" src="https://img.shields.io/badge/Linux-0d1117?style=flat-square&logo=linux&logoColor=fcc624">
  <img alt="Git" src="https://img.shields.io/badge/Git-0d1117?style=flat-square&logo=git&logoColor=f05033">
</p>

## Elsewhere

[camalali.com](https://camalali.com) ·
[LinkedIn](https://www.linkedin.com/in/camalali/) ·
[ORCID 0009-0002-9513-0512](https://orcid.org/0009-0002-9513-0512) ·
[npm](https://www.npmjs.com/package/zero-dep-devtools) ·
[Azərbaycanca](README.az.md)
