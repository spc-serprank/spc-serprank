<div align="center">

# SEO Pro Check

Free, open-source tools for technical SEO and AI search.<br>
Built in public by a search practitioner — 20 years in, still shipping.

[seoprocheck.com](https://seoprocheck.com) · [**41 browser tools →**](https://seoprocheck.github.io) · [repositories](https://github.com/seoprocheck?tab=repositories)

</div>

---

Every tool here does one job well, runs with **zero dependencies**, and never asks for a sign-up. The command-line tools are plain Python — clone and run. The browser tools are static pages — open and use. All MIT.

## Command-line tools

<details open>
<summary><strong>AI crawlers &amp; answer engines</strong> — the GEO toolkit</summary>
<br>

| | Tool | What it does |
|:-:|------|--------------|
| <img src="icons/ai-crawler-audit.svg" width="20" alt=""> | [ai-crawler-audit](https://github.com/seoprocheck/ai-crawler-audit) | Which of 27 AI bots your `robots.txt` really allows or blocks — real matching rules, not substring guesses |
| <img src="icons/llms-txt-kit.svg" width="20" alt=""> | [llms-txt-kit](https://github.com/seoprocheck/llms-txt-kit) | Validate and generate `llms.txt`, the map that tells AI models what your site is |
| <img src="icons/log-crawl-analyzer.svg" width="20" alt=""> | [log-crawl-analyzer](https://github.com/seoprocheck/log-crawl-analyzer) | Crawl-budget report from your server logs — Googlebot to GPTBot, waste % included |
| <img src="icons/ai-overview-checker.svg" width="20" alt=""> | ai-overview-checker | Which of your keywords trigger AI Overviews, and whether you're cited *(planned)* |
| <img src="icons/geo-visibility-tracker.svg" width="20" alt=""> | geo-visibility-tracker | Share-of-voice inside ChatGPT / Perplexity / Gemini answers over time *(planned)* |

</details>

<details>
<summary><strong>Search Console intelligence</strong> — what GSC won't show you directly</summary>
<br>

| | Tool | What it does |
|:-:|------|--------------|
| <img src="icons/content-decay.svg" width="20" alt=""> | [content-decay](https://github.com/seoprocheck/content-decay) | Finds pages bleeding traffic, diagnoses why, prescribes enrichment — never pruning |
| <img src="icons/cannibalization-map.svg" width="20" alt=""> | [cannibalization-map](https://github.com/seoprocheck/cannibalization-map) | Finds your URLs competing for the same query, with a concrete consolidate/differentiate call |

</details>

<details>
<summary><strong>Technical SEO</strong> — redirects, hreflang, headers</summary>
<br>

| | Tool | What it does |
|:-:|------|--------------|
| <img src="icons/redirect-chain-fixer.svg" width="20" alt=""> | [redirect-chain-fixer](https://github.com/seoprocheck/redirect-chain-fixer) | Traces chains and loops, then emits the exact `.htaccess`/nginx rule that collapses each one |
| <img src="icons/hreflang-check.svg" width="20" alt=""> | [hreflang-check](https://github.com/seoprocheck/hreflang-check) | Catches the missing return tag that makes Google ignore hreflang clusters — language-aware |

</details>

<details>
<summary><strong>Structured data</strong> — beyond "is it valid"</summary>
<br>

| | Tool | What it does |
|:-:|------|--------------|
| <img src="icons/schema-gap.svg" width="20" alt=""> | [schema-gap](https://github.com/seoprocheck/schema-gap) | Diffs your schema against the pages outranking you — missing types and properties |
| <img src="icons/bulk-schema-validator.svg" width="20" alt=""> | [bulk-schema-validator](https://github.com/seoprocheck/bulk-schema-validator) | Validates JSON-LD across a whole sitemap — required properties for 17 rich-result types |

</details>

<details>
<summary><strong>Performance</strong> — the numbers Google actually ranks on</summary>
<br>

| | Tool | What it does |
|:-:|------|--------------|
| <img src="icons/cwv-field-vs-lab.svg" width="20" alt=""> | [cwv-field-vs-lab](https://github.com/seoprocheck/cwv-field-vs-lab) | CrUX field data vs Lighthouse lab, side by side — divergence flagged and explained |

</details>

## Browser tools

<details>
<summary><strong><img src="icons/browser-hub.svg" width="20" alt=""> 41 tools, live at seoprocheck.github.io</strong></summary>
<br>

No install, no tracking — everything runs client-side. [Open the hub →](https://seoprocheck.github.io)

| Category | Tools |
|----------|-------|
| Schema & structured data | 6 generators — Article, FAQ, HowTo, Breadcrumb, Video, Event |
| GEO & AI visibility | 5 — AI crawler checker, llms.txt generator, entity clarity, citations, AI readiness |
| Technical SEO | 8 — robots.txt, hreflang, canonical, sitemap, redirects, headers |
| Content analysis | 6 — SERP preview, density, headings, readability, gaps, word count |
| Local SEO | 3 — review link, NAP consistency, LocalBusiness schema |
| Social & meta | 4 — Open Graph, Twitter cards, meta tags, social preview |
| Developer utilities | 9 — encoders, JSON, regex, UTM, slugs, timestamps |

</details>

## Example

```console
$ python3 ai_crawler_audit.py example.com

  ● BLOCKED  GPTBot            OpenAI
  ○ allowed  ClaudeBot         Anthropic   (not named)   ← the silent gap
  ...
  3/27 AI crawlers blocked · 14.8% coverage
  ⚠ You address some AI bots but not all.
```

---

<div align="center">
<sub>MIT licensed · no sign-ups, no telemetry, no "book a demo" · <a href="https://seoprocheck.com">seoprocheck.com</a></sub>
</div>
