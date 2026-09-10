# AI-Assisted Development Process

## Which tools you used, and for what — brainstorming, structure, drafting, editing, translation, nothing at all.

I used Rider's AI chat with GitHub Copilot to generate this file and correct the grammar in `README.md`.

After the first draft, two more AI passes touched these files. I used OpenAI Codex for a grammar and formatting pass over `README.md` and `PROCESS.md`, and then Claude Code to review that pass and apply the follow-up corrections. I kept the grammar and Markdown fixes; where an edit changed my meaning or wording rather than my grammar, the original text was restored.

To add a bit more polish, I set up a webhook relay on my backend at `api.darketomaly.com` for push events, using a custom Discord bot to format the notifications cleanly. I used GitHub Copilot to help me with some boring string formatting for cases in which the embed description exceeds the 4,096-character limit. This can be used with any GitHub repository.

<img width="600" height=auto alt="646745249-65826fab-1899-43e9-92c7-d5ab56d56a3c-modified" src="https://github.com/user-attachments/assets/9f820400-029e-4434-b63b-984e48803d1e" />

## One thing it produced that you kept, and why it was good.

While my wording was technically grammatically correct, AI helped to make it more natural. For example, changing "find out" to "discover" or "your efforts were put into something else" to "your efforts were redirected elsewhere".

## One thing it produced that you rejected, and why it was wrong, generic, or not what you think.

It referred to English as a low-level language. However, in programming terms, *low-level* means that a language is very close to machine code.

I corrected this in [commit `0dcc288`](https://github.com/darketomaly/sd5913-assignment-1/commit/0dcc2883646338fd01145eb8fca233e875167de4).
