# Indo-European Cognates: British Isles and India

## Project Purpose

This repository serves as a structured, version-controlled dataset for comparative etymological research between languages of the British Isles (specifically Old Irish) and classical languages of India (specifically Sanskrit). The goal is to document well-established cognate pairs, track the research process, and facilitate scholarly discussion on Indo-European language relationships.

## Methodology

1. **Data Structure**: Each cognate pair is recorded in a CSV file (`cognates.csv`) with the following columns:
   - `Old_Irish_Term`: The Old Irish word (with appropriate diacritics).
   - `Sanskrit_Term`: The corresponding Sanskrit word (in IAST transliteration).
   - `Proto_Indo-European_Root`: The reconstructed PIE root according to mainstream Indo-European linguistics.
   - `Meaning`: A brief English gloss of the shared semantic core.
   - `Notes`: Optional field for phonological observations, semantic shifts, or references.

2. **Research Workflow**:
   - Potential cognate sets are proposed as GitHub Issues with the label `research-needed`.
   - Each Issue is investigated using authoritative sources (e.g., Pokorny, Mayrhofer, MacBain).
   - After verification, the data is added to `cognates.csv` on a feature branch.
   - A Pull Request merges the branch, closing the corresponding Issue(s).

3. **Transparency & Auditability**:
   - All changes are tracked via Git commits.
   - Discussion and peer review take place in Pull Request comments.
   - The Issue tracker documents open questions and research tasks.

## Languages Compared

- **Old Irish** (Goídelc): The earliest attested Goidelic language, spoken in Ireland from roughly the 6th to the 10th centuries CE.
- **Sanskrit**: The classical language of ancient India, a primary source for reconstructing Proto-Indo-European.

Both languages belong to the Indo‑European language family, but to different branches (Celtic and Indo‑Iranian). Systematic comparison of their vocabularies helps elucidate the phonological and morphological developments from the common ancestor.

## Getting Started

1. Browse the `cognates.csv` file for the current dataset.
2. Check the **Issues** tab for proposed cognates awaiting research.
3. To contribute, fork the repository, create a new branch, and open a Pull Request with your additions or corrections.

## References

- Pokorny, Julius. *Indogermanisches etymologisches Wörterbuch*.
- Mayrhofer, Manfred. *Etymologisches Wörterbuch des Altindoarischen*.
- MacBain, Alexander. *An Etymological Dictionary of the Gaelic Language*.
- Matasović, Ranko. *Etymological Dictionary of Proto‑Celtic*.