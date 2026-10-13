# Xingyu Zhang — Academic Homepage (Private Draft)

This is a standalone academic homepage inspired by the two-column **Academic Portfolio Astro** layout and the restrained Minimal Light palette (white, dark navy, soft blue). It is an original static HTML/CSS implementation, not a fork of the Astro source.

## Status

**PRIVATE DRAFT.** This repository must remain Private. **Do not enable GitHub Pages or switch it to Public** until the owner explicitly approves the finished site. A noindex directive is included for review but is not an access-control mechanism.

## Content

- About: Ph.D. student at ISCAS / UCAS, advised by Changwen Zheng and Wenwen Qiang; contact email authorized for publication.
- Research interests: time-series forecasting, causal and structural modeling, LLM-based modeling; newer interests in agentic RL and World Action Models (WAMs), without presenting submitted work as accepted.
- News, six Selected Publications, Education, Honors & Awards.
- No Projects & Code section.

## Editing

Update `index.html` for biographies, dates, papers, news and links. The palette and responsive layout are in `assets/styles.css`. To preview locally run `python3 -m http.server 8000` and visit http://localhost:8000/.

## Award attachment limitation

The website includes `assets/ebmv-2026-award-summary.svg`, a **clearly labeled illustrated summary**, based on the supplied EBMV 2026 third-place award. **It is not the official certificate image**. The original high-resolution PDF is included in the separately supplied local ZIP but is not uploaded through this text-only connector. After approval, upload `assets/ebmv-2026-award.pdf` from the local ZIP using GitHub's browser upload or Git, then replace the summary link in `index.html` with that exact file path. Do not publish a broken PDF link.

## Publishing checklist

1. Verify the bio, advisor affiliations and author lists; use a preferred headshot if desired.
2. Upload the original certificate PDF if you want a link to it.
3. Explicitly approve publishing; only then change the repository visibility and enable GitHub Pages.
4. Only once approved for search indexing, change `<meta name="robots" content="noindex,nofollow">` and `robots.txt`.
