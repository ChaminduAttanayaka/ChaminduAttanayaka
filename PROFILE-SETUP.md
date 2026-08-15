# Animated GitHub Portfolio — Setup

This package is designed for the special GitHub profile repository:

`ChaminduAttanayaka/ChaminduAttanayaka`

## Structure

```text
ChaminduAttanayaka/
├── README.md
├── PROFILE-SETUP.md
└── assets/
    ├── hero.svg
    ├── engineering-focus.svg
    ├── technology-matrix.svg
    ├── featured-engineering.svg
    ├── certifications.svg
    └── footer.svg
```

## Install

If the profile repository already exists:

```bash
git clone https://github.com/ChaminduAttanayaka/ChaminduAttanayaka.git
cd ChaminduAttanayaka
```

Copy all files from this package into the repository.

Then:

```bash
git add README.md PROFILE-SETUP.md assets/
git commit -m "feat: add animated GitHub engineering portfolio"
git push origin main
```

## Important GitHub limitation

GitHub strips normal webpage CSS and JavaScript from README files. This portfolio therefore uses self-contained SVG animations, which is the most practical way to create an animated GitHub profile while staying inside GitHub's README renderer.

The repository links remain normal Markdown links below the visual Featured Engineering section because links inside an embedded SVG image are not reliably interactive when rendered by GitHub.
