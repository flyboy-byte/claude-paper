# claude-paper

A single HTML file that turns raw research text into a clean, structured white paper — powered by the Claude API.

No build step. No dependencies. No server. Just one file.

---

## How it works

You paste research text (e.g. from ChatGPT Deep Research, Perplexity, or your own notes). Claude adds structure — a title, table of contents, headings, and section breaks — without changing a single word or reordering your content. The result renders as a clean document you can save as HTML or print to PDF.

---

## Usage

### Option A — Inside claude.ai (free, no API key needed)

1. Open [claude.ai](https://claude.ai)
2. Upload or paste the contents of `whitepaper-formatter.html` into the chat and ask Claude to run it as an artifact
3. Leave the API key field blank — your session handles auth automatically

### Option B — Standalone (anywhere)

1. Download `whitepaper-formatter.html`
2. Open it in any modern browser
3. Paste your Anthropic API key (`sk-ant-...`) into the field at the bottom
4. Paste your research text and click **Format as white paper**

Get an API key at [console.anthropic.com](https://console.anthropic.com).

---

## Saving the output

After formatting, click **Save as HTML**. The button tries three methods in order:

1. **Native share sheet** — on iOS and Android this opens your system share menu so you can save to Files, AirDrop, email, etc.
2. **Direct download** — works on desktop Chrome, Firefox, and Edge
3. **Copy fallback** — if both fail, a modal appears with the raw HTML so you can copy and paste it manually into a `.html` file

To get a PDF: open the saved `.html` file in your browser and use **Print → Save as PDF**.

---

## What Claude does (and doesn't do)

| Does | Does not |
|------|----------|
| Add headings and section breaks | Rewrite any sentences |
| Generate a table of contents | Paraphrase or summarize |
| Wrap lists in proper HTML | Add new content |
| Detect the document title | Change the order of ideas |
| Preserve the author's exact words | Remove anything |

---

## API key privacy

Your API key is entered directly in your browser and is only used to make the single API request. It is never sent anywhere else and is not stored.

---

## License

MIT — see `LICENSE`.
