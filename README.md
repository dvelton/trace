# Trace

Trace is a format for publishing AI-assisted writing with provenance. It preserves the human's verbatim prompts inline with the text they produced, so readers can see how the final output was actually made.

This repository contains the Trace format specification website and a set of interactive examples.

## How it works

Paste the closing prompt at the end of any AI session (ChatGPT, Claude, Gemini, Copilot, Perplexity). The AI reconstructs a Trace document from the conversation history, reproducing your prompts word for word alongside the text they generated.

A Trace has two views:

- **Session record** — your messages in chronological order, showing the arc of the writing process
- **Unit record** — the final output annotated paragraph by paragraph, mapping each section to the prompt that shaped it

## Structure

```
index.html                      The format spec and closing prompt
examples/index.html             Example gallery
examples/the-apology.html       CEO data breach response (unit view)
examples/the-goodbye.html       Employee farewell email (unit view)
examples/the-pitch.html         Nonprofit grant narrative (unit view)
examples/the-update.html        Startup investor email (session + unit)
examples/the-recommendation.html  LinkedIn recommendation (session + unit)
```

No build step, no dependencies, no backend. Each page is self-contained HTML.

## License

MIT
