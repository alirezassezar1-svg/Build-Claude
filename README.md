# Build-Claude

NONONICK ADMIN OS — a single-file, browser-only visual page editor.

- `index.html` — the editor (open directly, or deploy to cPanel)
- `site/` — pages published from the editor's GitHub panel
- `.cpanel.yml` — cPanel Git deployment (editor → `public_html/admin-os/`, site → `public_html/build-site/`)

Protect `/admin-os/` with cPanel **Directory Privacy**: the editor has no login of its own.
