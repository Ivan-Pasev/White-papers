# Publication Constitution — GILC White Papers

Version 0.1 · 2026-11-11

## Scope
The public repository `Ivan-Pasev/White-papers` is a **release and citation surface**. Research notes, unreviewed proof claims, preliminary preprints and internal agent instructions remain in the canonical Google Drive foundry. A release can be journal-grade without having received external peer review; its actual review status must be stated unambiguously.

## Non-negotiable gates
1. **Provenance:** original inputs preserved, source and version identifiers resolved, author/affiliation acknowledged, permissions clear.
2. **Scientific claim map:** every theorem, calculation, observation, design hypothesis and forward-looking claim clearly classified; unstated assumptions and exaggerated conclusions rejected.
3. **Literature and novelty:** closest peer-reviewed comparators consulted; DOI, title, authors, year and specific cited claim verified.
4. **Mathematics:** formal definitions, domain and codomain, assumptions, correct proof or bounded unproved conjecture; no fake proof-assistant or numerical PASS.
5. **Empiricism:** methods, equipment/data, uncertainty and negative controls where empirical assertions are made. Pure theory is not penalized for lacking experiments but cannot assert measured physical effects.
6. **Reproducibility:** necessary code, data, tests, version lock and honestly reported execution receipts, or an explicit reason why not applicable/available.
7. **Figures:** editable source where possible; axes, dimensions, data sources, legends, scale and figure class (schematic/simulation/experiment/generated).
8. **Editorial integrity:** clear abstract, contribution, limitations, natural academic style, current venue-specific guidance, accurate author/funding/COI and AI-assistance declarations.
9. **Review:** an adversarial internal assessment and an external reviewer/venue status stated separately. **No self-awarded peer-review designation.**
10. **Approval:** explicit author sign-off and frozen version manifest before pushing a paper into the repository or publishing to Zenodo.

## Release states
`SOURCE_LOCKED` → `PREPRINT_WORKING` → `PREPRINT_READY` → `JOURNAL_WORKING` → `JOURNAL_READY` → `AUTHOR_APPROVED` → `PUBLIC_RELEASE`.

Independent external peer-review statuses are `NOT_SUBMITTED`, `SUBMITTED`, `UNDER_REVIEW`, `ACCEPTED`, `PUBLISHED`, or `UNKNOWN`. Do not infer them from the internal release state.

## GitHub admission
Only approved journal-grade, version-frozen manuscripts and their evidence packages may enter `papers/<year>/<slug>/`. README, policy, contributor instructions and catalogue infrastructure are excepted. No manuscript is automatically transferred when a Drive file changes. If Zenodo is used, link the exact version DOI and concept DOI as distinct objects.

## Security and copyright
Do not publish private Google Drive content without approval. Do not assume an open-source software license applies to research manuscript text. Scientific images and external skills require source-specific licensing/attribution. External skills are not automatically trusted or executable by virtue of appearing in a registry.

## Quality does not imply validation
Publication formatting is necessary but not sufficient. A logically invalid theory remains invalid even when beautifully typeset. An external DOI identifies a deposit; it is not proof of scientific correctness.

Canonical foundry: https://drive.google.com/drive/folders/1sxk0m2RhUNkyqq2HLQW9q8uJa0LeAPAK
