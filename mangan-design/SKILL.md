---
name: mangan-design
description: Mangan's design philosophy — brand-agnostic principles for any visual piece (decks, slides, web pages, mockups, social graphics). Use BEFORE creating OR reviewing any visual design. Covers legibility, color hierarchy, layout variety, composition & balance, fine craft, logo treatment, iteration & feedback, measuring feedback, versioning, QA and delivery. This is transversal taste, not one brand's look — apply it on top of whatever brand system you're working in.
---

# Mangan's Design Philosophy

This skill encodes the transversal design criteria of **Mangan (Orlando "Mango" Martinez)** — a creative director who does design, press and booking for music and product brands. These are *tools of judgment*, not a fixed style.

## The layered model (read this first)

Good design lives in three layers. This skill is **Layer 2** only.

1. **Layer 1 — Universal craft** (whatever your model already knows).
2. **Layer 2 — Mangan's philosophy** *(this skill)*: taste + process that hold across **every** brand.
3. **Layer 3 — The brand system**: the specific tokens of ONE brand (fonts, palette, motifs, outline style, emoji usage, voice). This is **NOT** in this skill and changes per project.

**Root principle: good design understands the language of each project.** There is no single "Mangan look" to stamp on everything — each brand speaks differently. Your job is to read that language and execute it. So: **apply this philosophy, but never invent or copy a brand's specific look from here.** If you don't have the brand's Layer 3 (its fonts/palette/motifs), ask for it or work from the client's real assets — don't guess a style.

> A brand rule misfiled as transversal stamps itself onto the next brand automatically. When a rule has no brand written next to it, treat it as brand-specific until confirmed — don't promote it to universal.

## How to work (process)

- **Piece by piece.** Apply feedback on one piece, **show the rendered image**, and confirm before moving on. Never ask about something you haven't shown.
- **Variants to decide.** When a choice is about taste (font, style), present **2–3 variants side by side** and let the human pick — don't decide taste unilaterally.
- **Show, don't describe.** The human is visual: present every direction as a **navigable link** (self-contained HTML / web page with images embedded), never as an abstract question ("photo or map?") or a loose attachment that "sometimes won't open." One example from them beats five described iterations.
- **Work from real assets.** Start from the client's actual drawings/logos/photos (crop, scale, recompose). Never invent the aesthetic from zero when brand material exists. Before producing your own art, **list the assets folder and LOOK** — if the client already drew something that does the job, your drawing is redundant.
- **Keep work files visible.** Put drafts/renders in a temporary folder inside the project so the human can see them while iterating.

## Iteration & feedback

- **Vague aesthetic feedback ("needs flow", "make it break", "more dynamic"):** diagnose or confirm the specific MECHANISM before building — with the smallest possible version or a one-line question. Don't swing a full interpretation, especially for a new system (animation, layers, JS). If something "looks flat / doesn't show," inspect the render for WHY (stacking, z-index, DOM) before changing the thing itself.
- **Two rejections of the same aspect = STOP iterating blind and get a concrete REFERENCE.** If they reject the same thing twice, don't swing a third interpretation: ask them to **mark or send an example** (a box over the image, a ref made elsewhere, a sketch). It's visual — their example reveals the real fix that blind iterations miss.
- **Big or vague redesign ("rethink it all", "make it more unique"), or "I'll send a sketch": WAIT for the sketch before building whole sections.** In deep redesigns the source of truth is their sketch, and it comes FIRST. Speculative sections built "to make progress" burn cycles and usually get tossed. The right "progress" there is *securing their visual direction*, not racing ahead.
- **When they point at an EXISTING element as reference ("like the one after the hero", "same as section X"), that's a SPECIFICATION, not a vibe.** Go LOOK at that element and clone its **medium and treatment**: photo or illustration? painted or vector? which palette? If their reference is a painting, the new thing is painted — don't bring photos "that match."
- **Faithful placement.** When the human draws a composition guide (a box, a mark of where each thing goes), respect it **to the letter** — don't auto-center or "improve" the placement.
- **A request for "more X" is NOT permission to give "less Y."** Before cutting content they already approved, ask: does the request REQUIRE this loss, or am I assuming it? Often both fit. If the trade-off is real, say so and let them choose.

## Legibility (the golden rule)

- **Text must always read well.** It's the first thing to check. Reading has to be effortless.
- **No patterns (dots/textures) behind text** — they wreck contrast. Keep the background clean behind text blocks; save patterns and color for margins and accents.
- **Colors must work on top of each other.** Whenever text sits on color (or color on color), verify contrast: dark text on light, white on mid/dark.
- **Check every piece of text against its real background — even the tiniest** (page numbers, credits, footnotes).
- **System trick:** UI text that can land on varied backgrounds (e.g. a page number) goes in a **solid color pill** (black fill, white text) so it always reads.
- **Secondary text and callouts can't be tiny.** If it doesn't read at presentation size, enlarge it.

