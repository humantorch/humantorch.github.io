This is a personal blog/writing vault built on Hugo with the PaperMod theme, focused on engineering management and leadership writing. It doubles as an Obsidian vault for drafting and a Hugo site source for publishing.

## Structure

- **content/**: All site content (17 notes)
  - **content/post/blog/**: Published blog posts on management/leadership topics
  - **content/post/**: Top-level pages (`about.md`, `blog.md`, `journey.md`, `testpage.md`, `readme.md`)
  - `_index.md`: Site homepage content
- **themes/PaperMod**: Vendored Hugo theme, not vault content to edit
- **archetypes/**: Hugo archetype template(s) for scaffolding new content
- **(vault root)**: `README.md`

## Conventions

- Post titles use lowercase, hyphenated slugs (e.g. `so-youre-a-manager-now-performance-management.md`)
- Some posts form explicit series, e.g. "So You're a Manager Now" (base post plus "-performance-management" and "-influence-without-authority" installments)
- Tags cluster around leadership/management themes: `#leadership` (9), `#career` (6), `#management` (5), `#engineering` (4), `#mentoring` (3) are most common, alongside a long tail of single-use tags
- Frontmatter drives Hugo publishing, so notes are both content and site source files — treat frontmatter fields as functional, not just metadata