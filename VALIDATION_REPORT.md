# Fihirana 2024 — Extraction & Validation Report

- Source: `Fihirana 2024.pdf`
- Total hymns detected: **295**
- Expected range: **1–295**
- Missing numbers: **[]**
- Duplicated numbers: **[]**
- Hymns with empty lyrics: **[]**
- Extraction warnings: **['Hymn 8: possible FIDERANA header remains', 'Hymn 30: possible FIDERANA header remains', 'Hymn 94: possible FIDERANA header remains', 'Hymn 121: possible FIDERANA header remains', 'Hymn 145: possible FIDERANA header remains', 'Hymn 155: possible FIDERANA header remains', 'Hymn 257: possible FIDERANA header remains', 'Hymn 262: possible FIDERANA header remains', 'Hymn 286: possible FIDERANA header remains']**

## Cleaning rules
- Standalone PDF page numbers were removed from hymn bodies.
- Repeated `FIDERANA` page headers were removed when clearly identified as page headers.
- Legitimate repetitions such as `(2X)`, `REF`, `Réf`, `Bis`, etc. were retained.
- Typographic ligatures `ﬁ`/`ﬂ` were normalized to `fi`/`fl` so search works reliably.
- No internet or external hymn source was used.
