# Example Academic Websites and Design Rationale

To design this site, I surveyed the personal pages of five researchers working in AI security / LLM safety,
covering different career stages (Ph.D. student, postdoc, industry researcher, and faculty).

| # | Researcher | Career stage | Site | Notes on structure |
| --- | --- | --- | --- | --- |
| 1 | Andy Zou | Ph.D. student, CMU (AI safety, adversarial attacks on LLMs) | https://andyzoujm.github.io | Single page: short bio + photo, "What's New", research list with paper thumbnails |
| 2 | Xiaogeng Liu | Ph.D. student, Johns Hopkins (trustworthy AI, jailbreaks) | https://xiaogeng-liu.com | Sections for About, News, Preprints, Publications, Honors, Education |
| 3 | Alex Robey | Former CMU postdoc, now industry (jailbreak defenses, robustness) | https://arobey1.github.io | Highlights, Papers, Press, Talks, Posts, Teaching |
| 4 | Florian Tramèr | Assistant Professor, ETH Zürich (ML security & privacy) | https://floriantramer.com | Multi-page: Home, Publications, Talks, Teaching, CV, Blog |
| 5 | Chaowei Xiao | Assistant Professor, Johns Hopkins (safe and secure AI agents) | https://xiaocw11.github.io | Home / About / Publications; news list and research directions on the landing page |

## Common patterns I adopted

1. **Landing page = photo + one-paragraph bio + contact.** Every example puts the name, position, affiliation and a clear headshot above the fold.
2. **News feed** with short dated items on the front page (Zou, Liu, Xiao).
3. **A separate publications page** generated from a single source of truth (BibTeX), with venue badges.
4. **A research page organized by theme** rather than a flat list of projects (Robey, Xiao).

6. **Prominent academic profile links:** Google Scholar, GitHub, email, LinkedIn/ORCID.

## Resulting structure (al-folio)

- **about** (landing): headshot, office address, email, bio, research interests, news, selected publications, social icons
- **research**: overview + three research directions with project descriptions
- **publications**: generated from `_bibliography/papers.bib`

