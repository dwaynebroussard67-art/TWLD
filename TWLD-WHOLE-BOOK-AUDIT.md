# THAT'S WHAT LOVE DOES — WHOLE-BOOK AUDIT

**Audit date:** 2026-11-10  
**Scope:** the complete repository after merging PRs #1, #3, #4, and #5 into `main`  
**Purpose:** distinguish source material, drafted manuscript, settled decisions, open decisions, and missing work.  
**Editorial boundary:** no manuscript prose was changed in this audit.

---

## 0. THE BOTTOM LINE

This is a real book with a strong voice, a clear theological center, and a substantial autobiographical spine. It is **not yet a complete first draft of the book described by the Book Bible**.

The most useful honest estimate is:

- **Autobiographical spine through the arrest:** about **65–70% drafted**. The childhood and descent material is substantial, but the jail-cell rescue and most of what follows are absent.
- **Complete core first draft, measured against the Book Bible:** about **40–45% structurally complete**. The missing Jesus-side pairing, prequel, second and third rescues, intercut climax, and final commission carry more structural weight than their eventual word counts suggest.
- **Publication-ready finished book:** roughly **15–20%**. This is not a criticism of the prose. It reflects the work still ahead: structural completion, canonical selection, continuity revision, theological/source review, safe-messaging and privacy review, line editing, front/back matter, art, and design.

These percentages are editorial estimates, not measurements produced by Git. The Book Bible gives no target word count, so a word-count-only percentage would be misleading.

### What is already working

1. **The book knows what it is about.** The Harrowing, ongoing rescue, Khuba, the misfit reader, and the refrain are not decorative ideas. They form a real thesis.
2. **The childhood material has durable scenes and images.** The packed bag, the copper smell, the tall grass, the bathroom mirror, the parking lot, the heavy bag, and the cafeteria table give the abstract theology a body.
3. **The later draft contains the necessary emotional counterweight.** Mr. Dean, Miss Jean, the hospital chapel, fatherhood, custody, addiction, and arrest keep the book from becoming only an argument.
4. **The planned post-salvation fall is the strongest structural choice.** It prevents a false “prison fixed me forever” ending and makes Peter/John 21 a credible template for the last movement.
5. **There is enough raw material to finish.** The problem is not a lack of vision or source fragments. The problem is canonical selection, missing testimony at the end, and integration.

### The main blocker

The repository has **sources and compilations, but no declared canonical working manuscript**. The read-aloud file is a useful listening copy; it explicitly preserves duplicates and unresolved gaps. It is not a final-book manifest.

The next high-value move is therefore **not polishing chapters and not adding more Notes**. It is declaring one canonical outline and creating an editable working draft while preserving every locked source snapshot unchanged.

---

## 1. PULL REQUESTS: WHAT WAS MERGED

All four open PRs were content-only additions. None edited or deleted existing manuscript prose. No automated checks were configured on the PRs.

| PR | Content | Disposition | Integration status after merge |
|---|---|---|---|
| **#5** | `thats-what-love-does-book-bible.md` | Merged into `main` | Governing target/reference, but its status report is stale and its outline conflicts with the newer later-chapter draft. |
| **#4** | `CHEK:NOTES` — 17 Notes from the King | Merged into `main` | Preserved as an uploaded source snapshot. It is a near-duplicate of Notes I–XVII in `NOTES-FROM-THE-KING-WEBSITE.md`, with mostly punctuation/typography differences. It adds no clearly new note. |
| **#1** | `TWLD-INTERLUDE-THE-THIEF.md` and `TWLD-TIMELINE.md` | Merged into `main` | Both are working material. Neither is integrated into the read-aloud manuscript or approved as final canon. |
| **#3** | `Insructions` — website/platform directives | Merged into `main` | Platform reference only. It is not book content, and this repository contains no website implementation to audit against it. |

**Current PR state:** no open pull requests remained after the merges.

Merging a PR preserved the material in `main`; it did **not** declare that material theologically approved, chronologically correct, or part of the final reading order.

---

## 2. REPOSITORY LAYOUT AS IT EXISTS NOW

The repository is a document archive, not a manuscript build system. There are 17 pre-audit files, no application code, no tests/CI checks, no manuscript manifest, no final chapter directory, and no art files.

