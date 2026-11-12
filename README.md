# TrustSec AI Lab Website

A static website for the TrustSec AI Lab at the University at Albany, built as a course project for CYBR 201 (Web Technology Essentials) in Spring 2026.

The site introduces the lab's mission, research areas, collaboration opportunities, and members.

## Pages

| File | Content |
|---|---|
| `index.html` | Lab overview, research highlights, contact information |
| `mission.html` | Mission and strategic direction |
| `foundational-work.html` | Machine learning and AI security areas behind the lab's work |
| `research-focus.html` | Active research themes (adversarial AI, privacy, LLM safety) |
| `why-it-matters.html` | Why trustworthy AI security research matters |
| `collaboration.html` | Ways to collaborate with the lab |
| `people.html` | Principal investigator and student researchers |

## Built with

- HTML and CSS (`css/theme.css` holds the custom styling)
- Bootstrap 2 and jQuery for the responsive grid, navigation, and image carousel
- GitHub Pages for hosting, served straight from the `main` branch

## Run locally

No build step is needed. From the repository root:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Notes

- Photos, names, and lab content belong to the TrustSec AI Lab.
- The bundled jQuery (1.9.1) is old and has known XSS issues; it's kept only because the Bootstrap 2 carousel depends on it. A future update would move to a current Bootstrap/jQuery or drop jQuery entirely.
