## Learned User Preferences

- Rephrase user-provided wording instead of pasting it verbatim. Keep a professional tone; no slang or overly casual phrasing.
- Avoid AI tells such as em dashes, LaTeX `---` asides, and "agent slop" constructions. Prefer concrete outcomes (for example, "to reduce unintended regressions").
- Do not invent job titles that would fail a background check.
- After editing `alin_ali_hassan.tex`, compile the PDF and verify it is current before considering the work done.
- Do not add name or page-number footers on this software resume.

## Learned Workspace Facts

- Source of truth is `alin_ali_hassan.tex`. Compile with `docker run --rm -i -v "$PWD":/data sotetsuk/pdflatex pdflatex alin_ali_hassan.tex`.
- The resume is a two-page layout: experience on page 1, education/projects/skills on page 2, no footer.
- Official Booking.com title is Software Engineer (Amsterdam); still employed there. Do not write Senior.
