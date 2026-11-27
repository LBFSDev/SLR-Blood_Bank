# How each part of the SLR paper was written

**Title and research questions.** These are copied word for word from `Paper/info.txt`.

**Abstract.** This was written last, as a structured summary of the finished sections. Every number in it comes from the PRISMA workbook or from the paper–dimension mapping Excel.

**1. Introduction.** The paper opens with documented crisis facts taken from the included studies: drive cancellations in the US (S24) and Canada (S35), the Ukraine wartime figures (S22) and the earthquake logistics (S37). It then explains why centralised systems are fragile and introduces regional blood-group data as the link between decentralisation and data-driven methods. The section ends with the RQs, the contributions and a guide to the paper's structure.

**2. Background.** This section is built from the included studies and two verifiable external sources: WHO guidance (2023) and the Ripoll-Gallardo et al. meta-analysis (2024). I found both in the reference lists of S19. The section defines "decentralised" and "innovative" as they are used in the review.

**3. Methodology.**
- The search keywords and eligibility criteria come from `Paper/info.txt`.
- The PRISMA numbers come from `PRISMA/PRISMA_Screening_Results_Blood_Supply.xlsx`: 97 identified, 3 duplicates, 94 screened, 43 excluded, 51 assessed, 7 excluded, 44 eligible.
- I compared the 44 eligible titles with the 41 papers in `included_papers`. Four eligible studies are missing from the final set (record IDs 32, 49, 74 and 77). One paper, the GIS study (S26), is in the final set but not in the screening file.
- The taxonomy method comes from `info.txt` (deductive ISBT frameworks, then inductive extraction), `Dimensions/Dimensions.txt` (12 initial dimensions plus 7 from the pilot papers) and `Final_Taxonomy/final_taxonomy.txt` (34 dimensions in 8 categories). The taxonomy figure is your existing tree image.

**4. Results.** These are the frequency, co-occurrence, publication and methodology analyses from the Steps 5–7 synthesis. They are recomputed from `Final_Taxonomy/Systematic_Review_filled.xlsx`.

**5. Findings by RQ.** Each RQ answer is a narrative synthesis. It uses the analytic codes from the Steps 5–7 work: strategy families (renamed M1–M9 in the paper, so they don't clash with the study IDs), blood-group data use (BG1–BG5) and challenge themes. Every factual claim is cited to the study it came from, and I checked the quoted figures against the PDFs.

**6. Discussion.** This section covers the principal findings, a proposed layered framework (a new figure), the seven gap types, implications for practice and research, and limitations. The framework is presented as a hypothesis for future testing, not as a validated result.

**7. Conclusion.** A short wrap-up of the answers and the main gap.

**References.** The included studies are cited S1–S41, matching paper1–41 in your mapping. I took author names, years, venues and DOIs from the PDFs' first pages and your Excel. Where the author order was unclear in the PDF, I used "et al.". The methodological references (PRISMA 2020, Kitchenham, Nickerson et al.) are standard citations.

**Style.** The paper is written in continuous academic prose, with tables and figures where they carry the evidence.

**Placeholders.** Text highlighted in yellow in the Word file marks details that are not in the folder and that you must fill in:
- author details
- database names and search strings
- why the 4 studies were dropped and where S26 came from
- the ISBT documents used
- the declarations

## Revision: two-column version (`SLR_Paper_Decentralized_Blood_Mobilization_2col`)

- **Layout.** The title and abstract run across the full page width. The body text is set in two columns. Wide figures and all tables span both columns, and the appendix is single-column.
- **Citations.** Study codes are gone. Every included study is cited by a shortened title and its year, for example (*Blood Bond*, 2025). The full titles appear in Appendix A and in an alphabetical reference list. Methodological sources are cited by author and year.
- **Tables.** The tables were restyled: navy header row, horizontal rules only, light row banding, and the header row repeats on each page. Rows no longer split across pages. Study lists show one title per line. Where a list was long (the evaluation-level and challenges tables), each row shows up to three titles plus "+ N more"; the full lists are in Appendix A and the supplementary Excel.
- **Figures.** The smaller charts were redrawn at column width. The blood-group chart and the framework figure no longer show study codes.

## Revision: condensed 10-page version (`SLR_Paper_Decentralized_Blood_Mobilization_10pp`)

- **Length.** The paper is now 10 A4 pages including all figures, tables and references, down from 23. The text went from about 13,000 to about 7,800 words (references included). Every RQ answer, the synthesis results, the seven gap types, the framework, the implications and the limitations are kept.
- **Register.** Informal phrasing was replaced with formal academic wording. Each claim cites one to three studies, and longer study lists were moved into the tables.
- **Layout.** The abstract is a structured, boxed abstract. The paper has a running header and page numbers, a 9.5 pt two-column body and an 8 pt reference list.
- **Tables (5).** Eligibility criteria (in a single column). The taxonomy merged with the dimension frequencies. The strategy families with their core mechanisms and representative studies. The challenges merged with illustrative evidence. The research gaps. The integration checks, evaluation levels and region counts are now given in the text.
- **Figures (6).** All were redrawn at a compact size: the PRISMA flow, the publication overview (year and design), the category co-occurrence, the strategy-by-crisis map, the blood-group data use and the framework. The taxonomy tree and Appendix A were dropped for space; the full study-level coding remains in the supplementary Excel.
- **Placeholders.** These are unchanged and still highlighted in yellow: authors, databases and search strings, the 44-to-41 reconciliation, the ISBT documents and the declarations.
