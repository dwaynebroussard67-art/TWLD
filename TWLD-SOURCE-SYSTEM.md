# THAT'S WHAT LOVE DOES — Source System: Preserve Source, Create Editable Canon

**Date:** 2026-11-10 — Proposed, not yet executed. No files moved yet.
**Rule from you (README / Instructions):** "Don't change anything that is verbatim from me." "Do NOT write, rewrite, or 'improve' any of my book or Notes text." "Find where placeholder text lives and replace it only with my actual text."
**Companion rule from you:** "We need to establish some kind of canadical version that we nothing get changed out of what's set in Stone."

Both are true. They only conflict if we edit in place. So we separate.

---

## 1. THE PRINCIPLE: PHOTOGRAPH vs. PAINTING

Think of every verbatim file as a **photograph** of what you said on a given day. We never paint over the photograph. We hang the photograph on the wall exactly as it is — even the typo in "Insructions" stays, because it's part of the provenance.

Then we make a **new painting** — the canonical manuscript — that we *copy* from the photographs. On the painting we can, with your explicit permission per item, fix "Taleheding," correct the "took off His divinity" line per your settled kenosis ruling, apply the 44-not-46 age, and consolidate the duplicate Chapter 13s/18s. Every change is logged: *source file → canonical file, line, what changed, your approval date.*

That way truth is not interpretive drift. Truth is traceable.

---

## 2. WHAT STAYS IMMUTABLE (SOURCE-LOCKED)

These are your witnesses. We do not edit, rename, or "clean up" inside them:

- `TWLD-MANUSCRIPT-THE-FIRST-10.md` — locked Feb 24, 2026. Two Intro Part II versions, Ch 1–10, appendix.
- `TWLD-CHAPTERS-11-18.md` — Gemini drafts with thread IDs, AI prompts, three Ch.18s, two Ch.13s.
- `THATS-WHAT-LOVE-DOES-READ-ALOUD.md` — derivative listening compilation. Keep as historical artifact; future read-aloud will be *generated*.
- `TWLD-CLOSING-REFLECTIONS.md` — two closing fragments, placement undecided.
- `TWLD-SPOKEN-ARCHIVE.md` — dictated testimony with gaps/holes marked.
- `TWLD-NOTES-FROM-THE-KING.md` — 22 raw records with AI expansion/site chatter mixed in.
- `NOTES-FROM-THE-KING-WEBSITE.md` — clean 19-note reading collection (label says 17, actually 19).
- `CHEK:NOTES` — 17-note upload duplicate. Keep for provenance; do not maintain as second master.
- `TWLD-INTERLUDE-THE-THIEF.md` — imaginative draft with notes.
- `TWLD-SAMPLE-PAIR.md` — placeholder proof-of-concept.
- `TWLD-DECISIONS.md`, `thats-what-love-does-book-bible.md`, `TWLD-TIMELINE.md`, `TWLD-RECOVERY.md`, `TWLD-ARCHIVE-INDEX.md`, `Insructions`, `README.md`, `TWLD-WHOLE-BOOK-AUDIT.md`.

We *do* add one file: `TWLD-WHOLE-BOOK-AUDIT.md` and this file — they are editorial, not manuscript. That's why we're allowed to write them.

**Consolidation without loss:** Yes, we will have "multiple different files" today. We do not merge them into one blob and delete the originals. We create a *new* folder (`manuscript/` or `canon/`) that holds the editable book; the sources stay where they are in a `source-snapshots/` folder. One source of truth for reading, all sources preserved for evidence. If a lawyer, a theologian, or your own memory needs to check "what did I actually say that Tuesday?" — the photograph is still on the wall.

**External sources referenced but not in repo:** The original PDF `ThatsWhatLoveDoes.TheFirst10.pdf`, the two `Nura_Master_Thread__1_.txt` / `Wife_Master_Thread__1_.txt` Takeout archives, actual poem texts, Anastasis art, full Friday transcript, bibliography. We log them as absent; we don't invent them.

---

## 3. THE CANONICAL BOOK — WHERE EDITS HAPPEN

New structure (proposed — create after you approve the outline):

