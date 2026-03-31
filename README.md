# UXR Case Study Studio

A free Claude skill that walks UX researchers through writing interview-ready case studies and strong CV bullets.

Built by [Dragana Trgovcevic](https://www.linkedin.com/in/draganatrgovcevic/) — UX research lead, hiring manager, someone who had manyyyy projects and zero case studies ready.

---

## What it does

You say "help me write my case study" and Claude walks you through it:

1. **Upload whatever you have** — messy notes, old decks, a rough blurb, or nothing at all
2. **Gap analysis** — maps your material against a 13-section structure, shows what's covered, weak, or missing
3. **Guided prompts** — for each gap, asks the right questions to draw the content out of you
4. **Rewrites** — shapes your rough answers into polished sections in your chosen voice
5. **Quality check** — runs a checklist before you're done

Also handles CV bullet rewriting using an impact formula (power verb + what you did + quantifier + consequence).

---

## Install

**Requires:** Claude Pro, Max, Team, or Enterprise ($20/mo for Pro). Code Execution must be enabled.

### Option 1: Download the .skill file (fastest)

1. Download [`uxr-case-study-studio.skill`](./uxr-case-study-studio.skill)
2. Open [claude.ai](https://claude.ai)
3. Go to **Settings → Capabilities → Skills**
4. Click **Upload skill**
5. Select the `.skill` file
6. Done. Say *"Help me write my case study."*

### Option 2: Clone this repo

```bash
git clone https://github.com/YOUR-USERNAME/uxr-case-study-studio.git
```

Then zip the `uxr-case-study-studio/` folder and upload it in Claude Settings → Skills.

---

## What's inside

```
uxr-case-study-studio/
├── SKILL.md                          ← The workflow (267 lines)
└── references/
    ├── section-prompts.md            ← Guided questions for all 13 sections
    │                                    Strong/weak examples, B2B/B2C/internal
    ├── cv-bullet-formula.md          ← Impact formula + 6 before/after examples
    └── quality-checklist.md          ← Final check before you ship it
```

### The 13 sections

1. Context and background
2. Your role
3. Timeline
4. Research statement and goals
5. Research methodology
6. Recruitment criteria and process
7. Sample questions asked or usability tasks
8. Analysis and synthesis process
9. Outputs/deliverables
10. Impact ← deep framework: product × cultural × internal, scaled from individual to company-wide
11. Next steps and recommendations
12. Reflections
13. *(Optional)* Biases and assumptions

### Three voice options

The skill asks you to pick before writing:
- **Conversational & human** — like talking to a smart colleague
- **Formal & structured** — clean, precise, enterprise-friendly
- **Confident & bold** — short sentences, no hedging, every claim lands

---

## How it was built

I followed [Anthropic's skill-building guide](https://resources.anthropic.com/hubfs/The-Complete-Guide-to-Building-Skill-for-Claude.pdf) and used Claude as a building partner. Full writeup: **[I needed 5 case studies in 5 hours. So I built a tool instead.](https://pinto-scooter-5c6.notion.site/3345125f4d31806cb653ef608db9d44e?source=copy_link)**

---

## License

MIT — use it, modify it, share it.

---

## Questions?

Open an issue or find me on [LinkedIn](https://www.linkedin.com/in/draganatrgovcevic/).
