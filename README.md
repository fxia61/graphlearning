# Graph Learning research website

This is a static HTML prototype generated from the supplied Overleaf source. Open `index.html` in a browser, or serve with `python -m http.server 8000` for search. Upload the contents of this folder to GitHub Pages or Cloudflare Pages.

## Conversion limitations
Pandoc conversion is best-effort. Specialized LaTeX commands, labels, citations, algorithms, and complex tables require manual review. Search indexes chapters rather than individual paragraphs. References are a browsable BibTeX-derived index and citations are not yet fully linked. MathJax loads from CDN. The original Overleaf ZIP remains the authoritative manuscript.


## Version 2: table restoration
Three LaTeX table environments have been restored as responsive HTML tables: one in Chapter 1 and two in Chapter 4. Check complex multirow formatting and citation rendering before publication.

## Figure numbering (v3)
Figures are numbered by chapter (Figure 1.1, 2.1, etc.). Original LaTeX figure labels are retained as HTML anchors, and figure cross-reference links are updated across chapters.


## Version 4: linked citations

In-text citation placeholders were replaced with numeric links, numbered by first occurrence across the nine chapters. Bibliography entries are ordered by first citation; uncited entries follow. Hover over a number for the source title. This is a website-level citation numbering scheme and may differ from the journal PDF style. 0 cited keys were not found in the prior website bibliography; these are explicitly marked as unresolved in the reference list.

## Version 5 additions

- Chapter-based table numbers and equation numbers.
- Table citation keys converted to numbered, linked references using the Version 4 bibliography mapping.
- Equation and table label links updated where source labels were preserved.
- Equation numbering follows HTML display-math blocks; check alignment with the original PDF, particularly unnumbered LaTeX display math.

## Version 6 — IEEE-style references
Bibliography is formatted from the source BibTeX data in IEEE-style order (author, title, venue, volume/issue/pages, year, DOI/URL). Existing citation numbering and anchors are retained. Review unusual BibTeX entries for complete metadata and strict IEEE editorial compliance.

## Version 7

The References page now displays only entries [1]–[489]; entries [490]–[582] were removed. Existing in-text citation numbers and links were left unchanged.
