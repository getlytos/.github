# Lytos

[![npm](https://img.shields.io/npm/v/lytos-cli)](https://www.npmjs.com/package/lytos-cli)

**Your AI forgets everything. Lytos fixes that.** · **[Lire en français 🇫🇷](https://github.com/getlytos/.github/blob/main/profile/README-fr.md)**

---

### The moment it clicks

A developer is coding with an AI agent. They explain the stack, the conventions, the constraints. The AI produces great code. Next session — it forgot everything. They explain again. And again.

Then they try a persona: *"You are a Senior Developer with 15 years of experience."* The tone changes. The quality doesn't. A costume doesn't create knowledge. Context does.

The problem isn't the AI. It's what the AI knows when it starts working.

> *"An agent dressed as a senior dev doesn't know your code. It knows the word 'senior'."*

### What if the AI remembered?

Every session starts with the project's constitution, the team's conventions, past decisions, the current sprint — loaded automatically, from files that live in the Git repo.

That's Lytos. Not another AI tool. A **method** that structures what any AI agent needs to do its best work.

```bash
npm install -g lytos-cli && lyt init
```

One command. The AI understands the project from the first session.

---

**Without Lytos:**
```
Dev: "We use Tailwind, not CSS modules. And we write tests before committing."
AI:  "Got it!" (until the next session, when it forgets again)
```

**With Lytos:**
```
The AI reads .lytos/ at startup → stack, conventions, sprint, past decisions.
No re-explaining. A real working session from line one.
```

> *"Agile structured human collaboration. Lytos structures collaboration with AI."*

---

### A project shouldn't depend on a model

Claude today. GPT tomorrow. Gemini next month. Models change every 3-6 months — APIs evolve, prices shift, features disappear. When project context lives in a vendor's chat history, every change means starting over.

Everything in Lytos is **Markdown in Git**. The manifest, the rules, the memory — plain text files that the team owns, versions, reviews, and migrates freely. The AI is an engine. Engines get swapped. The foundation stays.

It runs on Claude Code today. It will run on whatever's best tomorrow. The context doesn't move.

> *"Choose your AI. Don't belong to it."*

---

### Three paths

**→ Try it** — `npm install -g lytos-cli && lyt init`

**→ Learn by doing** — [lytos-learn](https://github.com/getlytos/lytos-learn) — a guided tutorial in 7 steps

**→ Understand the method** — [lytos.org](https://lytos.org)

**→ For teams & trainers** — [Trainer Kit](https://lytos.org/en/philosophy/trainers/)

---

### Repositories

| Repo | What it is |
|------|-----------|
| **[lytos-method](https://github.com/getlytos/lytos-method)** | The method — manifest, skills, rules, memory. Works with any AI |
| **[lytos-cli](https://github.com/getlytos/lytos-cli)** | The CLI — `lyt init` · `lyt board` · `lyt lint` · `lyt doctor` · `lyt start` · `lyt close` |
| **[lytos-learn](https://github.com/getlytos/lytos-learn)** | Hands-on tutorial — learn Lytos by building a todo API |
| **[lytos-website](https://github.com/getlytos/lytos-website)** | Documentation — [lytos.org](https://lytos.org) |
