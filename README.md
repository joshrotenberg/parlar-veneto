# Parlar Veneto

A practical, open-source introduction to the Venetian language for learners who
already know Italian. The book focuses on present-day central Venetian,
especially Padovano and Vicentino, while calling out important regional
variation.

The manuscript combines a beginner quick start and guided lessons with a
reference grammar, thematic vocabulary, proverbs, contemporary usage, cultural
context, and compact reference appendices.

## Build

```bash
# Install mdbook if needed
cargo install mdbook

# Build the book
mdbook build

# Run chapter tests and the project linter
mdbook test
mdbook-lint --config .mdbook-lint.toml src/

# Serve locally with hot reload
mdbook serve
```

## Project Status

All 25 planned chapters and four appendices have full first drafts. The project
is now in editorial development rather than initial scaffolding.

Current priorities are:

- Extend the initial three-lesson beginner path into a graded course
- Add short reading and listening material
- Review forms, regional labels, and IPA against cited sources
- Improve source attribution at the example level
- Add native-speaker audio when licensing and attribution permit

The text is usable now, but it should not yet be treated as a settled language
standard. Venetian has meaningful regional variation and no single universally
used orthography.

## Editorial Approach

- **Default variety:** central terraferma Venetian, mainly Padovano-Vicentino
- **Audience:** learners with roughly B1 or stronger Italian
- **Spelling:** one consistent learning orthography, with variants noted
- **Evidence:** scholarly references for grammar plus attributed contemporary
  examples for living usage
- **Variation:** regional and register differences are described, not ranked

Corrections from native speakers and specialists are especially welcome. A
useful report identifies the form, the speaker's area, the context or register,
and a source or natural example when possible.

## Selected Sources

### Scholarly
- Silvano Belloni, *Grammatica Veneta* (linguaveneta.net)
- El Galepin online Venetian–Italian–English dictionary
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

See the complete, annotated bibliography in
[Appendix D](src/appendices/app-d-sources.md).

## Structure

```
src/
  front/           # Preface, beginner quick start, conventions, map
  guided-lessons/  # Trilingual beginner lessons and practice
  part1-phonology/ # Sounds, changes, orthography
  part2-nominal/   # Articles, nouns, adjectives, pronouns
  part3-verbal/    # Verb system (9 chapters)
  part4-syntax/    # Sentence structure (3 chapters)
  part5-vocabulary/# Core vocab, etymology, expressions
  part6-living/    # Proverbs, contemporary, culture
  appendices/      # Verb tables, quick ref, glossary, sources
```

## License

[MIT](LICENSE)
