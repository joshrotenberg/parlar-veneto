# Parlar Veneto: A Practical Grammar of the Venetian Language

An mdbook project for learners of Venetian, designed for those who already know Italian.

## Build

```bash
# Install mdbook if needed
cargo install mdbook

# Build the book
mdbook build

# Serve locally with hot reload
mdbook serve
```

## Project Status

### Completed

- **Front Matter**
  - Preface (project philosophy, terraferma focus, attribution framework)
  - Abbreviations & Symbols (source citations, grammatical terms, phonetic symbols)

- **Part I: Phonology & Orthography** (Complete)
  - Chapter 1: The Sound System (vowels, consonants, evanescent l, voiced x)
  - Chapter 2: Sound Changes from Italian (degemination, v-drop, gl to j, gi to x)
  - Chapter 3: Orthographic Conventions

- **Part II: Nominal Morphology** (Complete)
  - Chapter 4: Articles (el/la/i/le, contractions)
  - Chapter 5: Nouns (gender, plurals, diminutives)
  - Chapter 6: Adjectives (agreement, position, comparison)
  - Chapter 7: Pronouns (emphatic, clitics, object, reflexive, relative)

- **Part III: Verbal Morphology** (In Progress)
  - Chapter 8: Overview of the Verb System
  - Chapter 9: Present Indicative
  - Chapter 10: Auxiliaries (esser & gaver)
  - Chapters 11-16: Skeleton only

- **Part IV: Syntax** - Skeleton only

- **Part V: Vocabulary** (Complete)
  - Chapter 20: Core Vocabulary by Theme (food/drink, greetings, expressions)
  - Chapter 21: Etymological Highlights (Greek, Germanic, Arabic loans)
  - Chapter 22: Expressive Language (exclamations, mona, intensifiers)

- **Part VI: The Living Language** (In Progress)
  - Chapter 23: Proverbs & Sayings (40+ proverbs by theme)
  - Chapters 24-25: Skeleton only

- **Appendices**
  - Appendix D: Sources & Further Reading (scholarly, contemporary, pronunciation resources)

### Remaining Work

- Front Matter: How to Use, Map of the Veneto
- Part III: Chapters 11-16 (irregular verbs, past, future, subjunctive, imperative, non-finite)
- Part IV: All chapters (sentence structure, questions, complex sentences)
- Part VI: Chapters 24-25 (contemporary Venetian, cultural context)
- Appendices A-C: Verb tables, quick reference, glossary

## Sources

### Scholarly
- Silvano Belloni, *Grammatica Veneta* (linguaveneta.net)
- El Galepin online dictionary (~37,000 entries)
- Giuseppe Boerio, *Dizionario del dialetto veneziano* (1856)

### Contemporary
- Rumatera (punk rock, Venice province)
- Herman Medrano (singer-songwriter)
- Canal il Canal (YouTube)
- @proverbiveneti, @venetosegreto (Instagram)
- @tommygondolier, @benedettapolato, @chiarasbakery (Instagram)

### Pronunciation
- Forvo.com (native speaker recordings)
- Omniglot (phrase audio)
- Localingual (field recordings)

## Structure

```
src/
  front/           # Preface, abbreviations, how-to-use, map
  part1-phonology/ # Sounds, changes, orthography
  part2-nominal/   # Articles, nouns, adjectives, pronouns
  part3-verbal/    # Verb system (9 chapters)
  part4-syntax/    # Sentence structure (3 chapters)
  part5-vocabulary/# Core vocab, etymology, expressions
  part6-living/    # Proverbs, contemporary, culture
  appendices/      # Verb tables, quick ref, glossary, sources
```

## License

TBD