| File | What it really is | Canonical role today | Important caveat |
|---|---|---|---|
| `README.md` | Author's request for help and instruction not to alter verbatim words | Governing intention | Calls for a canonical version, but does not define one. |
| `TWLD-MANUSCRIPT-THE-FIRST-10.md` | Recovered, locked source paste: introductions, Chapters 1–10, and a non-locked appendix | **Immutable primary source snapshot** | Contains two Introduction Part II versions and the Chapter Two theology later marked for correction. |
| `TWLD-CHAPTERS-11-18.md` | Later-chapter source drafts recovered from AI conversation archives | **Draft source, not clean canon** | Two Chapter Thirteens, three Chapter Eighteens, thread IDs, drafting prompts, alternate-draft references, and factual conflicts. |
| `THATS-WHAT-LOVE-DOES-READ-ALOUD.md` | Verbatim working compilation of selected intro, Chapters 1–10, all later variants, and closing reflections | **Derivative listening/review copy** | It intentionally retains provisional numbering and editorial notes. It must not be mistaken for the finished manuscript. |
| `TWLD-CLOSING-REFLECTIONS.md` | Two present-tense reflections collected for possible end use | **Source material** | Placement is expressly undecided; one piece is locked verbatim and contains an age conflict. |
| `TWLD-INTERLUDE-THE-THIEF.md` | New Dismas/Harrowing dramatic draft with source notes | **Unintegrated imaginative draft** | Contains invented dialogue and scenes. It conflicts with the stated “no words in His mouth or His head” rule unless the author grants a specific exception. |
| `TWLD-NOTES-FROM-THE-KING.md` | 22 archived records containing raw dictation, AI responses, written-up versions, and unrelated site/discussion material | **Raw provenance archive** | Not 22 clean, publication-ready Notes; not safe to publish wholesale as “my words only.” |
| `NOTES-FROM-THE-KING-WEBSITE.md` | Clean reading collection of Notes I–XIX | **Best current clean Notes source** | The introduction says “Seventeen notes,” but the file actually contains 19. Placement in the book is undecided. |
| `CHEK:NOTES` | Uploaded 17-note plain-text collection | **Redundant source snapshot** | Near-duplicate of the first 17 website Notes. Keep for provenance; do not maintain as a second editable master. |
| `TWLD-DECISIONS.md` | Decision log with LOCKED / SETTLED / OPEN labels | **Historical governing reference** | Some entries are stale or internally contradictory: later chapters are called unwritten; Chapter Ten's age conflicts with the newer timeline; the closer is both settled and open. |
| `thats-what-love-does-book-bible.md` | Newly merged synthesis of concept, rules, sources, 26-chapter architecture, and missing material | **Target architecture/reference** | Its statement that Chapters 11–18 were not drafted is no longer true. Its outline also predates and duplicates later material. |
| `TWLD-RECOVERY.md` | August recovery report and theological pressure test | **Historical reference** | It points to an external PDF and archive files that are not in this repository. Its manuscript-status statements are stale. |
| `TWLD-TIMELINE.md` | New working chronology and requested locked-text corrections | **Latest chronology worksheet, not applied canon** | Resolves some dates by assertion but leaves manuscript conflicts and adds no approved edits. |
| `TWLD-SPOKEN-ARCHIVE.md` | First-person dictated testimony with minimal cleanup and explicit gaps | **High-value factual source** | Contains unresolved questions, a lost car-crash account, and variants that conflict with drafted chapters. |
| `TWLD-SAMPLE-PAIR.md` | Experimental demonstration of the age-paired device | **Placeholder/proof of concept only** | It expressly says the voice is a placeholder. Its invented writing by Jesus also needs a ruling under the interiority/speech rule. |
| `TWLD-ARCHIVE-INDEX.md` | Index into two large Gemini Takeout archives | **External-source locator** | The raw `Nura_Master_Thread__1_.txt` and `Wife_Master_Thread__1_.txt` files are absent, so indexed records cannot be verified from this repo alone. |
| `Insructions` | Directives for a separate website/platform | **Non-book platform reference** | Filename is misspelled, but renaming was not necessary for this audit. No platform source code is present here. |

### Material referred to but not actually present

- The original `ThatsWhatLoveDoes.TheFirst10.pdf`.
- The two raw master-thread archives indexed by `TWLD-ARCHIVE-INDEX.md`.
- The actual poem texts behind the “Poetry of the Have-Nots” index entries.
- The complete Misfit Manifesto and other archive-only doctrine/source documents.
- A verbatim transcript of the full Friday welcome/fire teaching required by the ending decision.
- Licensed/selected Anastasis artwork or any other book art.
- A complete sourcing note, bibliography, permissions log, or fact-check register.

