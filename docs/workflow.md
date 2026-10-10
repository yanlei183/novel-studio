# Novel Studio

A multi-book, multi-genre, multi-length writing workspace for organizing novels, outlines, characters, worldbuilding, scenes, and ideas.

## Project purpose

This repository is designed for:

- managing multiple novels at the same time
- separating different genres and worlds
- tracking long-term drafts and writing progress
- standardizing project structure across different stories
- supporting future AI-assisted writing workflows

## Repository structure

```text
novel-studio/
├── README.md
├── docs/
│   ├── workflow.md
│   ├── conventions.md
│   └── naming.md
├── templates/
│   ├── novel-outline.md
│   ├── character-card.md
│   ├── worldbuilding.md
│   ├── chapter-template.md
│   ├── scene-template.md
│   └── series-index.md
├── projects/
│   ├── project-template/
│   │   ├── README.md
│   │   ├── outline.md
│   │   ├── characters/
│   │   │   └── README.md
│   │   ├── world/
│   │   │   └── README.md
│   │   ├── chapters/
│   │   │   └── README.md
│   │   ├── notes/
│   │   │   └── README.md
│   │   ├── references/
│   │   │   └── README.md
│   │   └── timeline.md
│   ├── project-01/
│   ├── project-02/
│   └── ...
├── library/
│   ├── ideas/
│   ├── references/
│   ├── scenes/
│   ├── styles/
│   └── tags.md
├── tools/
│   ├── checklist.md
│   ├── timeline.md
│   ├── index.md
│   └── release-checklist.md
├── .gitignore
└── LICENSE
```

## Recommended usage workflow

1. Create a project under `projects/` for each novel or series.
2. Fill in `outline.md` with the main premise, arc, and structure.
3. Use `characters/` and `world/` to document key people and setting.
4. Write chapters under `chapters/` using numbered names.
5. Keep ideas and loose notes in `notes/` and `library/`.
6. Use `tools/` to manage checklists, timelines, and release readiness.

## Suggested project types

- Long-form novels
- Short stories
- Series and sequels
- Fantasy, sci-fi, romance, mystery, thriller, horror, slice-of-life
- AI-assisted drafting and revision workflows

## Writing standards

- Each project should have a clear README
- Keep chapters numbered and consistent
- Use a single naming convention across all works
- Separate worldbuilding from chapter drafts
- Keep raw inspiration separate from final content

## Future expansions

This repository can grow into a more complete writing system later, for example:

- AI writing assistant scripts
- chapter generation templates
- relation graph or character map tools
- timeline manager
- export tools for manuscript formatting
- publishing pipeline for ebook or print

## Quick start

```bash
mkdir -p projects/project-template/characters projects/project-template/world projects/project-template/chapters projects/project-template/notes projects/project-template/references
```

Then copy the templates from `templates/` and fill in your own materials.

## Maintainer

- GitHub: @yanlei183
