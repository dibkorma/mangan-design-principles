# Mangan Design Principles — a Claude Code skill

The transversal **design philosophy of Mangan (Orlando "Mango" Martinez)**, packaged as a [Claude Code](https://claude.com/claude-code) skill. Once installed, Claude applies these design criteria automatically whenever you create or review a visual piece (decks, slides, web pages, mockups, social graphics).

It's **brand-agnostic taste + process** — not one brand's look. Root idea: *good design understands the language of each project.* You bring the brand's specific fonts/palette/motifs; this skill brings the judgment.

---

## Instalar (Español)

Necesitas tener **Claude Code** instalado. Luego, en la terminal:

**Opción A — para TODOS tus proyectos** (recomendado):
```bash
git clone https://github.com/dibkorma/mangan-design-principles.git
cp -r mangan-design-principles/mangan-design ~/.claude/skills/
```

**Opción B — solo para un proyecto:**
```bash
git clone https://github.com/dibkorma/mangan-design-principles.git
cp -r mangan-design-principles/mangan-design /ruta/a/tu-proyecto/.claude/skills/
```

Abre (o reinicia) Claude Code. Listo: cuando le pidas diseñar o revisar una pieza visual, aplica los principios solo. También puedes invocarlo escribiendo `/mangan-design`.

---

## Install (English)

You need **Claude Code** installed. Then, in your terminal:

**Option A — for ALL your projects** (recommended):
```bash
git clone https://github.com/dibkorma/mangan-design-principles.git
cp -r mangan-design-principles/mangan-design ~/.claude/skills/
```

**Option B — for a single project:**
```bash
git clone https://github.com/dibkorma/mangan-design-principles.git
cp -r mangan-design-principles/mangan-design /path/to/your-project/.claude/skills/
```

Open (or restart) Claude Code. That's it — Claude applies the principles automatically when you ask it to create or review a visual piece. You can also invoke it directly with `/mangan-design`.

---

## What's inside

```
mangan-design/
└── SKILL.md   ← the philosophy: how to work, iteration & feedback, legibility,
                  color hierarchy, layout variety, composition & balance, fine
                  craft, logo treatment, elements, measuring feedback, versioning
                  & pipeline, QA before showing, and delivery
```

## The layered model

This skill is **Layer 2**. Good design stacks in three layers:

1. **Universal craft** — what the model already knows.
2. **Mangan's philosophy** *(this skill)* — taste + process across every brand.
3. **The brand system** — one brand's specific tokens (fonts, palette, motifs, voice). Not included here; you define it per project and it layers on top.

## License

MIT — use it, fork it, adapt it to your own brands.