The index is valuable, but an index entry is not the same thing as recovered manuscript content.

---

## 3. WHAT THE CURRENT MANUSCRIPT ACTUALLY CONTAINS

### 3.1 Draft units, not “18 finished chapters”

The read-aloud compilation contains:

- Two selected introduction sections.
- Chapters One through Ten.
- Eleven later chapter units: Chapter Eleven, Chapter Twelve, **two Chapter Thirteens**, Chapters Fourteen through Seventeen, and **three Chapter Eighteens**.
- Two closing reflections.

That is **21 numbered chapter units representing labels 1–18**, not 18 integrated chapters.

The duplicate labels are not merely numbering mistakes:

- The two Chapter Thirteens are alternate treatments of the same baptism/wilderness material. “The First Rebel” is longer and more rhetorically developed; “The King in the Wilderness” is shorter. They need one selected/merged canonical treatment, not two adjacent chapters.
- The three Chapter Eighteens substantially repeat the same addiction, robbery, and arrest sequence. Each also contains unique details and factual differences. They need a fact-checked consolidation decision, not automatic deletion of two files.

### 3.2 Useful selected word count

A mechanical count of the read-aloud narrative, excluding drafting metadata/prompts and counting only one Chapter Thirteen and one Chapter Eighteen, gives approximately:

| Material | Approximate words |
|---|---:|
| Selected introductions | 931 |
| Chapters 1–10 | 6,599 |
| Later material, selecting one Chapter 13 and one Chapter 18 | 5,584 |
| Two closing reflections | 1,100 |
| **Selected current narrative subtotal** | **14,214** |

For comparison:

- The same narrative with **all** Chapter 13/18 variants included is about **15,660 words**.
- The new thief interlude is about **2,712 words including its notes**.
- The clean 19-note website collection is about **3,691 words**, but it is not currently core manuscript text.

These counts describe available material, not approved final prose. The 14,214-word subtotal still includes unresolved theology, timeline conflicts, and unsafe/private material requiring review.

### 3.3 Where the story stops

The autobiographical draft currently reaches the arrest. The Book Bible's defining movements after that point are not drafted as a continuous narrative:

1. The jail-cell second meeting at age 33.
2. The intercut between the historical Harrowing and the cell.
3. Release and the subsequent fall—the decision log's true rock bottom.
4. The third rescue using Peter/John 21 as the structural template.
5. The present-tense desk ending and turned commission toward the reader.
6. The Jesus-side Great Commission counterpart.
7. The exact Friday teaching and final “Are you coming?” sequence.

There are present-tense reflections and Notes that can feed the ending, but they are not the ending itself.

---

## 4. THE BOOK BIBLE VERSUS THE REPOSITORY

### 4.1 The Bible is a target, not a current status report

The Book Bible says Chapters 11–18 “have not been drafted or shared.” That was true of an earlier recovery point, but it is false of the current repo. `TWLD-CHAPTERS-11-18.md` now contains substantial prose.

The Bible also puts “ages 16–33, the long fall to prison” in proposed Chapter 21 and marks it as needing material. The newer Chapters 11–18 already cover much of that same territory. Consequently, the team must not mechanically write Bible Chapters 19–26 on top of the existing later draft; that would duplicate the descent.

### 4.2 The Bible's own outline no longer reconciles with the actual chapters

Its Part One table proposes 18 alternating chapters built around nine existing autobiographical titles. But:

- It does not cleanly account for the current Chapter One, “The Descent,” as an age-paired autobiographical chapter.
- “The Stolen Garden” is itself largely theological/Harrowing material, not a simple one-side childhood chapter.
- The actual manuscript now has autobiographical material labeled through Chapter Eighteen.
- The two Chapter Thirteens concern Jesus's baptism/wilderness at about age 30, while their placement beside post-LTI material at roughly 17–18 does not fulfill same-age pairing.
- The 22/19–24/27–28 architectures already flagged in `TWLD-DECISIONS.md` were never collapsed into one manifest.

**Conclusion:** the Bible remains the best statement of intention, but its numbering cannot be declared canonical without revision.

### 4.3 Requirements scorecard

