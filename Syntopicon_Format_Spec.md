---
date: 2026-04-30
project: Great Books / Syntopicon
tags: [syntopicon, spec, format, athena]
type: spec
status: active — Athena reads this as the working spec
---

# Syntopicon Format Spec

The Syntopicon has **two indices** that work together. They are different file types with different templates and different purposes.

## 1. Ideas index

The English-language navigation spine. Adler's 30 + the Western additions Mike has authorized:

- **Adler's 30** — already files in `Syntopicon/`
- **31. Sexuality** — promoted (driven by GHB)
- **32. Eros** — promoted (distinct from Sexuality; Plato/Sappho/Ovid/Sufi divine-eros lineage)
- **33. Witness** — promoted (Mike's framing, GHB-load-bearing)

Each Idea is one file: `Syntopicon/<Idea_Name>.md`. Template: `Syntopicon/_Idea_TEMPLATE.md`.

An Idea page does not pretend to be culturally neutral. It is the English-language framing of a question. When other traditions ask the question differently, the Idea page acknowledges this in a **Reframings** section — short, honest, pointing to the Term page for the tradition-native concept.

## 2. Terms index

Tradition-native concepts that **do not reduce** to a single English Idea. Each is one file: `Syntopicon/Terms/<Term_Name>.md`. Template: `Syntopicon/_Term_TEMPLATE.md`.

A Term page exists when:
- The term has multiple distinct meanings within its own tradition (polysemy), AND
- Flattening it into one Adler Idea would lose the tradition's actual shape.

Examples already authorized:
- **Dharma** (Sanskrit) — cosmic order / duty / religion / truth
- **Karma** (Sanskrit) — action / ritual / moral consequence — including the modern US misuse
- **Logos** (Greek) — Heraclitus / Stoic / Johannine / Philonic — four different concepts, all called "Logos"
- **Tantra** (Sanskrit) — continuum/loom / esoteric ritual / sexual practice — three distinct usages

Term pages link out to whichever Idea pages they touch. Idea pages link in to whichever Terms reframe them.

## Why two indices

A Western reader looking for *Justice* across cultures gets Plato + Aristotle + Confucius + a Reframing pointing to the Dharma page. A reader interested in *Dharma* on its own terms gets a single coherent page with all four meanings, primary-source quotations, common misuses called out, and a "see also" linking to Justice / Duty / Religion / Truth.

This refuses to flatten without fragmenting the work. **Methodological bonus:** the Terms index also handles polysemy *inside* the Western canon (Logos has the same problem), so it is not a concession — it is the more honest structure.

## Starter Term list (Phase 1)

Athena should aim for these ~26 Term pages first. Order is suggested by load-bearingness against the existing Idea set, not strict priority:

**Sanskrit / Hindu:** Dharma, Karma, Brahman, Atman, Moksha, Maya
**Pali / Sanskrit / Buddhist:** Nirvana, Sunyata, Anatman, Dukkha
**Chinese / Daoist:** Tao, Wu Wei, De
**Chinese / Confucian:** Ren, Yi, Li
**Greek:** Logos, Arete, Eudaimonia, Telos
**Arabic / Sufi:** Fana, Tawhid, Nafs
**Hebrew:** Hesed, Tzimtzum

Tantra goes in Phase 2 (after Phase 3 lyric/mystical lands and there's tantric primary-source material). Eros is an *Idea* not a Term (because Mike has authorized it as a Western addition with its own canon — Plato, Sappho, Ovid, the Sufi divine-eros lineage). The Greek-Eros / agape / philia / storge distinction can be noted inside the Eros Idea page; it does not need a separate Term page.

## Methodological note: non-Western Term pages and translation drift

The corpus contains pre-1929 English translations of non-Western primary sources (Bhagavad Gītā, Upanishads, Vedānta-sūtras, Tao Te Ching, Analects, Dhammapada, etc.). The translators of that era — Arnold, Müller, Legge, Thibaut — overwhelmingly **translated** tradition-native terms (dharma → "duty," wu wei → "non-action," ren → "humaneness") rather than transliterating them. As a result, a keyword search for the term itself often returns few or zero hits even when the corpus contains substantial material on the concept.

The Term-page builder addresses this by retrieving two passage types:

- **Direct matches** — passages where the term itself (or close transliteration) appears in the text. Genuine attestations.
- **Equivalent matches** — passages retrieved by searching for the English words a pre-1929 translator typically uses for the concept, *filtered to the relevant tradition* (so "duty" returns Arnold's Gita, not Aristotle's Ethics).

**Each cited passage is labeled in the page as either a direct or equivalent match.** When equivalent matches are used, the page explains in its polysemy section that the cited text uses the translator's English word, not the original term. This is honest navigation, not hidden semantic flattening.

This approach is a deliberate compromise. Better corpus-side fixes would be (a) acquiring scholarly editions that preserve the original terms (Edgerton, van Buitenen, Olivelle for Sanskrit; Watson or Mair for Chinese), (b) adding a parallel-text annotation layer mapping translator words back to source terms. Both are deferred. For now, equivalent-match passages are better than empty pages and they give Mike useful comparative material — which was the point.

## Bibliographic discipline (mandatory)

Every quoted passage must cite **author, work, location, translator, year**. Translation provenance matters — the lyric/mystical canon is the trap zone (Coleman Barks Rumi vs. Whinfield Rumi; Ladinsky "Hafiz" vs. Bell Hafiz; modern Loeb vs. pre-1929 Loeb). When in doubt, log and ask Mike rather than substitute.

## See Also
- [[Syntopicon/_Idea_TEMPLATE]]
- [[Syntopicon/_Term_TEMPLATE]]
- [[Syntopicon_New_Ideas_Tracker]]
- [[Great_Books_Master_Index]]
- [[Lyric_Mystical_Canon_Expansion_Plan]]
- [[Psychoanalysis_Sexology_Phase27_Plan]]
- [[Eastern_Canon_Expansion_Plan]]
