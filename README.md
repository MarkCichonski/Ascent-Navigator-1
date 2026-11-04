# The Ascent · Level II: AI Navigator

**You don't just use AI — you direct it.**

AI Navigator is Level II of *The Ascent*, the AI certification program by [Data GOLD](https://datagoldvalue.com). Over four weeks, you'll go from prompting AI to building a working AI agent that handles a real, recurring task from your own job — with you approving its work before anything goes out.

This repository holds the course materials: templates, the Navigator workbook, the demo agent, and session materials as each week is released.

---

## What you'll build

By December 2, you'll have a single-purpose agent that:

- Does one recurring task from your work (a weekly report, a recap, a summary you rebuild every time)
- Works from standing instructions you write once, not prompts you re-type each time
- Knows its boundaries: what it can read, what it can create, and what it must escalate to you
- Holds its work for your approval and never sends anything on its own
- Has been tested against real past examples, with before-and-after numbers to prove the time it saves

---

## The climb: prompt → chain → agent

| Level | What it is | Who does the work |
|---|---|---|
| **Prompt** | One request, one answer | You do everything else |
| **Prompt chain** (Week 1) | A series of prompts, run in order | You run each step and carry the work between them |
| **Agent** (Weeks 2–4) | A job, data access, standing instructions and boundaries | The agent runs the steps; you approve at the gates |

The rule we'll come back to all course: **use the lowest level that does the job reliably.**

---

## Schedule

Wednesdays, 6:00–8:00 PM ET, on Zoom.

| Week | Date | Session | You leave with |
|---|---|---|---|
| 1 | Nov 4 | **Directing AI:** RICCE prompting, and mapping a real task as a prompt chain | A workflow canvas, a working prompt chain, a baseline |
| 2 | Nov 11 | **Choosing the level of autonomy:** when a task needs an agent, and designing yours | A completed agent canvas |
| 3 | Nov 18 | **Build session:** building, testing against real cases, and a partner red-team | A working agent that has passed its tests |
| — | Nov 25 | *No class (Thanksgiving week)* | |
| 4 | Dec 2 | **Prove it:** scenario assessment, 4-minute agent demo, credential moment | The AI Navigator credential |

---

## What's in this repo

```
├── README.md
├── workbook/
│   ├── Navigator-Workbook.xlsx           ← your working file for Weeks 1–3
│   └── Navigator-Workbook-Example.xlsx   ← fully worked example (weekly status report)
├── demo-agent/
│   ├── Project-Instructions.md      ← the agent's standing instructions
│   ├── Backup-Sample-Output.md      ← what a good run looks like
│   └── data/                        ← Project Atlas sample files (fictional)
└── sessions/
    ├── week-1/
    ├── week-2/
    ├── week-3/
    └── week-4/                      ← slides and handouts, added after each session
```

---

## Using the Navigator workbook

Download `workbook/Navigator-Workbook.xlsx` and keep one copy for the whole course. Your Week 1 answers carry forward into Week 2 automatically.

| Tab | When | What you do |
|---|---|---|
| **Start Here** | Week 1 | How the tabs connect, and the color legend |
| **W1 Workflow** | Week 1 | Map your task: trigger, inputs, steps, who does each step, checkpoints, baseline |
| **W1 Prompts** | Week 1 homework | Write a RICCE prompt for each AI step, run the chain, and fill in the **glue log**: what you did by hand after each step |
| **W2 Agent Canvas** | Week 2 | Design your agent. Grey cells fill in from Week 1; yellow cells are yours |

**Yellow cells** are yours to fill in. **Grey cells** fill automatically from earlier tabs — change them at the source.

The workbook needs Excel 2019 or later, Microsoft 365, or Google Sheets. A few cells that assemble text from Week 1 show an error in older versions of Excel.

Stuck? Open `Navigator-Workbook-Example.xlsx` to see every cell filled in for a weekly project status report.

---

## The demo agent: Project Atlas

The agent you saw in Week 1 drafts a weekly steering-committee status report for **Project Atlas**, a CRM migration. Project Atlas is entirely fictional: the company, the people and the numbers are made up for teaching.

To try it yourself in Claude:

1. Create a new Project.
2. Paste the contents of `demo-agent/Project-Instructions.md` into the project's instructions.
3. Upload the six files from `demo-agent/data/`.
4. In a new chat, type: *"It's Thursday, November 5, 9 AM. Run this week's status report."*
5. Compare what you get against `demo-agent/Backup-Sample-Output.md`.

Using ChatGPT or Copilot? The same pieces work there: the instructions go wherever your tool keeps standing instructions for a custom assistant, and the data files go in its knowledge or file area. We'll cover your platform in Week 2.

Look at what the agent escalates instead of deciding on its own. Every one of those catches traces back to a line on the agent canvas — and that's the design work you'll do for your own agent.

---

## Your AI tool

Claude, Microsoft Copilot and ChatGPT are all welcome. What matters is the design — the job, the access, the rules and the approval gates — not the platform. Before Week 2, check whether your tool lets you create a reusable assistant (a Claude Project, a custom GPT or ChatGPT Project, or a Copilot agent), and whether you're building on a work or personal account.

---

## Homework

Expect about an hour between sessions, mostly building on your own task. Each week's homework is listed at the end of that session's materials in `sessions/`.

You'll also have an **accountability partner** from Week 1. Check in with them at least once between sessions.

---

## Earning the AI Navigator credential

| | |
|---|---|
| **Train** | RICCE prompting, workflow design, choosing the level of autonomy, and agent design |
| **Assess** | A scenario-based assessment: for real business problems, choose a prompt, a chain or an agent, and justify it |
| **Deliver** | Build and test an agent that runs a real task from your work, with human approval gates and a measured improvement |

Navigators earn the steel blue coin, the Navigator patch and a LinkedIn badge.

---

## Guardrails for this repo

- **Never commit real company data.** Use sample or redacted data for anything you share here.
- Don't paste confidential, client or personnel information into any AI tool your company hasn't approved.
- Project Atlas data is fictional and safe to use, share and modify for practice.

---

## Questions

Mark Cichonski · Founder, Data GOLD · [mark@datagoldvalue.com](mailto:mark@datagoldvalue.com)

*The Ascent by Data GOLD. The climb changes you.*