| Book Bible requirement | Repository evidence | Status |
|---|---|---|
| Parallel-biography frame; Jesus's story with D as mirror | Locked in decisions; partial Jesus passages and one wilderness pair of variants | **Decided, weakly implemented.** Chapters 3–10 mostly drop the sustained alternation. |
| Feeling over action | Strong sensory/emotional writing throughout | **Implemented strength.** Preserve during revision. |
| No invented Christ interiority or speech | Rule locked; sample and new interlude invent speech/actions | **Decision and drafts conflict.** Author ruling required. |
| Khuba and Nura as deliberate paired terms | Both appear in intro and chapters | **Present but not consistently defined.** Needs one exact ruling and linguistic/source verification. |
| Two-tier Scripture/ancient-tradition sourcing | Decision log and Bible explain it; interlude has notes | **Decided, not implemented as front matter or a book-wide citation system.** |
| Selected introduction | Two versions in source; later version selected for read-aloud | **Working selection exists; print canon not formally declared.** |
| Prosperity-gospel Introduction Part III and later reprise | Appendix candidate and decision-log argument | **Planned/partial source, not a settled front-matter chapter.** |
| Prequel: Hidden One / seven heavens / curse of fathers | Outline only | **Not drafted as an integrated prequel.** Family history is absent. |
| Autobiographical childhood through LTI | Chapters 1–10 | **Substantially drafted.** Timeline, safety, and mirror issues remain. |
| Jesus-side birth-to-cross sequence | Brief passages, Chapter Two theology, two wilderness variants, thief interlude | **Mostly missing as a complete paired sequence.** |
| First meeting at age nine | Chapter Seven parking-lot scene | **Drafted and strong.** Placement/labeling within the three-rescue arc remains to be formalized. |
| Autobiographical descent, roughly 16–33 | Chapters 11–18 through arrest | **Substantial but noncanonical draft.** Major chronology conflicts and duplicate variants. |
| Historical Holy Saturday Harrowing | Intro/Chapter One and new thief interlude | **Drafted in more than one form; final placement and imaginative-license rule unresolved.** |
| Second meeting in cell and iron-door intercut | Referenced in plans and sample device | **Core scene missing.** |
| Post-rescue fall / true rock bottom | Ruled in decisions; no continuous narrative | **Core testimony missing.** |
| Third rescue through Peter/John 21 | Theological plan and supporting texts | **Not drafted.** |
| Ending at desk, refrain flipped, reader addressed | Closing reflections and Notes supply fragments | **Not assembled; present-tense truth still needed.** |
| Great Commission counterpart | Decision only | **Not drafted.** |
| Exact Friday welcome/fire teaching and “Are you coming?” | Note XVII supplies a polished fire/commission version | **Partial material, not verified verbatim full teaching; final sequence unresolved.** |
| Notes from the King | 22 raw records, 19 clean website Notes, 17-note duplicate upload | **Substantial collection; zero canonical placement.** |
| Poetry and visual add-ons | Index entries and plans | **Essentially unintegrated; actual poems/art absent from repo.** |

---

## 5. A PROVISIONAL “WHERE THE PIECES GO” MAP

This is an integration recommendation, **not a silent renumbering or a new locked outline**. It preserves the existing story while honoring the Bible's intended arc.

### Movement A — Frame and covenant

**Use:** selected “Tablet of My Heart”; selected “Harrowing and the Flesh”; current Chapter One and Chapter Two as frame material or carefully separated paired material.  
**Still needed:** author-approved Chapter Two correction; Khuba/Nura definition; sourcing note; decision on the prosperity appendix as Introduction Part III.

**Why:** these sections tell the reader how to read the book. They should not be forced into an artificial childhood age pair simply to preserve old numbering.

### Movement B — Prequel: before the bloodline

**Planned:** 1 Enoch “Hidden One”; Ascension of Isaiah descent, labeled ancient tradition; documented father/grandfather pattern.  
**Current status:** plan only.

### Movement C — Parallel descent: childhood through LTI

**Use:** current Chapters Three through Ten and relevant parts of One/Two after the frame decision.  
**Add:** the short, restrained Jesus-side age pairs; the ages 13–18 Bible-study material in the spoken archive where chronologically appropriate.  
**Decide:** whether Chapter Ten stays compressed or is split as proposed in `TWLD-SAMPLE-PAIR.md`.

### Movement D — Sanctuary, fatherhood, and the long fall

**Use:** current Chapters Eleven, Twelve, Fourteen through Seventeen.  
**Move:** the baptism/wilderness Chapter Thirteen variants to the Jesus thread near age 30, rather than treating them as same-age companions to seventeen-year-old material.  
**Recover/decide:** Earl's Furniture, the car crash, the driveway details, and the factual chronology before consolidation.

### Movement E — Arrest and the second Harrowing

