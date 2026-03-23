# Trace

Trace is a format for publishing AI-assisted writing with provenance. It preserves the human's verbatim prompts inline with the text they produced, so readers can see how the final output was actually made. Probably not for normal daily use, but there may be times and places where this sort of radical transparency can make for compelling reading and a glimpse into the author's mind that the author may wish to share.

**To try it get the closing prompt here: https://dvelton.github.io/trace/**

## How to use it

1. Write something with any AI tool (ChatGPT, Claude, Gemini, Copilot, Perplexity, anything).
2. When you're done, visit **https://dvelton.github.io/trace/** and copy the closing prompt.
3. Paste it into the same AI conversation. The AI already has your full session in context — it will reconstruct a Trace document from what it can see, reproducing your prompts and reactions word for word alongside the specific text they generated.
4. Paste the AI's output into the **[Trace creator](https://dvelton.github.io/trace/create/)** to get a formatted page with a shareable URL.

No signup, no install, no extension. The entire document is encoded in the URL.

A Trace has two records:

- **Session record** — your messages in chronological order, showing the arc of the writing process
- **Unit record** — the final output annotated paragraph by paragraph, mapping each section to the prompt that shaped it

## License

MIT
