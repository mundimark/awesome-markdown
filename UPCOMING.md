# Awesome Markdown   - What's News (Upcoming) in 2026?


<!-- please, add your app, tool, library, service to the best matching category. thanks! 
  -->


# Markdown Building Blocks

### Markdown Libraries & Tools

**markupmarkdown**  (web: [mumd.metavert.io](https://mumd.metavert.io), github: [jonradoff/markupmarkdown](https://github.com/jonradoff/markupmarkdown)) "Google Docs for Markdown" — collaborative review & editing for `.md` files: anchored comment threads, suggested changes with one-click apply, review states, document checks, and GitHub round-trip (open any repo's Markdown, push edits back as a PR). Includes an MCP server so AI agents can review documents alongside humans. MIT licensed, built with Go + React.



**mdshare**  (web: [mdshare.live](https://mdshare.live), github: [urbanmorph/mdshare](https://github.com/urbanmorph/mdshare), npm: [mdshare-mcp](https://www.npmjs.com/package/mdshare-mcp)) Free markdown sharing and collaboration. Upload a markdown, get shareable links with view/edit/comment permissions. WYSIWYG editor, inline comments, no login required. API + MCP server for AI integration.

**md-viewer-py**  (GitHub: [bot-anica/md-viewer-py](https://github.com/bot-anica/md-viewer-py), PyPI: [md-viewer-py](https://pypi.org/project/md-viewer-py/)) Drop-in Markdown viewer for any folder. It works locally. Its main features: dashboard, live reload, dark/light themes, in-browser editing, 3 types of search as in Webstorm: search in current file, search in all files, search files by names.

**BeLikeNative Markdown Preview**  (web: [theluckystrike.github.io/bln-markdown-preview](https://theluckystrike.github.io/bln-markdown-preview/), github: [theluckystrike/bln-markdown-preview](https://github.com/theluckystrike/bln-markdown-preview)) Free online Markdown editor with live preview, syntax highlighting, and writing quality checks. Client-side only, no server needed. Features include dark/light themes, export to HTML, and L1-aware grammar suggestions powered by BeLikeNative.

**LiteMarkup**  (GitHub: [tuures/LiteMarkup](https://github.com/tuures/LiteMarkup), NPM: [litemarkup](https://www.npmjs.com/package/litemarkup), Web: [Live demo](https://tuures.github.io/LiteMarkup/docs/demopage.html)) Parser with a typed, AST-first TypeScript API. Under 3 KB gzipped, zero dependencies. LiteMarkup supports the most popular Markdown features while maintaining a small bundle size, good performance, and strong AST extensibility. A simple HTML string renderer is included for demonstration and simple use cases, but users are expected to bring their own renderer tailored to their specific use case and context, such as rendering to React, docx, or something else. LiteMarkup performance is roughly on par with popular JS-based implementations like commonmark, marked, and markdown-it, but naturally slower than WASM-based ones.

**Dualmark**  (web: [dualmark.dev](https://dualmark.dev), github: [dodopayments/dualmark](https://github.com/dodopayments/dualmark), npm: [@dualmark/core](https://www.npmjs.com/package/@dualmark/core)) Markdown-first web infrastructure. Auto-generates a markdown twin of every page (e.g. `/pricing` + `/pricing.md`) and serves it via HTTP content negotiation when AI crawlers visit — same URL, two formats. TypeScript, Apache 2.0, adapters for Astro, Next.js, and Cloudflare Workers.

**Redline**  (web: [redline.levistudio.net](https://redline.levistudio.net), github: [alevi/redline](https://github.com/alevi/redline), npm: [@levistudio/redline](https://www.npmjs.com/package/@levistudio/redline)) — by Alon Levi at Levi Studio. Local inline-comment review tool for markdown files, designed for human-in-the-loop AI doc review. Open a `.md`, highlight any sentence, leave an inline comment; a Claude agent replies in the comment thread within seconds, suggests edits, and rewrites the document when you accept the round. The next round opens with the rewrite shown inline as a diff. Local-first: the server binds to `127.0.0.1`, the agent inherits your Claude Code session (no `ANTHROPIC_API_KEY`), and history snapshots land alongside the file so a bad round can be rolled back from disk. One-command install: `bunx @levistudio/redline ./your-file.md`. MIT-licensed.

**@webc.site/math** (web: [math.webc.site](https://math.webc.site), github: [webc-site/math](https://github.com/webc-site/math), npm: [@webc.site/math](https://www.npmjs.com/package/@webc.site/math)) The world's smallest and fastest TeX-to-MathML compiler for Markdown math formulas (LaTeX/TeX) rendering. Under 4 KB gzipped, zero dependencies, and 3.6x faster than KaTeX. Compiles formulas directly into browser-native MathML Core elements, completely eliminating client-side layout rendering dependencies and heavy font/CSS bundles. Comes with official plugins for markdown-it, marked, and remark.

**Embridge** (web: [embridge.net](https://embridge.net), github: [embridge-foundation/embridge](https://github.com/embridge-foundation/embridge), npm: [embridge](https://www.npmjs.com/package/embridge)) Markdown-based item and task list format that aims to be flexible and human-friendly while providing enough structure for automated parsers and AI agents. With stable IDs, metadata fields, comments, attachments, and a reference validator. Suitable for Kanban boards and calendars too.

**MDMA** (web: [mdma.software](https://mdma.software), github: [MobileReality/mdma](https://github.com/MobileReality/mdma), npm: [@mobile-reality/mdma-renderer-react](https://www.npmjs.com/package/@mobile-reality/mdma-renderer-react)) Markdown Document with Mounted Applications — extends Markdown with interactive components (forms, tables, approval gates, charts, callouts, webhooks) declared in fenced ` ```mdma ` blocks, so an LLM responds with validated, renderable UI instead of plain text. Parser is a remark plugin; ships a React renderer, a validator, a prompt-pack, a CLI, and an MCP server. Open source, MIT. Built by [Mobile Reality](https://themobilereality.com).


### Babelmark


### Markdown Style Guides / Best Practices


### Markdown Lint / Style Rule Checker

**slopless**  (github: [seochecks-ai/slopless](https://github.com/seochecks-ai/slopless), npm: [slopless](https://www.npmjs.com/package/slopless)) Deterministic textlint preset and CLI to flag AI-generated and padded English prose without calling an LLM. It catches the common "LLM tells" — hollow framing, fake "not X but Y" contrasts, hedging, em-dash overuse, vacuous closers — and emits reproducible JSON findings, so it runs in CI. Use it via `npx slopless` or as a textlint preset (`"preset-slopless": true`). MIT-licensed.

### Markdown Web Components / Custom Elements


### Markdown to Website / Blog


### Markdown to Email


### Markdown to Presentation / Slideshow

### Markdown to Portable Document Format (PDF)

**MDMagic** (web: https://mdmagic.ai, github: https://github.com/MDMagic-MCP/mdmagic-mcp-server) - convert Markdown to Word, PDF, and HTML using your own Word templates - letterhead, fonts, branding applied automatically. Web app + MCP server for Claude, Cursor, OpenClaw, and any MCP-compatible AI assistant. Freemium.


### Markdown Styles / Documents / Pages


### Markdown to Books



### Markdown to Table of Contents (TOC)


### Markdown to Markdown Pre-Processor

**NRG**  (web: [central.sonatype.com/.../readme-generator](https://central.sonatype.com/artifact/com.nanolaba/readme-generator), github: [nanolaba/readme-generator](https://github.com/nanolaba/readme-generator)) Nanolaba Readme Generator — builds multi-language README files (e.g. `README.md` and `README.ru.md`) from a single `.src.md` template via file imports, custom widgets, a built-in table-of-contents, and language-specific text via `${en:'…', ru:'…'}` substitutions. Distributed as a CLI, a Maven plugin, and a Java library.

### Markdown to Notion


## Convert to Markdown Tools

### Microsoft Word to Markdown


### PDF / Office Documents to Markdown

- [FolioMD](https://foliomd.es) - Free online PDF to Markdown converter with OCR, table extraction, and image support.

### WordStar to Markdown

### Various Note Formats to Markdown


### Hypertext Markup Language (HTML) to Markdown


### Source Code to Markdown


### Technical Documentation to Markdown

### Screencast to Markdown

### JSON to Markdown

## Book Services

## Protocol



## Meta

**License**

The awesome list is dedicated to the public domain. Use it as you please with no restrictions whatsoever.

