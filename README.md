# Trace

Trace is a format for publishing AI-assisted writing with provenance. It preserves the human's verbatim prompts inline with the text they produced, so readers can see how the final output was actually made.

This repository contains the Trace format specification website and a set of interactive examples.

## How it works

Paste the closing prompt at the end of any AI session (ChatGPT, Claude, Gemini, Copilot, Perplexity). The AI reconstructs a Trace document from the conversation history, reproducing your prompts word for word alongside the text they generated.

## Structure

```
index.html              The format spec and closing prompt
examples/index.html     Example gallery
examples/the-apology    CEO data breach response
examples/the-goodbye    Employee farewell email
examples/the-pitch      Nonprofit grant narrative
```

No build step, no dependencies, no backend. Each page is self-contained HTML.

## License

MIT
