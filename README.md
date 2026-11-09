# Faculty Digital Accessibility Research Hub

**Pilot V26 — faculty review release**

A static, faculty-oriented accessibility guidance website for mathematics and statistics teaching. Includes PDF and handwritten notes workflows, Canvas, videos and captions, equations and graphs, web app checks, color contrast, student support, accessibility law and student rights, and practical search/navigation.

## Files

- `index.html` — complete website, including styles, JavaScript, and search.
- `examples/EL2-Guided-Notes.pdf` — PDF used by the site's example link.
- `netlify.toml` — optional Netlify static site configuration.

## Deploy to GitHub and Netlify

1. Create a new GitHub repository (for example, `faculty-accessibility-hub`).
2. Upload the **contents of this folder** to the repository root. Keep `index.html` at the root and retain the `examples` directory.
3. In Netlify, choose **Add new project → Import an existing project**, connect GitHub, and select your repository.
4. For a static site, leave the build command blank. The publish directory is `.` (repository root). Deploy.
5. Open the Netlify URL and test homepage navigation, search, interactive tools, and the example PDF link.

You can also drag the unzipped folder into Netlify's manual deploy interface; GitHub integration is better for future updates.

## Notes for reviewers

This is a faculty pilot and research aid, **not** an official institutional policy or accessibility certification. Automated tests and AI-generated remediation require human verification. Before broad release, test the live website with keyboard and screen readers and obtain appropriate campus accessibility review.

No backend, account, AI API, or build tooling is required. External resource links require internet access.
