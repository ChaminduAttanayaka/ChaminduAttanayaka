# GitHub Profile Setup

This package is ready for the special GitHub profile repository:

`ChaminduAttanayaka/ChaminduAttanayaka`

## Repository structure

```text
ChaminduAttanayaka/
├── README.md
├── assets/
│   └── hero.svg
└── PROFILE-SETUP.md
```

## Option 1 — Existing profile repository

```bash
git clone https://github.com/ChaminduAttanayaka/ChaminduAttanayaka.git
cd ChaminduAttanayaka
```

Copy `README.md` and the `assets` directory from this package into the repository, then run:

```bash
git add README.md assets/hero.svg
git commit -m "feat: redesign GitHub engineering portfolio"
git push origin main
```

## Option 2 — New repository

Create a new **public** GitHub repository named exactly:

`ChaminduAttanayaka`

Then:

```bash
git clone https://github.com/ChaminduAttanayaka/ChaminduAttanayaka.git
cd ChaminduAttanayaka
```

Copy the package files into it and push:

```bash
git add .
git commit -m "feat: add GitHub engineering portfolio"
git push origin main
```

## Recommended GitHub profile bio

`DevOps Engineer | Cloud & Platform Engineering | AWS • Azure • Kubernetes • Terraform • Jenkins`

## Notes

- Keep the repository public.
- Do not rename `README.md`.
- Keep `assets/hero.svg` in the same relative location.
- GitHub profile repositories display `README.md` automatically on the main profile.