## Color hierarchy (two planes)

- **Not everything in the same color.** When several elements share one tone (eyebrow + title + bullets), the layout **flattens**. Differentiate to create hierarchy and depth.
- *Why:* color creates hierarchy; one tone across everything kills it.
- The *concrete* color assignment (which element gets which hue) belongs to the brand system (Layer 3), not here. Here: just enforce that there **are** distinct planes.

## Layout variety (critical)

- **Every piece must look different.** Not the same template with the content swapped — that reads as "the same slide with more info" and bores.
- **Vary the composition:** flip the axis (hero left vs right), change the container shape (circle vs panel vs band), full-bleed vs margins, big hero vs grid.
- **Don't overuse buttons/chips.** Use the minimum; if something can be lettering, plain text, or an image with more character, prefer that. *Fewer buttons.*
- Brand consistency ≠ repeating one layout. Font, colors and system stay constant; the **composition** changes.
- **Count treatments before delivering a set.** A feed/deck with no variety drifts into a single treatment (all illustration, all text). Before calling a set done, count how many distinct treatments it actually has.

## Composition: air, borders, vertical balance

- **Nothing glued to the edge.** Elements (especially characters/images) touching the canvas edge create friction — give them margin to breathe.
- **Nothing cut off.** No illustration/character should be clipped by the edge or a container (unless it's an intentional bleed). If something doesn't fit, the fix is **reserving space in the design**, not shrinking/shoving it afterward.
- **Nothing overlapping.** Every element has air from the edges AND from the others — they don't stack on top of each other.
- **Flat mono-color backgrounds look cheap.** Add something (a textured band/"stage," a geometric accent) for life — without putting pattern behind text. Bonus: that band can make a foreground element pop.
- **A textured/color background must be PRESENT, not a thin frame.** If a nice background color only peeks as a border, it looks flat → widen it (passe-partout style) and make its texture actually visible.
- **Vertical balance.** Content must fill the height evenly. A big empty block at the bottom (content crammed up top) looks unbalanced → center vertically and/or add air between sections.

## Fine craft

*The details that separate a piece that "works" from a clean one. Zoom into the small stuff BEFORE showing.*

- **Lines don't touch,** and line-art is **clean and anti-aliased** — never a hard binary threshold that leaves jaggies/stair-stepping. Line extraction is always smooth.
- **Fine details** (eyes, small features, thin lines) must read **clean**, no pixelation or ragged edges. Zoom into those zones before signing off.
- **Care for the WHOLE artwork, not just the silhouette.** A design's own lettering, internal textures, small details — all of it has to pop and be clean, not only the character's outline.

## Logo treatment

- **Never text on top of a logo.** The logo stands alone; text (title, subtitle, tagline) goes BELOW or BESIDE it, never on top or crowding it from above. Keep the zone above the logo clean. Cover hierarchy: logo → title → subtitle → age/CTA.
- **The logo breathes, no boxes.** Never trap a logo in a little box that gets in the way. Let it sit on a background that integrates it (transparent, or the same color so the edge dissolves). A logo on a square fill reads as a cropped sticker — "boxed in."
- **Crop the emptiness, don't enlarge it.** If the file has lots of empty background, crop to the mark and scale the real mark large.
- **The mark must stand out from its background.** If it doesn't pop, give it contrast (hard shadow, outline, size) — don't leave it weak.
- **Don't repeat the same mark twice in one view.** If the brand is already large on one side, the other use goes reduced (e.g. wordmark only).

## Elements: symmetry, motifs, characters

- **Repeated elements are symmetric.** Rows of buttons/chips are even, equal width, aligned — no lopsided 4+1.
- **Eyebrows/labels usually read better integrated** as text (brand color, slightly larger) than trapped in a pill. Not everything needs a pill.
- **Decorative motifs stay away from text.** Populating the background with brand motifs adds life, but near text they create noise → keep them in corners/empty zones. Even better if the motif reinforces the message.
- **Characters/illustrations as cut-out PNGs with no background**, floating as design elements (peek, bleed, sticker with a hard shadow) — never inside a box with their original background.
- **The background behind an image/character must complement/contrast** so it stands out — never on a band of the same color/pattern (it camouflages).

## Measuring feedback

- **If feedback can be MEASURED, measure it before you show.** Don't chase a problem by eye when a probe/pixel-read gives you the real number (contrast, size, saturation, hue, color area, position). Good diagnosis comes from measuring, not intuiting.
- **A correction has TWO directions of error — after a measured adjustment, MEASURE the result against the source.** Over-correcting is as real a failure mode as under-correcting, and harder to see because you're coming off a hit.
- **The metric that DIAGNOSES the problem isn't always the one that VERIFIES the fix.** (E.g. the problem is diagnosed by *hue* but the fix is verified by *area of vivid color*.) Think about what to measure to confirm — don't just repeat the diagnostic measurement.
- **"Looks shifted / misaligned" + your measurement says it's fine = their browser CACHE,** not a bug. Measure it objectively (bounding box + center line); if it's fine, tell them the truth and ask for a hard-refresh instead of moving CSS that was already correct.

## Versioning & pipeline

- **Always work from the most advanced/approved version.** Before regenerating an asset that might already exist finished, look for the pipeline's latest output (the work folder, the approved batch) — don't rebuild from raw inputs. The approved output wins over the sources; rebuilding from scratch loses decisions already made and comes out worse.
- **Piece #2 of a series: piece #1 isn't a reference, it's the SPECIFICATION.** Before the first line, open #1 and **clone its system** (tokens, treatment, chrome) — don't reinterpret it. And bring its **patches** too: the code you're copying is the version *with* the bugs, and the fixes usually live written in the project log, not in the CSS.
- **Before a BATCH of assets, lock the full finish on a one-of-each-type sample** (line, color, texture) and get the OK — THEN produce the batch once. Don't run the batch with a treatment still open.
- **Every regenerated deliverable carries a visible version in its NAME** (`... V2`, `... V3`). The human sees files as a list of names; if the new version is named like the old one they can't tell which to open — and on platforms that don't overwrite (e.g. Drive) both coexist. When delivering the new one, say which it is and **which to discard**. (Versioning is NOT minting a new link for a doc they already approved and edited — that link stays; it's for real regenerations.)
- **Snapshot the approved version before evolving it.** When the human says "I like it," save a frozen copy of that version BEFORE iterating on top — don't overwrite the same files. "Let's go back to the first one" requires having that version intact, not rebuilding it from memory.
- **When the human hand-edits a deliverable, THEIR file becomes the source of truth — and you say so out loud.** If you need to replicate their edit in the system that generates the file, tell them and show the result so they confirm it matches; otherwise two versions diverge silently and the next regeneration overwrites their work.

## QA before showing

*Catch your own mistakes before they do, not after. Run the piece through these principles BEFORE presenting it.*

- **Render for real, don't assume.** Confirm every texture/style actually renders — look at the render, don't take it on faith that the CSS worked. When you change a global style (font, palette, size), verify it applies to EVERY kind of element.
- **Zoom into fine details** (eyes, thin lines): clean, no pixelation.
- **Nothing cut, nothing overlapping, everything with air** from the edges and each other.
- **Every CONTEXT and every STATE.** If the piece renders in more than one context (standalone + embedded, different breakpoints) or has states/modes (steps, panel open/closed, empty/full), verify the layout in the one with the MOST content and at the shortest realistic screen height — that's where it clips. Nothing can end up unreachable.
- **When you remove/move an element, look at the NEIGHBOR,** not just your change: a z-index covers the adjacent wave, a hanging separator clips the section below, a deleted node leaves orphan JS that throws on load. Ask "did I break the neighbor?", not just "is what I added there?"

## Delivery

- **Visual proposals as self-contained HTML** (images embedded as base64) that opens on its own, or as a **navigable link** — not a loose image or attachment (they sometimes "don't load / won't open"). Save it in the project folder.
- **Web deliverables as a playable link**, not just screenshots — and re-publish to the same URL after each iteration (packaging ≠ publishing: republish and confirm it loaded before saying "done").
- **Check the file weight** of image-heavy pages before publishing, and state the trade-off (sharpness vs MB / load time). Never silently ship a multi-MB page.
- **If the deliverable is in a format you can't see rendered** (a spreadsheet, CSV→Sheets, a doc uploaded via API), you verified the DATA, not the LOOK — say so explicitly or ask them to eyeball it before calling it done. An unreadable deliverable is broken even if the data is perfect.

## When you apply this

Before designing or reviewing a visual piece, run through: *Does it read? Are there distinct color planes? Is the layout different from its neighbors? Does it breathe and balance vertically — nothing cut, nothing overlapping? Is the fine craft clean at zoom? Is the logo free, text never on top of it, and does the mark stand out? Are motifs off the text? Did I measure what could be measured, and check every context and state?* Then execute in the **brand's own language** — this skill gives the criteria, the brand gives the look.
