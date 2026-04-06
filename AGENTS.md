# AGENTS.md

Scope: entire repository.

## Editing rules
- Keep the site as a static, dependency-free project unless explicitly requested.
- Preserve accessibility and readability for Hindi/English mixed content.
- Do not remove legal disclaimer, terms, privacy/safety notes, or doctor-escalation section.
- Preserve SEO tags and JSON-LD unless replacing with a better validated equivalent.

## SEO rules
- Maintain one canonical URL and keep it consistent with `sitemap.xml` and `robots.txt`.
- Keep FAQ content synchronized with FAQ JSON-LD where practical.
- Avoid keyword stuffing; prefer helpful, user-first copy.

## Validation checklist (before commit)
- `index.html` has exactly one `<!DOCTYPE html>` and one closing `</html>`.
- `sitemap.xml` parses as valid XML.
- `robots.txt` includes a sitemap reference.

## Commit expectations
- Use concise, descriptive commit messages.
- Mention user-visible changes in the final summary.
