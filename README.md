# Krasis — website

The public pages for **Krasis**, an iPhone app that tells you whether what
you're about to eat will hold you, and what one thing to add if it won't.

κρᾶσις — *the blending of elements in due proportion*.

| Page | URL |
|---|---|
| Landing | <https://stavrop.github.io/krasis/> |
| Privacy Policy | <https://stavrop.github.io/krasis/privacy.html> |
| Terms of Use | <https://stavrop.github.io/krasis/terms.html> |
| Support | <https://stavrop.github.io/krasis/support.html> |

The privacy and terms URLs are linked from the app's paywall and are what App
Store Connect points at, so **they must not move**. Rename a file and you break
a shipped build.

## How it's published

GitHub Pages, from `main` → `/docs`. Push and it redeploys; a build takes about
a minute.

Plain HTML and one stylesheet — no build step, no framework, no external fonts
or scripts, so the pages themselves make no third-party requests. That is a
claim the privacy policy relies on; keep it true.

The tokens in `docs/style.css` are lifted from the app's design spec
(`docs/design/core-loop.html` in the app repo): paper, ink, one terracotta
accent, serif for meaning and sans for chrome. **No second colour** — the app's
rule, and it applies here.

The app itself is a separate, private repository.