**Use:** one consolidated, fact-checked arrest narrative drawn from the three Chapter Eighteen variants.  
**Add:** the actual cell experience and the iron-door intercut.  
**Possible placement for the thief interlude:** within or immediately before this intercut, but only after the author rules on its invented speech/scenes and selects it over or alongside the existing Harrowing frame.

### Movement F — After the happy ending

**Add:** release, the subsequent fall, the third rescue, Peter/John 21, and the ongoing—not completed—sanctification arc.  
**Use as sources, not substitutes for scenes:** “A Note from the King,” “A Word on Loyalty and Love,” and relevant Notes such as “The Right Now Heart” and “What I Taught My Demons.”

### Movement G — Commission and open door

**Add:** the desk ending, the refrain flipped into action, direct address to the reader, Great Commission counterpart, and exact Friday teaching.  
**Candidate final door:** Note XVII, “Are You Coming?”  
**Needs explicit confirmation:** “Are you coming?” as the final line, with “Give me one more breath…” as the hinge rather than the closer.

### Companion material — Notes, poetry, sources, and art

**Recommended default:** keep the Notes as a companion section after the core narrative unless a small number are deliberately chosen as interludes. Inserting all 19 would interrupt the parallel biography and turn the last third into a devotional anthology.

**Strong candidates for intentional placement:**

- “Baptism Is a Funeral” near the baptism thread.
- “The Right Now Heart” and “What I Taught My Demons” in the post-rescue movement.
- “Are You Coming?” at the final door.
- “The Name Is Not a Rank” near the commission/reader address.

**Do not integrate yet:** poetry and artwork whose actual files/rights are not in the repo.

---

## 6. DECISIONS ALREADY MADE

The following are recorded as LOCKED or SETTLED in `TWLD-DECISIONS.md` and/or carried into the Book Bible. “Made” does not always mean “implemented.”

### Frame and voice

- The book is presented as **Jesus's story**, with D's life as the mirror, rather than being labeled simply a memoir.
- The intended device is age-paired parallel narrative, converging in a jail cell.
- **Feeling over action** governs the storytelling.
- Inference must be possible, plausible, theologically grounded, and never cast a shadow on Christ.
- The author's stated rule is not to claim Christ's interior life or put words in His mouth/head.
- The silent-years imbalance is intentional: His sections may be short and quiet while D's are long and loud.

### Theology and sourcing

- The Harrowing/Holy Saturday is the theological center; the rescue is ongoing rather than a single past event.
- The age-33 convergence is intended to govern the climax.
- The age-nine encounter, age-33 cell, and later fall form a sanctification arc rather than a simple conversion arc.
- The book must not end with “fixed forever.”
- Peter/John 21, not Adam alone, is the template for the third rescue and commission.
- Ethiopian-canon material and ancient devotional tradition are to be labeled in two tiers; Aquarian Gospel/Notovitch material is excluded.
- The Chapter Two correction is settled conceptually: divinity was not surrendered; the use of divine prerogative was. **The old wording still remains in both manuscript copies.**
- The prosperity-gospel thesis belongs near the front and before the climax. “Suffering is the curriculum, not the grade” is the governing correction.

### Refrain, prequel, and ending

- “And that's what love does” is the primary refrain; it should eventually flip from rescue received to mission enacted.
- “Give me one more breath, and I'll breathe for both of us” is protected language.
- The prequel is planned around the Hidden One, descent through the heavens, and generational father history.
- The ending is planned at the desk, then direct reader address, the Friday teaching, the Great Commission counterpart, and an open question rather than tidy recovery.

### Important qualification

The decision log calls “Are you coming?” the final line in Section IX but lists the closer as still requiring an explicit ruling in Section XI. Treat it as the **leading recorded choice**, not an unquestionable final canon decision.

---

## 7. DECISIONS STILL PENDING

### 7.1 Structural decisions that block clean drafting

1. **One canonical outline and numbering system.** Reconcile the Bible's 26-chapter plan with the newer Chapters 11–18 before drafting more.
2. **Strict alternation versus braided chapters.** The current manuscript often blends both threads inside one chapter. Decide whether that is the real device or whether separate age-paired chapters must be restored.
3. **Immutable sources versus editable canon.** “Never change locked text” and “apply settled corrections” can coexist only if originals are preserved as immutable sources and a separate working manuscript receives approved revisions.
4. **Chapter Ten compression or split.** `TWLD-SAMPLE-PAIR.md` explicitly leaves both options open.
5. **Chapter Thirteen selection.** Choose one wilderness variant or approve a merge.
6. **Chapter Eighteen consolidation.** Decide the factual sequence and which unique images/details survive; do not choose only by prose polish.
7. **Placement of the thief interlude.** Mid-book interlude, climax intercut, replacement for part of Chapter One, or companion material.
8. **The final ending that is true now.** The desk ending cannot be honestly completed from aspirational summaries.

