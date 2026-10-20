# [Project Name]

> **One-line pitch:** [Who is this for, and what job does it do for them?]

- **Builder:** [Your Name] (`@github-handle`)
- **Pod:** [Pod Name / Number]
- **Product Landing Page & Living PRD (GitHub Pages):** [https://building-with-ai-f26.github.io/<your-repo-name>/](#)
- **Live App URL:** [https://your-live-url.com](#)

---

## Turn On Your Free Single-Page Product Site (Do This in Week 1!)

Your repository comes with a ready-made single-page Product Site at [`docs/index.html`](./docs/index.html). It acts as your **public product landing page**, your **living PRD**, your **weekly build log**, and the home for your **PostHog analytics snippet**.

To make it live on the internet in 30 seconds:
1. On your GitHub repository page, click **Settings** (top tab) -> **Pages** (left sidebar).
2. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
3. Select branch **`main`** and folder **`/docs`**, then click **Save**.
4. Within 60 seconds, your site will be live at `https://building-with-ai-f26.github.io/<your-repo-name>/`.

---

## Repository Map

| File / Folder | Purpose | Updated |
| :--- | :--- | :--- |
| [`docs/index.html`](./docs/index.html) | **Single-Page Product Site:** Public pitch, Living PRD, PostHog analytics snippet, and Weekly Build Log | Every week ($\ge 2$ commit days/wk) |
| [`Intent.md`](./Intent.md) / [`Plan.md`](./Plan.md) | Markdown scratchpads for your initial spec & architecture plan (kept in sync with your Product Page PRD) | Weeks 1–2 |
| [`AGENTS.md`](./AGENTS.md) | Operating manual & rules for your coding agent (`Claude Code`, `Codex`, or `Pi`) | Week 2+ |
| [`tests/`](./tests/) | **Build 4:** 10-scenario test scorecard and automated checks | Mon, Nov 30 @ Noon |
| [`journal/`](./journal/) | Weekly build journal notes (can be linked from or mirrored on `docs/index.html`) | Every Monday @ Noon |
| [`SPONSOR_MEMO.md`](./SPONSOR_MEMO.md) | **Final Write-up:** 1-page executive call (`Invest`, `Maintain`, or `Sunset`) backed by PostHog & cost data | Mon, Dec 14 @ Noon |

---

## Local Setup

```bash
# 1. Clone your repo
gh repo clone building-with-ai-f26/<your-repo-name>
cd <your-repo-name>

# 2. Configure environment variables (never commit .env!)
cp .env.example .env

# 3. Install dependencies & run
# [Ask your coding agent to add your exact run command here]
```
