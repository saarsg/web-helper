# Chrome Web Store Listing — Mark Clipper

## Short description (132 char max)

> Clip any web page or selection into clean Markdown in a side panel. Edit it, then copy or send to your AI. Private and local.

(124 characters)

## Detailed description

**Clip any web page or selection into clean Markdown — edit it, then send it to your AI.**

Open the side panel next to any page. Capture the whole page or just your
selection as clean, readable Markdown, edit it right there, then copy it or send
it to the AI assistant of your choice. No accounts, no API keys — everything is
assembled on your machine.

**What it does**

- **Capture** a page or selection as fenced Markdown, dropped at your cursor.
- **Clip** a selection as an attributed blockquote; **extract tables** to GFM
  Markdown; **pull page metadata** (JSON-LD / OpenGraph / meta tags).
- **Edit** everything in a plain-Markdown editor with a live character + token
  count that persists across restarts.
- **Send to an AI:** pick a provider — Claude, ChatGPT, or Gemini — and Copy &
  Open copies the text and opens the chat in a new tab. You paste it yourself.
  Nothing is auto-submitted.
- **Workflows:** save your own multi-step sequences (capture + send combinations)
  and re-run them in one click — build a repeatable routine once, reuse it
  everywhere. Runs entirely on your machine; no network.
- **Options:** wrap content in a Context Pack (YAML frontmatter + a bounded
  `<document>` block), pick a prompt instruction (Summarize, Critique, Extract
  action items, Q&A flashcards, Explain — or your own saved presets), choose an
  output format (Markdown / HTML / plain / JSON), or export a file.
- **Treats captured pages as untrusted:** removes invisible/hidden text and
  smuggled instructions (prompt-injection protection) so what you paste is what
  you could actually see.

**What it does not do**

- No accounts, no sign-in, no API keys.
- No servers, no analytics, no tracking.
- Nothing leaves your machine unless *you* copy or export it. The extension makes
  no network requests of its own.

**A note on permissions.** Mark Clipper requests access to read all sites. This is
so the capture features can auto-follow whatever tab you switch to, without you
having to re-click for each page. That access is for *reading* the page you are
capturing — it is never used to send your pages anywhere. Everything is assembled
locally and stored only on your computer.

Built for research and personal use. Open source.

## Single-purpose statement

Mark Clipper has one purpose: to capture content from the web page you are viewing
(the full page or a selection) into clean Markdown that you can edit locally and
then copy or send to an external AI chat. Every feature — including saved
workflows, which only sequence these same capture and send actions — serves that
single capture-edit-send workflow. The extension performs no other function — no
background data collection, no network communication of its own, and no
auto-submission of content.
