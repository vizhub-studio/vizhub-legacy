# VizHub

> **Historical repository:** This source preserves earlier **VizHub 2, VizHub 3 planning, and prototypes**. Its images, "currently deployed" language and beta domain references date from an earlier era and should not be used to identify the live service in 2026. The current user-facing product is [VizHub](https://vizhub.com/), while the previous public platform is associated with [old.vizhub.com](https://old.vizhub.com/).
>
> The original design goals and screen captures below are retained for historical study, not as a current feature list or production runbook.

## Repository navigation

- [`vizhub-v2/`](vizhub-v2/) — second-generation implementation.
- [`vizhub-v3/`](vizhub-v3/) — third-generation development history.
- [`prototypes/`](prototypes/) — earlier explorations, including false starts.
- [VZCode](https://github.com/vizhub-studio/vzcode) and [magic-sandbox](https://github.com/vizhub-studio/magic-sandbox) are separate public components relevant to the historical implementation.
- This repository has **no root `package.json`**; development commands must be taken from the specific version subdirectory, not assumed for the whole repository.

## Original project overview (historical)


A platform for interactive graphics.

Try it out 👉 https://vizhub.com/

[![image](https://user-images.githubusercontent.com/68416/146487297-256c5aca-eb67-43a8-8eff-dc68218f914d.png)](https://vizhub.com/)

[![image](https://user-images.githubusercontent.com/68416/145478956-cffca1c5-5c28-4bb4-8def-134329aa0975.png)](https://vizhub.com/curran/ad3f8d0a56cb4293864154a7c62719d4?edit=files&file=index.js)

## VizHub 2

At the time this text was written, VizHub version 2 was the product deployed at https://vizhub.com. This statement is historical and no longer describes the current deployment. Source code for this is located in the [vizhub-v2 directory](https://github.com/vizhub-studio/vizhub-legacy/tree/main/vizhub-v2). This codebase will remain deployed for some time with maintenance fixes from time to time, but active development energy is going towards VizHub 3.

### VizHub 2 Features

VizHub has enough features to be useful for people who teach data visualization with D3 and React. It has been used in [Data Visualization Course 2018](https://curran.github.io/dataviz-course-2018/), [Datavis 2020](https://datavis.tech/datavis-2020/), and [Get it Right in Black and White](

 * Fork and modify vizzes coded with ES6 in the browser.
 * iFrame-based code execution environment.
 * Uses [https://github.com/vizhub-studio/magic-sandbox](https://github.com/vizhub-studio/magic-sandbox), the same tech used for [Blockbuilder](http://blockbuilder.org/) circa 2016.
 * Code editor based on CodeMirror 5.
 * Ability to switch between files (only one file is viewable at a time currently).
 * Code editor OT integration with ShareDB and JSON0.
 * Real-time collaborative code editing with presence avatars (but [buggy](https://github.com/vizhub-studio/vizhub-legacy/blob/main/vizhub-v2/packages/json0-with-presence/index.js#L8)).
 * Embed a viz in any page (iframe-based embed with backlink).
 * Embed a code snippet in any page (iframe-based embed with backlink).
 * Mini mode
 * Full screen mode

## VizHub 3

Try it out 👉 https://beta.vizhub.com/

A rewrite of VizHub was being explored at the time this document was written, in the [vizhub-v3 directory](https://github.com/vizhub-studio/vizhub-legacy/tree/main/vizhub-v3). This sentence refers to the historical development effort, not active 2026 development.

![image](https://user-images.githubusercontent.com/68416/144443632-db541593-580d-4a29-8eb3-4a106d003d06.png)

Goals:

- **Self-hosting** - It should be possible to self-host your own instance using 100% open source code.
- **Extensibility** - It should be possible to extend the core with plugins that add features.
- **Mobile UX** - It should be possible to develop interactive visual software on a smartphone.
- **Internationalization** - The interface should be in your local language, for the global VizHub audience.
- **Accessibility** - The UI should be accessible, fully navigable by keyboard and screen reader.

## Prototypes

This repository houses an archive of prototypes as a reference to draw from for VizHub 3 development.

 * [prototypes/open-core-first-attempt](https://github.com/vizhub-studio/vizhub-legacy/tree/main/prototypes/open-core-first-attempt) - An attempt at a modular architecture. Notable features here include: Server rendering, Proper ShareDB hydration, and Markdown rendering in a Web worker
 * [prototypes/vizhub-v3-false-start](https://github.com/vizhub-studio/vizhub-legacy/tree/main/prototypes/vizhub-v3-false-start) - An earlier false start at a VizHub rewrite. Notable features here include: Working PWA setup, new viz preview design, new home page design.
 * [prototypes/vizhub-v2-false-start](https://github.com/vizhub-studio/vizhub-legacy/tree/main/prototypes/vizhub-v2-false-start) - An ancient effort. Notable features here include: CodeMirror 6 integration, dynamic code editor theming, fonts with ligatures.

## Historical participation links
The original issue boards and social invitations belonged to an earlier project phase. For current source discussions, use the relevant repository's GitHub issues.
