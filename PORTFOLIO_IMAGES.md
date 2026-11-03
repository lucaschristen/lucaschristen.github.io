# Adding figures and photographs to the portfolio

The Research and Engineering pages use a reusable case-study layout.
Each section reserves a large **16:10 image / diagram slot**. When an image path
is empty, the site shows a styled placeholder rather than a broken image.

## Add a photo in three steps

1. Upload your original image to `assets/img/portfolio/research/` or
   `assets/img/portfolio/engineering/` in this repository.
2. Open the corresponding file:
   - Research: `_data/research_portfolio.yml`
   - Engineering: `_data/engineering_portfolio.yml`
3. Find the relevant `id:` and set the `image` field, for example:

   ```yaml
   image: "/assets/img/portfolio/engineering/laser-vacuum-system.webp"
   image_alt: "Laser and vacuum processing apparatus with labelled optical ports"
   image_caption: "Laser-heating platform (laboratory photograph)"
   ```

The section automatically shows your image, caption and the existing short
technical description. The same file may be edited via GitHub Desktop or ChatGPT.

## Recommended figures for each section

| Page        | Section ID                | Preferred material                                                                 |
| ----------- | ------------------------- | ---------------------------------------------------------------------------------- |
| Research    | `laser-vaporization`      | Laser-irradiated regolith or chamber photo (an original image is already supplied) |
| Research    | `enrichment`              | Samples before/after processing + composition plot                                 |
| Research    | `temperature-diagnostics` | Pyrometry/spectrometer layout or temperature trace                                 |
| Research    | `numerical-analysis`      | Model prediction of residue composition or energy balance                          |
| Engineering | `vacuum-platform`         | Annotated full vacuum/lasing system photo                                          |
| Engineering | `pid-software`            | PID graphical interface screenshot and control-flow diagram                        |
| Engineering | `optical-instrumentation` | Annotated optical path with focal lengths and filters                              |
| Engineering | `numerical-tools`         | Numerical model flow diagram and result graph                                      |
| Engineering | `collection-systems`      | Heated collector plate and diagnostics setup                                       |

## Quality and publication checks

- Prefer WebP or optimized JPEG for photos; PNG or SVG for diagrams with sharp text.
- Export around 1600–2000 px wide with a 16:10 landscape crop for the large image slots.
- Aim for under 500 KB per image when possible; avoid multi-megabyte raw photos.
- Provide descriptive `image_alt` text for accessibility; the caption is optional.
- Use original or explicitly permitted imagery. Remove personal identifiers and
  unpublished/confidential laboratory content from photos and screenshots.
- In scientific plots, retain units, axes, legends and uncertainties as appropriate.
- Check the site on desktop and mobile after a GitHub Pages deployment.

## Other content

- Papers and conference entries: `_data/academic_works.yml`
- The Jekyll Scholar-compatible bibliography: `_bibliography/papers.bib`
- Portfolio section renderer: `_includes/portfolio/showcase.liquid`
- Portfolio-specific CSS: `assets/css/portfolio-detail.css`

The bibliography and the academic record are maintained manually so verify new
researchmap entries before updating both.
