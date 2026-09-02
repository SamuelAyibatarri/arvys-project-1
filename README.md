# Atelier — Fire & Grain | Wood-Fired Bistro

Restaurant webpage for **Atelier**, a small wood-fired bistro on 5th (fictional). Built as coursework for "Build a Simple Webpage with AI, Git & GitHub".

Live site: open `index.html` locally or via GitHub Pages (enable Pages on `main` branch if needed).

## About the Webpage

- **Subject:** Wood-fired neighbourhood bistro — thesis is open flame (hero: oven + flicker + kitchen ticket). Sections: hero, about, kitchen ticket menu (signature), hours/location, reservation contact, footer.
- **Design system:** 6 tokens (`ink #141A1F`, `cream #F8F6F0`, `paper #FFFFFF`, `blue #206EE3` from logo, `ember #C45A3C`, `brass #C9A86A`, `sage #7A8B7A`), display `Cormorant Garamond` + body `Inter` + mono `JetBrains Mono`, signature perforated kitchen ticket with ember hover.
- **Assets:** `assets/logoipsum-438.svg` (provided generic logo, blue #206EE3) + inline Lucide SVGs (no external icon font, self-contained).
- **Stack:** Pure HTML + CSS, Google Fonts, no build step. Responsive (900px/600px/380px), `prefers-reduced-motion` respected, keyboard focus visible, semantic HTML.

## AI Tool Used

**Muse Spark — `muse-spark-1.2-contributor-free`** (via OpenCode).

## How AI Helped

- **Initial webpage:** generated semantic skeleton (`header/nav/main/section/footer`, hero/about/menu/hours/contact).
- **Improve structure:** refined semantics, added skip-link, ARIA labels, meta description, font preconnects.
- **CSS styling:** proposed token system derived from logo blue, typography pairing, ticket signature, oven/flame hero, hover/transition system.
- **Images/icons:** suggested Lucide inline SVGs (self-contained, styleable), placement in nav/meta/visit/contact, logo integration (`nav__brand` + wordmark).
- **Responsiveness:** breakpoints, grid→stack, stacked hero on mobile, fluid `clamp()` title, touch-friendly buttons.
- **Final polish:** HTML validation fixes (`html-validate`), non-breaking hyphen/space in tel, inline-style removal, reduced-motion guard, focus states, commit sequencing per rubric. Also applied **frontend-design skill** (`.agents/skills/frontend-design`) — deliberate palette/type/layout critique to avoid generic defaults.

## Requirements (as per brief)

1. Use AI to generate initial webpage (examples: profile/restaurant/school/product/portfolio) — **done: restaurant "Atelier" via Muse Spark**.
2. Create local Git repository — **done: `git init` + connected to `https://github.com/SamuelAyibatarri/arvys-project-1.git`**.
3. Make ≥5 meaningful commits while improving — **done (6 commits):**
   - `Initial webpage`
   - `Improve page structure`
   - `Add CSS styling`
   - `Add images/icons`
   - `Improve responsiveness`
   - `Fix errors and final improvements` (this README + validations)
4. Create GitHub repo and push — **done: `origin/main` → `https://github.com/SamuelAyibatarri/arvys-project-1`**.
5. Repo must contain: webpage files, `README.md`, clear history ≥5 — **files: `index.html`, `styles/style.css`, `assets/logoipsum-438.svg`, `README.md`**; verify with `git log --oneline`.
6. `README.md` must state: what webpage about, which AI used, how AI helped — **sections above**.

**Submission:** submit GitHub repo URL via portal. Commit history checked — commits made sequentially, not squashed at end.

## Project Structure

```
index.html
styles/style.css
assets/logoipsum-438.svg
README.md
```

## Run Locally

```bash
git clone https://github.com/SamuelAyibatarri/arvys-project-1.git
cd arvys-project-1
open index.html  # or python -m http.server
```

## Verification

```bash
git log --oneline   # ≥6 commits
npx html-validate index.html  # 0 errors
```

## Commit History

Check `git log --oneline` — commits are intentional and incremental per rubric.
