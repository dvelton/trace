# Trace

Trace is a format for publishing AI-assisted writing with provenance. It preserves the human's verbatim prompts inline with the text they produced, so readers can see how the final output was actually made.

**Get the closing prompt and try it now: https://dvelton.github.io/trace/**

## How to use it

1. Write something with any AI tool (ChatGPT, Claude, Gemini, Copilot, Perplexity, anything).
2. When you're done, visit **https://dvelton.github.io/trace/** and copy the closing prompt.
3. Paste it into the same AI conversation. The AI already has your full session in context — it will reconstruct a Trace document from what it can see, reproducing your prompts word for word alongside the text they generated.

That's it. No signup, no install, no extension. One prompt, pasted at the end.

A Trace has two records:

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