### 7.2 Christ-side imaginative-license decision

The no-speech/no-interiority rule conflicts with:

- Direct dialogue and dramatic invention throughout `TWLD-INTERLUDE-THE-THIEF.md`.
- The invented potsherd saying in `TWLD-SAMPLE-PAIR.md`.
- Some direct speech already present in earlier manuscript chapters.

The author needs one consistent rule. Options include: strict rule everywhere; clearly labeled imaginative interludes as exceptions; or paraphrase/indirect narration only. This decision affects multiple files and should be made before further Jesus-side drafting.

### 7.3 Notes and add-ons

- Are Notes from the King a companion section, selected interludes, a separate book, or website-only material?
- Which source is the clean Notes master? Recommendation: the 19-note website file, after correcting its “Seventeen” label in a canonical copy, while preserving all originals.
- Which Notes are verbatim dictation, which are “dressed for the page,” and which contain AI-written expansion? The platform directive says “my words only,” so provenance must be explicit.
- Does the potsherd device belong in the book? It is currently only a placeholder demonstration.
- What poetry is actually yours, which poems belong in the book, and where do they sit?
- Will the Anastasis image be reproduced, referenced, or used as cover/interior art, and under what license?

### 7.4 Editorial and publishing decisions

- Approve or reject each requested change to locked prose; do not silently correct source snapshots.
- Confirm the final-line choice and the role of the breath refrain.
- Decide the treatment of explicit profanity and slurs in a canonical reading edition.
- Approve a safe-messaging revision. The decision log says to remove method-specific self-harm detail, but such detail remains in the current draft, alongside detailed intended violence.
- Decide real names versus pseudonyms and obtain appropriate permissions/legal review. The manuscript names private people and includes allegations of abuse, custody misconduct, crimes, addiction, medical information, and police/judicial wrongdoing.
- Decide how doctrinal claims will be reviewed. A Tewahedo-informed reviewer plus a broader theological/source editor would reduce the risk of presenting contested interpretation as uncontested fact.

---

## 8. CONTINUITY AND FACTUAL REGISTER

These are not line-editing nitpicks. Several change the architecture.

| Issue | Current conflict | Required action |
|---|---|---|
| Rescue/arrest age | New timeline pins the cell at **33 (2015)**; Chapters 17–18 say “by thirty”; Chapter One says “thirty-four years.” | Author must establish the actual arrest/cell year and distinguish arrest, conversion, and later bottom if they occurred in different years. |
| Present age | Timeline says **44 in August 2026**; locked closing reflection says **46**. | Approve correction in canonical copy or establish a different birth/date fact. |
| Bridge City/LTI age | New timeline says **14 in 1996**; older decisions and source labels use 15–16. | Confirm one chronology and update the age map. |
| Sebastian's birth | New timeline says author age **21–22**; Chapter Fifteen says **twenty**. | Confirm birth year/age. |
| “Five-year forge” | Chapter Fifteen describes stability from 20–25 before a child is taken at about six months; spoken archive places birth at 21–22 and removal in infancy. | Rebuild this period's sequence and retitle if needed. The current version cannot all be literally simultaneous. |
| Naomi | Chapter Fourteen says met at thirteen; spoken archive says together since fifteen; chapter also gives 17–21 as the happy period. | Distinguish first meeting, relationship start, reunion, and breakup. |
| Homeless duration | Chapter Eleven says **six weeks**; spoken archive says **two weeks**. | Confirm duration and how long Mr. Dean's driveway was part of it. |
| Fire/car/Earl sequence | Spoken archive places the fire after Earl's and the car; new timeline asks to settle “right after LTI.” | Establish exact order; recover the lost crash account if possible. |
| Texas/addiction years | Chapter Seventeen gives return at 25 and crisis at 30; timeline uses broader 26–30 and 33 pins. | Build one dated sequence for Texas, Gabriel, hand injury, marriage, prescription, and arrest. |
| Robbery/arrest variants | Chapter Eighteen variants differ on first versus repeat robbery, tactical-team abbreviation, and arrest details. | Establish facts before selecting prose. |
| Childhood films | Chapter Three attaches specific films to ages 2–3; new timeline flags release-date/age concerns. | Verify memory framing; avoid false precision if the age is uncertain. |
| Early-chapter age map | The decisions file calls it a longstanding blocker; timeline pins only some chapters. | Complete one authoritative age map for every proposed pair. |
| Spoken-archive parked questions | Retiring man's wish, car cosigner, lost crash, $50/$15, Mr. Dean's motive, and medical wording remain unresolved. | Answer only from testimony; mark unknown rather than invent. |

