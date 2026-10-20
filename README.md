# Concept to Form

**From meaning to form. From form to system.**

A **task-first, concept-driven graphic design Skill** for Claude Code. Useful for invitations, posters, editorial designs, campaign assets, and identity projects **when an identity project is actually requested**.

This Skill helps you find a meaningful idea for a **specific design assignment**, turn it into visual form, make coherent decisions, and critique the result.

> An independent project informed by concept-driven design practice, including publicly documented design work. Not affiliated with or endorsed by Pentagram.

## The five questions

| Stage | Where AI often goes wrong | What we actually need |
| --- | --- | --- |
| **01 UNDERSTAND** | Investigate the company's deepest mission or brand truth | Understand the communication problem **of this assignment** |
| **02 CREATIVE CONCEPT** | Define the organization's core values | Propose **a meaningful creative idea for this piece** |
| **03 VISUAL PRINCIPLE** | Hunt for brand symbols and metaphors | Explore **typography, shapes, scale and space** |
| **04 GRAPHIC SYSTEM** | Build a full brand identity | Define **the visual rules needed for this project** |
| **05 DESIGN CRITIQUE** | Check corporate strategic alignment | Check **concept, composition, hierarchy, clarity and visual quality** |

In plain Chinese:

1. 搞清楚：**这次设计**要解决什么问题？
2. 想明白：**这张作品**最值得表达的一个想法是什么？
3. 想办法：怎么用**字体、形状、空间**把想法表达出来？
4. 定规则：怎么让**当前作品**的视觉语言保持一致？
5. 做判断：概念、构图、视觉重点和美感是否成立？

### The practical steps inside the framework

**Research → Collect Observations → Find a Tension → Explore Visual Relationships → Sketch → Generate / Execute → Critique**

These are **actions within the five stages**, not a separate brand-strategy program. Context research should be limited to what helps the particular piece. Brand-system work occurs only when the user explicitly asks for it.

## Install with Claude Code

Global:

```bash
git clone https://github.com/gracege17/concept-to-form.git ~/.claude/skills/concept-to-form
```

Within one project:

```bash
mkdir -p .claude/skills
git clone https://github.com/gracege17/concept-to-form.git .claude/skills/concept-to-form
```

Invoke:

```text
/concept-to-form Help me design an invitation. Start with the specific communication problem, not an analysis of the organization's entire brand.
```

## Included

- [SKILL.md](SKILL.md) — scope rules, five stages, anti-drift checks
- [Discovery worksheet](templates/01-discovery.md)
- [Concept cards](templates/02-concept-cards.md)
- [Visual exploration worksheet](templates/03-visual-explorations.md)
- [Graphic system sheet](templates/04-visual-system.md)
- [Critique log](templates/05-critique.md)
- [Visual operations reference](references/visual-operations.md)
- [Critique checklist](references/critique-checklist.md)
- [LSC 2027 illustrative example](references/example-lsc.md)

## Core rule

**One idea. One visual mechanism. Every element earns its place.**

An object isn't automatically a concept. Texture isn't a visual principle. A poster isn't an excuse to redesign the company.

## License

MIT; see [LICENSE](LICENSE).
