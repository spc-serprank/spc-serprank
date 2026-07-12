<h1 align="center">SEO Pro Check</h1>

<p align="center">
  <strong>Open-source SEO &amp; AI-search tooling — built by a practitioner, not a marketer.</strong><br>
  <em>Small, sharp, zero-fluff tools for the search era that's actually happening: Google, Bing, and the AI answer engines.</em>
</p>

<p align="center">
  <a href="https://spc-serprank.github.io">🧰 41 live tools</a> &nbsp;·&nbsp;
  <a href="https://github.com/spc-serprank?tab=repositories">📦 Repos</a> &nbsp;·&nbsp;
  <a href="https://seoprocheck.com">🌐 seoprocheck.com</a>
</p>

<p align="center">
  <img alt="Focus" src="https://img.shields.io/badge/focus-SEO%20%2B%20GEO%2FAEO-6E56CF">
  <img alt="20 years" src="https://img.shields.io/badge/experience-20%2B%20years%20in%20search-111111">
  <img alt="Style" src="https://img.shields.io/badge/tools-zero%20fluff%2C%20zero%20bloat-2EA043">
</p>

---

### 👋 What this is

Twenty years in the trenches of technical and content SEO — for global brands and small sites alike — distilled into **free, focused tools you can actually run.** Each one does a single job that a bloated all-in-one suite buries three menus deep, and each is built for **where search is going**: not just Googlebot, but ChatGPT, Perplexity, Claude, Gemini, and Google's AI Overviews.

No sign-ups. No "book a demo." No 14-day trial that charges your card. Clone it, run it, own the output.

---

### 🧰 41 free SEO &amp; GEO tools — live in your browser

<p>
  <a href="https://spc-serprank.github.io"><strong>▶ spc-serprank.github.io</strong></a> — a searchable hub of <strong>41 client-side tools</strong>: schema generators, SERP &amp; social previews, robots/hreflang/sitemap builders, AI-crawler &amp; llms.txt tools, content analyzers, and developer utilities. Pure static HTML/JS — no backend, no tracking, nothing to break.
</p>

### ⭐ Featured tools — command-line

<table>
<tr>
<td width="30%"><strong><a href="https://github.com/spc-serprank/ai-crawler-audit">ai-crawler-audit</a></strong></td>
<td>Audit any site's <code>robots.txt</code> for <strong>AI/LLM crawler policy</strong>. Most sites that "block AI" only block GPTBot — meanwhile ClaudeBot, PerplexityBot, Google-Extended and 20+ others walk right in. This shows the gap in one command. Tracks 27 AI crawlers across training, AI-search, and assistant-fetch. Zero dependencies.</td>
</tr>
</table>

```console
$ python3 ai_crawler_audit.py example.com
  ● BLOCKED  GPTBot            OpenAI
  ○ allowed  ClaudeBot         Anthropic   (not named)   ← the silent gap
  ...
  3/27 AI crawlers blocked · 14.8% coverage
  ⚠ You address some AI bots but not all.
```

---

### 🧰 The toolkit

A growing set of single-purpose tools across the modern search stack. **Shipped** are live and runnable today; the rest are in active build order.

| Tool | What it does | Status |
|---|---|---|
| **[ai-crawler-audit](https://github.com/spc-serprank/ai-crawler-audit)** | Which of 27 AI bots your `robots.txt` really allows/blocks | ✅ **Shipped** |
| **[llms-txt-kit](https://github.com/spc-serprank/llms-txt-kit)** | Validate + generate the emerging `llms.txt` standard | ✅ **Shipped** |
| **[hreflang-check](https://github.com/spc-serprank/hreflang-check)** | Language-aware hreflang reciprocity validator | ✅ **Shipped** |
| **content-decay** | Flag pages bleeding impressions — with *enrich, don't prune* guidance | 🔨 Building |
| **serp-schema-gap** | Compare your schema against the pages outranking you | 📋 Planned |
| **redirect-chain-fixer** | Find chains/loops, output ready-to-paste `.htaccess`/nginx rules | 📋 Planned |
| **cwv-field-vs-lab** | CrUX (real users) vs Lighthouse (lab), divergence flagged | 📋 Planned |
| **cannibalization-map** | Find URLs competing for one query + a merge call | 📋 Planned |

<sub>Full roadmap of 20 tools tracked in the repositories tab. Built in public — starring a repo bumps it up the queue.</sub>

---

### 🛠️ Built with

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white">
  <img alt="Google Search Console" src="https://img.shields.io/badge/Search%20Console-4285F4?logo=google&logoColor=white">
  <img alt="Bing Webmaster" src="https://img.shields.io/badge/Bing%20WMT-008373?logo=microsoftbing&logoColor=white">
  <img alt="MCP" src="https://img.shields.io/badge/Model%20Context%20Protocol-000000">
</p>

Data-driven SEO — Search Console & Bing WMT APIs, log-file analysis, structured data, Core Web Vitals, and AI-search/GEO measurement. Tools are built to be **composable and scriptable**, not locked in a dashboard.

---

<p align="center">
  <sub>Free & open source · MIT licensed · <a href="https://seoprocheck.com">seoprocheck.com</a></sub>
</p>
