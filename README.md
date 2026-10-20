# Concept to Form

**From meaning to form. From form to system.**

An independent, concept-driven graphic design **Agent Skill** for Claude Code and assistants that support SKILL.md. Build thoughtful visual identities, editorial graphics, invitations, posters and campaign systems by reasoning **before** choosing a style.

> Inspired by the broader discipline of concept-driven graphic design, including publicly discussed work from Pentagram. This project is independent and is not an official Pentagram product, endorsement, or affiliated initiative.

## Five questions

| Stage | Core question | 直白一点 |
| --- | --- | --- |
| **01 — Understand** | What is the real communication problem? | 搞清楚：到底要解决什么问题？ |
| **02 — Creative Concept** | What is the one meaningful idea? | 想明白：最值得表达的一个想法是什么？ |
| **03 — Visual Principle** | How can the idea become visible? | 想办法：怎么让想法变得看得见？ |
| **04 — Graphic System** | What rules make the idea repeatable? | 定规则：怎么让这个视觉想法持续成立？ |
| **05 — Design Critique** | Does every decision serve the idea? | 做判断：每个元素真的有必要吗？ |

Seven practical actions support the five questions:

**Research → Collect Observations → Find a Tension → Explore Visual Relationships → Sketch → Generate / Execute → Critique**

**Core rule:** One meaningful idea. One primary visual mechanism. Every element earns its place.

## Installation

Clone this repository and copy the whole folder into Claude Code's skills directory.

Personal installation:

    git clone https://github.com/gracege17/concept-to-form.git ~/.claude/skills/concept-to-form

Project installation (from the project's root directory):

    mkdir -p .claude/skills
    git clone https://github.com/gracege17/concept-to-form.git .claude/skills/concept-to-form

Invoke the skill in Claude Code:

    /concept-to-form Help me develop three graphic concepts from this client brief. Start with research and observation. No images yet.

Or try:

- **Discover:** Research a brief and find meaningful tensions.
- **Translate:** Develop three distinct visual mechanisms, then black-and-white sketches.
- **Build:** Turn a selected mechanism into a consistent graphic system.
- **Critique:** Audit an existing design: keep, remove, change — with reasons.
- **Iterate:** Make one focused edit while protecting approved design decisions.

## Files

    concept-to-form/
    ├── SKILL.md
    ├── README.md
    ├── LICENSE
    ├── references/
    │   ├── visual-operations.md
    │   ├── critique-checklist.md
    │   └── example-lsc.md
    └── templates/
        ├── 01-discovery.md
        ├── 02-concept-cards.md
        ├── 03-visual-explorations.md
        ├── 04-visual-system.md
        └── 05-critique.md

## Philosophy

- Research is not a Pinterest board.
- A concept is not a color palette.
- A visual principle is a **relationship or action**, not a random symbolic object.
- A graphic system is a small set of repeatable rules, not extra decoration.
- Critique diagnoses the *level* of the problem before proposing a fix.
- When iterating, change the requested dimension and preserve the rest.
- AI-generated mockups are not automatically production-ready files.

## License

MIT. See LICENSE.
