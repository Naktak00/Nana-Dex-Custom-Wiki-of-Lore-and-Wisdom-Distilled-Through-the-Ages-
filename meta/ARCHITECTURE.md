# Nana-Dex Architecture

**Page type:** index  
**Claim status:** 🟣 Personal definition/model  
**Source posture:** v2 architecture proposal  
**Private boundary:** public-safe

## Purpose
Nana-Dex needs to scale from a handful of strong pages into a ludicrous wiki without becoming a maze or a mythology blender.

The architecture is simple:

1. Put every page in a known page type.
2. Mark the evidence status of claims.
3. Track source records separately from interpretations.
4. Link laterally, not only downward from the index.
5. Keep public research separate from Nana's private story.

## Top-level Zones
| Zone | Purpose | Current examples |
|---|---|---|
| `core/` | Methods, guardrails, and personal models used across the wiki | Logic Through Life, Xen, Guardrails |
| `goddex/` | Entity and taxonomy pages for gods, demons, spirits, archetypes, and transformations | Taxonomy, Astarte line |
| `research/` | Textual traditions, research maps, comparisons, and source-gathering pages | Grimoires, Keys of Solomon |
| `field-notes/` | Bounded observations with causal, interpretive, and personal layers separated | Light at the Desk |
| `sources/` | Source records and bibliography scaffolds | Source record template |
| `templates/` | Reusable page schemas | Entity, text, concept, field note, source |
| `meta/` | Architecture, queues, AARs, and maintenance records | This page, research queue |

## Page Types
| Type | Use when | Required template |
|---|---|---|
| Entity | The page centers on a named figure, spirit, deity, demon, archetype, or symbol-persona | [Entity template](../templates/ENTITY.md) |
| Text | The page centers on a book, manuscript, grimoire, corpus, edition, translation, or textual tradition | [Text template](../templates/TEXT.md) |
| Concept | The page centers on a Nana-Dex model, method, distinction, or reusable interpretive tool | [Concept template](../templates/CONCEPT.md) |
| Field note | The page begins in lived observation and separates event, cause, interpretation, and personal meaning | [Field note template](../templates/FIELD-NOTE.md) |
| Source record | The page records bibliographic/source data and what the source can and cannot support | [Source template](../templates/SOURCE.md) |
| Index | The page routes readers through a cluster | No heavy template; keep it navigational |

## Claim Ladder
Use the strongest label the page actually earns:

1. 🔴 Unsupported
2. 🟡 Hypothesis
3. 🟣 Personal definition/model
4. 🔵 Interpretation
5. 🟢 Attested

One page may contain multiple statuses. When that happens, label the section or claim directly.

## Cross-linking Rules
- Every entity page should link to related texts, source records, predecessor/successor forms, and open questions.
- Every text page should link to the entity pages it supports and the source records it depends on.
- Every field note should link to the core model it illustrates, not to a historical claim unless the historical claim is separately sourced.
- Every research scaffold should link to the research queue until its citation burden is resolved.

## Naming Rules
- Use stable, readable filenames in uppercase words separated by hyphens.
- Prefer one concept per page.
- Create disambiguation pages when one name carries multiple historical, literary, or personal meanings.
- Do not use a modern conclusion as the filename for an ancient figure unless the page is explicitly about reception history.

## Reality Veto
If the sources disagree with the model, the model changes. If the private story knows more than the public page can safely say, the public page remains incomplete rather than overexposed.
