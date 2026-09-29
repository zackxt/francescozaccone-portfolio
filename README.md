# Francesco Zaccone — Portfolio

## Asset structure

```text
assets/
├── _inbox/
├── _review/
│   └── frame-selection/
├── fonts/
│   └── Manrope/
├── site/
│   ├── favicon/
│   ├── icons/
│   └── about/
├── hero/
│   ├── desktop/
│   └── mobile/
├── projects/
└── _placeholders/
    ├── images/
    └── video/
```

## Directory guide

- `assets/fonts/Manrope/` contains the local Manrope font files used by the site. Keep this directory in place.
- `assets/_inbox/` is the canonical intake area for source media. Do not alter originals in place.
- `assets/_review/` is the canonical review area for temporary frame selections, contact sheets and review notes.
- `assets/site/favicon/` is reserved for the final site favicon assets.
- `assets/site/icons/` is reserved for interface and utility icons.
- `assets/site/about/` is reserved for images or media specific to the About section.
- `assets/hero/desktop/` and `assets/hero/mobile/` are reserved for the future final homepage hero media.
- `assets/projects/` contains the real project assets added later.
- `assets/_placeholders/images/` contains temporary or generated images used only to stand in for real work.
- `assets/_placeholders/video/` contains temporary video placeholders, when needed.

## Project convention

Use one directory per project:

```text
assets/projects/01_project-name/
├── cover/
│   ├── desktop/
│   └── mobile/
├── film/
├── breakdown/
│   ├── plates/
│   ├── elements/
│   └── finals/
├── process/
└── technical/
```

Use a zero-padded number and a short lowercase `kebab-case` project name. Keep filenames descriptive and stable, for example `cover-desktop.webp`, `breakdown-final-01.webp` or `technical-material-study.mp4`.

Current project directories:

```text
assets/projects/
├── 01_enemy/                 # flagship cinematic / VFX project
└── 02_digital-double/        # scan, MetaHuman, facial performance and OPLO application
```

`02_digital-double/` is the canonical home for the complete Digital Double workflow. OPLO is an application chapter inside this project, not a competing Selected Work. Avoid duplicating heavy media when a stable existing path is appropriate.

## Content data

- `content/projects.js` contains project titles, roles, descriptions, tags and media paths.
- `content/professional-profile.js` contains the concise About / Experience data.
- `content/vfx-credits.js` contains the Film & VFX professional entries and verified film metadata.

## Asset rules

- `_placeholders` is temporary and must not be treated as the final portfolio archive.
- Do not store original master files in the web project. Keep masters in the appropriate source or production archive outside this repository.
- Web assets must be derived, resized, compressed and optimized for their actual use before being added here.
- Keep only the files required by the local site and remove exact duplicates when they are genuinely identical.
- Keep `assets/fonts/Manrope/` as the local source for the site's typography.

## Publishing rule

This portfolio must remain local until Francesco Zaccone gives explicit authorization to publish or deploy it. Do not publish, deploy, connect a public domain or make the site public without that authorization.