### Source/theology/fact-check flags

- **“Taleheding traditions”** remains unrecognized and unresolved in Chapter Three.
- **Khuba/Nura** need consistent definitions and independent Aramaic linguistic verification, not only repeated internal usage.
- The Chapter Two kenosis correction is not yet applied.
- The interlude's Dismas name, mission, splinter, blessing, dialogue, and several scenes are explicitly author additions/tradition, not canonical narrative.
- The Notes' mathematical statement that infinity divided by infinity is infinity is not mathematically reliable as written; the spiritual analogy needs a different verified formulation if retained.
- Historical claims about sources, canon, Christian etymology, baptism, and ancient tradition need a bibliography and qualified review.
- Broad causal/medical assertions and categorical doctrinal formulations should be identified as testimony, interpretation, or sourced claim rather than left unlabeled.

This audit does not attempt to settle those theological or historical questions itself.

---

## 9. CRAFT ASSESSMENT: WHAT TO PROTECT AND WHAT TO REVISE LATER

### Protect

- **The South Louisiana sensory register.** Place is most convincing when carried by dew, cicadas, vinyl, copper, cane smoke, wood, concrete, and light.
- **The honest self-indictment without a false hero ending.** The hospital chapel and fatherhood scenes are especially useful because they complicate rather than merely condemn the narrator.
- **The protectors.** Joe, Teddy, the probation officer, Mr. Dean, and Miss Jean embody the thesis before the narrator can explain it.
- **The recurring hand/door/fire/light imagery.** These can unify the Harrowing and the lived scenes without more explanation.
- **The short quiet Christ-side concept.** The imbalance can be powerful if it is consistent and does not invent certainty to fill silence.

### Revise after the complete draft exists

- **Repeated stock language.** “Atmosphere,” “Matrix,” “gladiator,” “absolute,” “heavy,” “violent,” “rotting man,” “there is no good in D,” and related formulas sometimes substitute for new scene-specific perception. Revision should preserve the voice while making repetition intentional.
- **Summary versus scene.** Several later chapters compress years into explanation. The cell, fall, and third rescue need lived scenes, not only doctrinal summaries.
- **The title refrain's placement.** “That's what love does” is strong in the opening but sparse through much of the current narrative. It has not yet performed the full chorus/flip function described by the Bible. Add by structure, not by frequency target.
- **Variant redundancy.** Do not line-edit three versions of the arrest before selecting the canonical facts and scene.
- **Drafting artifacts.** Thread IDs, “other drafts,” AI questions, and publishing prompts must remain in source files but be excluded from the canonical reading copy.
- **Provenance.** Distinguish verbatim dictation, minimally cleaned speech, author-approved AI-assisted prose, and placeholders. That protects both the author's ownership rule and future revision work.

None of this requires flattening the profanity, theology, or emotional force into generic inspirational prose.

---

## 10. RECOMMENDED CANONICAL REPOSITORY SYSTEM

Do not move or rewrite everything in one destructive pass. First declare roles in a manifest; then create the canonical draft by copying approved selections.

A future layout could be:

```text
manuscript/
  MANIFEST.md                 # canonical order, status, source for every unit
  front-matter/
  prequel/
  chapters/
  ending/
source-snapshots/             # locked uploads and recovered pastes; immutable
  TWLD-MANUSCRIPT-THE-FIRST-10.md
  TWLD-CHAPTERS-11-18.md
  CHEK-NOTES.txt
reference/
  book-bible.md
  decisions.md
  timeline.md
  continuity-register.md
  sourcing-register.md
notes-from-the-king/
  raw-master.md
  reading-collection.md
  placement-map.md
testimony/
  spoken-archive.md
  missing-testimony.md
experiments/
  sample-pair.md
  thief-interlude.md          # until approved for canon
companions/
  poetry/
  art/
platform/
  instructions.md
build/
  read-aloud.md               # generated from canon, never independently edited
```

### Status labels for the manifest

