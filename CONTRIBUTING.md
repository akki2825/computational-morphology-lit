# Contributing

Thank you for your interest in contributing to this curated collection of computational morphology literature!

## How to Add a Paper

1. **Fork** this repository
2. **Create a paper folder** following this path convention:
   ```
   conference-publications/YYYY/publications_confYY/papername_confYY/README.md
   ```
   - `YYYY` = publication year (e.g., `2023`)
   - `conf` = venue abbreviation in lowercase (e.g., `acl`, `emnlp`, `sigmorphon`)
   - `YY` = two-digit year (e.g., `23`)
   - `papername` = short identifier for the paper (e.g., `hardattn`, `morfessor`)

3. **Paper README format** — each paper's `README.md` should contain:
   ```markdown
   # Paper Title

   link: [URL to paper]

   authors: Author One, Author Two, Author Three

   ```
   @inproceedings{bibtex_key,
   title = {Paper Title},
   author = {Last, First and Last, First},
   booktitle = {Proceedings of ...},
   year = {2023}
   }
   ```
   ```

4. **Update the index** — add the paper to `conference-publications/README.md` under the appropriate conference and year section.

5. **Submit a pull request** with a clear description.

## Guidelines

- Only include peer-reviewed publications (conferences, workshops, journals) or widely-cited preprints
- Ensure BibTeX entries are accurate (check against ACL Anthology, DBLP, or Semantic Scholar)
- Papers should be relevant to computational morphology or closely related topics
- Use the existing folder naming conventions consistently

## Scope

This collection covers:
- Morphological inflection and generation
- Morphological segmentation
- Morphological analysis and tagging
- Paradigm completion and learning
- Lemmatization
- Morphological typology
- Low-resource and cross-lingual morphology
- Subword tokenization (as it relates to morphology)
- Character-level models for morphological processing
- Computational phonology
- Finite-state morphology
- Surveys, books, and shared task descriptions

## Questions?

Open an issue if you have questions about whether a paper fits the scope or need help with formatting.
