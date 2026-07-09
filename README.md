# Mimo Evidence Log

Public evidence registry for mimoaitools.com - an AI-tools review site where every claim traces to a dated, publicly linkable source. The reader-facing protocol summary lives at mimoaitools.com/methodology.

Commit history is the timestamp: entries are committed when captured, so git history independently proves when each piece of evidence was collected.

## Layout

registry/registry-PAGE.json - evidence entries per reviewed page: claim, source URL, source date, verbatim quote (max 60 words), platform, capture date, screening status with exclusion reason codes, dual-coder labels.

Every entry has an EV id - the same codes cited inline in Mimo articles. Open the record, read the quote, click the source, check the dates.

## Ground rules (Mimo Evidence Protocol v1.0)

- Sources must be dated, publicly linkable, and re-fetched live on capture day.
- - Anecdotes stay anecdotes: community reports are never converted into percentages; counts always carry their denominator and date window.
  - - Vendor materials are always labeled as the vendor speaking about itself.
    - - Corrections are public: superseded entries stay in the log with a dated note.
     
      - ## Disclosure
     
      - Mimo earns affiliate commissions on some outbound links; ratings are evidence-derived and commission-independent (mimoaitools.com/affiliate-disclosure). The founder's own products and their categories are excluded from coverage entirely (mimoaitools.com/about).
