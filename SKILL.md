---
name: kirby-voice-dna-extractor
description: "Codifies an author's unique voice, sentence cadence, vocabulary, and ideological stance into a portable Voice DNA Specification to de-genericize AI outputs."
category: writing
triggers: [extract-voice, voice-dna, writing-style-analysis, voice-profiler, author-voice, tone-analysis]
---

# SOP: Author Voice DNA Extraction & Codification

> Standard Operating Procedure for reverse-engineering an author or creator's unique human writing style into a deterministic, machine-enforceable Voice DNA Profile.

---

## 1. The Voice DNA Problem

Generic AI text and raw PLR share the same flaw: **tonal neutrality**. They read like a composite average of the entire internet. When human readers encounter this, subconscious alarms fire: *"This is a machine, or someone who has nothing distinct to say."*

Voice is not an abstract vibe; it is a measurable set of linguistic, rhythmic, and psychological markers:
* **Cadence:** Sentence length variance, fragment usage, transition words.
* **Lexicon:** Signature verbs, idiomatic expressions, regional dialect, banned clichés.
* **Posture:** Worldview, contrarian biases, level of vulnerability, pedagogical stance (mentor vs. peer vs. drill sergeant).

This skill interrogates writing samples or runs a live interview to produce a **Voice DNA Specification** that any downstream agent or rewriting pipeline can enforce.

---

## 2. The 5 Pillars of Voice DNA

```
┌─────────────────────────────────────────────────────────┐
│                    VOICE DNA MATRIX                     │
├─────────────────┬───────────────────────────────────────┤
│ 1. Cadence      │ Sentence length variance & fragments  │
│ 2. Posture      │ Authority relationship to reader      │
│ 3. Lexicon      │ Signature terms vs. taboo buzzwords   │
│ 4. Vulnerability│ Balance of scars vs. advice           │
│ 5. Formatting   │ Bullet rhythm, line breaks, emphasis  │
└─────────────────┴───────────────────────────────────────┘
```

### Pillar 1: Cadence & Rhythm
- **Staccato vs. Flowing:** Does the author use 3-word punchy lines (*"Stop doing that. It fails."*) or compound, rhythmic clauses?
- **Fragment Density:** Frequency of grammatically incomplete sentences used for emphasis (*"Not a chance."*, *"Every single time."*).
- **Paragraph Length:** Single-sentence punchlines vs. dense 4-sentence analytical blocks.

### Pillar 2: Posture & Relational Dynamic
- **The Peer-in-the-Trenches:** *"I tried this last Tuesday and burned $400 so you don't have to."*
- **The Pragmatic Mentor:** *"You can ignore this, but your bank balance will reflect it."*
- **The Iconoclast:** Calls out sacred cows and mocks industry consensus.

### Pillar 3: Lexical Signature & Taboo Words
- **Signature Verbs & Slang:** Words unique to the author (e.g., *slog, butcher, unlock, weaponize, grind, blueprint*).
- **Taboo Banned List:** Instant disqualifiers that reveal AI slop (e.g., *delve, tapestry, beacon, testament, game-changer, unlock your potential*).

### Pillar 4: Vulnerability & Scar Ratio
- Authentic voices don't just share victories; they share **embarrassing failures and costs**.
- Target ratio: At least 1 tangible failure or misstep per 1,000 words of educational content.

### Pillar 5: Formatting & Visual Structure
- Use of em-dashes, parenthetical asides `(like this)`, capitalization for emphasis, or numbered micro-lists.

---

## 3. Extraction Protocol

### Method A: Corpus Analysis (When Samples Exist)
1. Feed 3 to 5 samples of the author's raw, unedited writing (emails, blog posts, transcripts).
2. Run the **Linguistic Feature Extraction Query**:

```markdown
Analyze the provided text samples and extract the author's Voice DNA:
1. Sentence length distribution (short vs. medium vs. long).
2. Punctuation habits (em-dashes, semicolons, exclamation marks, parentheticals).
3. Level of directness (does the author hedge with "maybe/perhaps", or use absolute imperatives?).
4. Signature phrases and recurring metaphors.
5. Identify 10 words or styles this author would NEVER use.
6. Output a standardized Voice DNA Card.
```

### Method B: Socratic Interrogation (When No Samples Exist)
Ask the operator 5 targeted diagnostic questions:
1. *"If your favorite mentor and your most annoying competitor got into an argument, which side of the room would you stand on?"*
2. *"What is one popular belief in your industry that you think is complete nonsense?"*
3. *"Do you prefer explaining things with tight metaphors (machines/engines) or personal life stories (family/daily struggles)?"*
4. *"When someone makes an amateur mistake, do you comfort them or give them tough love?"*
5. *"Give me 3 phrases or buzzwords that make you cringe when you hear other creators say them."*

---

## 4. Voice DNA Specification Output Schema

Every extraction must output a machine-readable specification formatted as follows:

```yaml
---
voice_dna:
  author_id: "operator_01"
  posture: "Pragmatic Practitioner (direct, zero-fluff, tough love)"
  reading_level: "Grade 7-8 (accessible, punchy, clear)"
  cadence:
    primary_sentence_length: "8-14 words"
    fragment_frequency: "High (approx 2-3 per 250 words)"
    pacing: "Fast, punchy, conversational transitions"
  lexicon:
    signature_terms: ["slog", "feast-or-famine", "operational drag", "raw numbers", "stop guessing"]
    taboo_banned_words: ["delve", "tapestry", "game-changer", "moreover", "in conclusion", "beacon"]
    preferred_transitions: ["Look,", "Here is the truth:", "The real rub?", "Bottom line:"]
  formatting_quirks:
    use_em_dashes: true
    use_parenthetical_asides: true
    max_paragraph_lines: 3
  vulnerability_stance: "Openly cites specific dollar losses and wasted time from early career"
---
```

---

## 5. Downstream Integration

Once generated, save the Voice DNA spec as `voice_dna.yaml` or `voice_dna.json`. Downstream skills (`kirby-plr-personalizer`, `kirby-plr-email-sequences`, `kirby-plr-sales-converter`) ingest this spec to guarantee tonal consistency across all deliverables.
