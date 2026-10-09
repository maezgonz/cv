# cv

![Render](https://github.com/maezgonz/cv/actions/workflows/render.yml/badge.svg)

Curriculum vitae: **Systems Engineer → High-Performance Computing & Quantitative Analysis**.

## Layout

```text
cv/
├── CV.qmd                  # CV source (quarto markdown)
├── MATIAS_GONZALEZ_CV.md   # plain markdown version
└── .github/workflows/render.yml   # CI: renders the PDF on every push
```

## The PDF

The PDF renders automatically on every push:

- **Artifact**: Actions tab → latest run → `cv-pdf` artifact
- **Release**: on version tags (`git tag v1 && git push --tags`) → [Releases](https://github.com/maezgonz/cv/releases) with the PDF attached
