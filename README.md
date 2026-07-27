# The Upwelling Project website

Quarto website for The Upwelling Project, an Oceania-based initiative backing
the next generation of ocean leaders through training and practical
experience.

## Pages

- Home
- What we offer
- Eligibility and how to apply
- Contact

## Preview locally

Open `upwelling_website.Rproj`, then run:

```bash
quarto preview
```

The site uses a single light theme defined in `theme.scss`.

## Publishing

The GitHub Pages workflow in `.github/workflows/publish.yml` renders and
deploys the site after pushes to `main`. In the repository settings, set Pages
to use **GitHub Actions** as its source.

## Content to confirm before launch

- `eligibility.qmd` now defines "early-career" using the UN Ocean Decade ECOP
  Programme definition (≤10 years of ocean-related professional experience),
  cited from Vozzo et al. (2025), *Frontiers in Ocean Sustainability*. Confirm
  the board wants to adopt this definition as-is.
- `application.qmd` is a **mock-up** application form (disabled inputs, no
  submission) so applicants can preview what's required. Replace it with a
  live form (e.g. Google Forms, Typeform, or a backend) before 1 November 2026.
- `contact.qmd` uses a **placeholder** email, `hello@theupwellingproject.org`.
  Replace it with the organisation's approved, monitored inbox before launch.