- `SOURCE-LOCKED` — preserved exactly; never silently edited.
- `CANON-DRAFT` — selected into the current working book; may receive author-approved revision.
- `VARIANT` — alternate source retained outside canon.
- `REFERENCE` — Bible, timeline, decisions, research.
- `PLACEHOLDER` — not author-approved prose.
- `MISSING` — required by the outline but not drafted.
- `NEEDS-RULING` — blocked by an author decision.

The key rule: **edit the canonical copy, never erase the source evidence.** The read-aloud file should eventually be generated from the canonical manifest so it cannot drift into a second competing manuscript.

---

## 11. FASTEST RESPONSIBLE ROUTE TO A COMPLETE FIRST DRAFT

### Phase 1 — Lock the container, not more prose

1. Approve the immutable-source/editable-canon workflow.
2. Produce one outline that reconciles the Bible with Chapters 11–18.
3. Assign every existing unit a slot and status.
4. Select the working Notes master and keep it outside the core count for now.

### Phase 2 — Recover only the missing load-bearing testimony

Prioritize:

1. The arrest/cell year and the actual second meeting.
2. Release and the post-salvation fall.
3. The third rescue and what “He came again” concretely refers to.
4. The honest present-tense situation at the desk.
5. The exact Friday teaching.
6. Father/grandfather documentation for the prequel.
7. The chronology conflicts in Section 8.
8. The parked spoken-archive questions, where memory permits.

No method-specific self-harm detail is needed to answer these.

### Phase 3 — Draft the missing spine before polishing

Recommended order:

1. Cell/second Harrowing.
2. Fall and third rescue/John 21.
3. Desk ending and commission.
4. Missing Jesus-side pairs and Great Commission counterpart.
5. Prequel and sourcing/front matter.
6. Consolidate Chapters 13 and 18 and complete the age-paired arrangement.

This order ensures the book has an ending before effort is spent beautifying the middle.

### Phase 4 — Integrate the living material

- Place only the Notes that perform a structural job; keep the rest as a companion collection.
- Add actual poems and art after their texts, authorship, placement, and rights are known.
- Add source notes/bibliography and the Anastasis explanation/image.
- Generate a new clean read-aloud copy from canon.

### Phase 5 — Separate revision passes

1. **Truth and chronology pass** with the author.
2. **Structure and scene pass** for pairing, repetition, pacing, and payoff.
3. **Theology/source pass** with qualified reviewers.
4. **Safety, privacy, permissions, and legal pass.**
5. **Voice/line pass** that protects approved language and removes accidental formulas/artifacts.
6. **Read-aloud and proof pass.**
7. **Book design and add-on pass.**

A finished book should not be attempted in one undifferentiated “re-edit.”

---

## 12. THE NEXT DECISION SHEET

The shortest useful next author session can answer these eight items:

1. **Canon workflow:** preserve originals and revise a separate canonical copy — yes/no?
2. **Architecture:** revise the Bible into the movement map above, or insist on its original 26-number outline?
3. **Christ-side license:** strict no invented speech everywhere, or labeled imaginative exceptions?
4. **Chronology:** what are the actual arrest/cell year and age, and which timeline corrections are approved?
5. **Variants:** which Chapter 13 treatment and what factual content belongs in the consolidated Chapter 18?
6. **Ending:** is “Are you coming?” the final line, and what is true at the desk today?
7. **Notes:** companion collection, selected interludes, or separate work?
8. **Publishing boundaries:** approve safe-messaging revision and a real-name/privacy/legal review?

Once those are answered, the project can move from archive recovery to actual first-draft completion without continually rebuilding the same chapters.

---

## 13. FINAL JUDGMENT

The repo is closer than the old recovery documents suggest and farther from finished than the label “Chapters 1–18” suggests.

The strongest asset is not the number of files. It is that the book already has a **coherent moral and narrative engine**: Love descends, the rescued man falls again, Love descends again, and the rescued man is sent back for others.

The missing work is concentrated and identifiable:

- one canonical architecture;
- the complete Jesus-side mirror;
- the cell and everything after it;
- factual chronology decisions;
- approved corrections to locked text in a separate canon;
- integration of Notes, poetry, sources, and art;
- the publishing safety/privacy/theology passes.

**Estimated distance to a complete core first draft: roughly 55–60% of the structural work remains.**  
**Estimated distance to a finished publication: substantially farther, because the most important revision passes cannot responsibly begin until that draft exists.**

The next milestone should be a complete, imperfect, chronologically honest draft from prequel to “Are you coming?”—not a more polished opening third.