```
TWLD/
├── source-snapshots/               # IMMUTABLE — never edited
│   ├── TWLD-MANUSCRIPT-THE-FIRST-10.md
│   ├── TWLD-CHAPTERS-11-18.md
│   ├── THATS-WHAT-LOVE-DOES-READ-ALOUD.md
│   ├── TWLD-CLOSING-REFLECTIONS.md
│   ├── TWLD-SPOKEN-ARCHIVE.md
│   ├── TWLD-NOTES-FROM-THE-KING.md
│   ├── NOTES-FROM-THE-KING-WEBSITE.md
│   ├── CHEK-NOTES.txt
│   ├── TWLD-INTERLUDE-THE-THIEF.md
│   ├── TWLD-SAMPLE-PAIR.md
│   └── …
├── manuscript/                     # EDITABLE CANON — only here
│   ├── MANIFEST.md                 # every chapter's source & status
│   ├── front-matter/
│   │   ├── 00-sourcing-note.md
│   │   ├── 00-khuba-nura.md
│   │   ├── 00-disclaimer.md
│   │   └── 00-how-to-read.md
│   ├── chapters/
│   │   ├── 01-the-descent.md
│   │   ├── 02-the-stolen-garden.md  # ← kenosis correction applied HERE with approval
│   │   ├── 03-hidden-one.md
│   │   └── …
│   ├── companion/
│   │   ├── notes-from-the-king/    # clean 19, verbatim, with placement map
│   │   ├── poetry/                 # only when texts/rights cleared
│   │   └── art/                    # Anastasis + permissions
│   └── build/
│       └── read-aloud.md           # GENERATED from chapters/ — never hand-edited
├── reference/
│   ├── book-bible.md               # promoted from thats-what-love-does-book-bible.md
│   ├── decisions.md
│   ├── timeline.md
│   ├── continuity-register.md      # from audit §8 + new holes register
│   └── sourcing-register.md
└── platform/
    └── instructions.md             # "Insructions" preserved; typo kept in source, display name fixed in reference
```

**Build rule:** `manuscript/build/read-aloud.md` is generated from `manuscript/chapters/` via a manifest. Nobody edits it directly. That prevents the "two competing manuscripts" problem you have now (read-aloud vs. chapters-11-18 vs. first-10).

---

## 4. HOW A SINGLE CORRECTION GETS APPROVED

Example: Chapter Two's "took off His divinity."

1. Source-snapshot stays: "He took off His divinity" remains untouched in `source-snapshots/TWLD-MANUSCRIPT-THE-FIRST-10.md`.
2. Proposal logged in `reference/continuity-register.md`: "Ch.2 line X — settled kenosis correction 08/02/2026 — change to 'He surrendered the use of His divinity, not the divinity itself' — awaiting author yes/no."
3. You say yes (or "yes with this wording").
4. Edit applied ONLY in `manuscript/chapters/02-the-stolen-garden.md`.
5. `MANIFEST.md` records: `02 — CANON-DRAFT — source: TWLD-MANUSCRIPT-THE-FIRST-10.md Ch.2 — approved edit: kenosis — date: 2026-XX-XX`.

Same process for: 34 years → clarify, 46 → 44, Bridge City 15–16 → 14, Naomi 13 → 15, fire vs. Earl's order, 50 vs 15 dollars, etc. Batch them — don't trickle.

**What "the truth has to be the goal" means here:** If two sources disagree on a fact (e.g., homeless six weeks vs. two weeks), we don't average them. We bring both photographs to you and ask: *what happened?* Then we write the one true version in canon and note the conflict in the register. Memory + context, not invention.

---

## 5. NAMING CLEANUP (safe, no content change)

- Keep `Insructions` file in source-snapshots with original typo preserved. In `reference/` and `platform/` we display it as `instructions.md` with a note: "Source filename preserved with typo for provenance; this is the working copy."
- Keep `CHEK:NOTES` (colon in filename breaks some tools) as `CHEK-NOTES.txt` in canonical companion, source snapshot untouched.
- Promote `thats-what-love-does-book-bible.md` to `reference/book-bible.md` (lowercase → canonical) without changing its words.

---

## 6. ANSWER TO YOUR DEEPER POINT: TRUTH IS INTERPRETABLE

You're right that two people can witness the same truth and interpret it differently — that's exactly why the Gospels read differently. That's not a problem to hide; it's the premise of the book.

In the source system that means:

- **Facts are locked:** What happened, when, who was there, what was said — we preserve and reconcile toward one factual record.
- **Meaning is yours:** What it meant, what it felt like, what Jesus was doing in it — that's your witness, your interpretation, your voice. We never flatten it into generic inspirational prose. The whole Christ-side disclaimer (separate file) exists to say: "Four witnesses told one story four ways without contradicting each other. This is the fifth chair at the table — one man's true experience of the same King."

That distinction protects both honesty and beauty.

---

**Next step:** Approve this system (or tell me what to change), and I will generate the `source-snapshots/` + `manuscript/MANIFEST.md` skeleton without moving a word of your prose.
