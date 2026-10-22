# Shiloh Cadere — Professional Portfolio

**Professional bioinformatics and software portfolio** focused on genomics quality review, reproducible sequencing workflows, laboratory informatics, and analytical software.

**Live website:** https://shilohcadere.github.io/

## Purpose

This site documents selected technical work through project case studies, implementation decisions, and limitations. It also presents laboratory experience, education, technical skills, and ways to connect about relevant opportunities.

The featured bioinformatics repositories are independent portfolio implementations using simulated or demonstration data, not production clinical systems. The Furlong case study describes work on its `feature/saved-options-panel` development branch rather than the older default branch.

## Selected work

- [Clinical NGS Review](https://github.com/ShilohCadere/clinical-ngs-review) — Configurable QC assessment and analyst-facing reporting.
- [Clinical NGS Workflow](https://github.com/ShilohCadere/clinical-ngs-workflow) — Nextflow/Docker sequencing workflow.
- [Barcode Crossover Analysis](https://github.com/ShilohCadere/ont-barcode-crossover-analysis) — Oxford Nanopore sequencing analysis demonstration.
- [Laboratory LIMS Database](https://github.com/ShilohCadere/laboratory-lims-database) — Oracle SQL laboratory data model.
- [Genomic Toolkit](https://github.com/ShilohCadere/Genomic-Toolkit) — Python sequence-analysis CLI.
- [Furlong technical case study](https://shilohcadere.github.io/work/furlong/) — Application development documented from a private source repository.

## Relationship to Cadere Productions

[Cadere Productions](https://shilohcadere.github.io/cadere-productions/) is a separate independent studio for practical software and imaginative interactive experiences. The studio presents Furlong as a product; this professional website discusses its technical implementation. The two sites share a complementary visual language but serve different audiences.

## Local editing and publication

This is a static HTML/CSS/JavaScript site. Edit `index.html`, case-study directories under `work/`, and assets in `assets/`. Preview with a local static HTTP server rather than opening files directly.

GitHub Pages serves the user site from `main` at the repository root; enable this in **Settings → Pages → Deploy from a branch** if necessary. Keep `.nojekyll` to prevent Jekyll processing. Root-relative links intentionally point to `/`.

Screenshots use development or example data, not private account records. Do not commit databases, credentials, secrets, or session files.

© 2026 Shiloh Cadere. Linked projects retain their own licenses.
