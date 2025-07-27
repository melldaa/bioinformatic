# 🧬 Bioinformatics: Pairwise Sequence Alignment using GenBank

This project demonstrates the process of retrieving nucleotide sequences from NCBI GenBank and performing **pairwise alignment** to compare genetic similarities between species using R.

## 📌 Project Summary

- The goal of this analysis is to evaluate genetic similarities and differences across selected species.
- The sequences are retrieved using their accession numbers from GenBank.
- Pairwise alignments are performed using both **local** and **global** alignment methods.
- The alignment scores are interpreted to assess which species are genetically closest to *Homo sapiens*.

## 🧪 Tools & Libraries

This project is written in **R Markdown (.Rmd)** using the following packages:

- `ape`: for accessing GenBank
- `Biostrings`: for pairwise sequence alignment
- `knitr`: for generating report documents

## 🧬 Species Analyzed

The following species and GenBank accession numbers were used:
- **Homo sapiens** – `NM_003381.4`
- **Pongo abelii** – `XM_024248829.1`
- **Equus caballus** – `XM_023633005.1`
- **Lutra lutra** – `XM_047733983.1`
- **Cavia porcellus** – `XM_005003122.3`

## 📈 Results

- Highest similarity: **Homo sapiens** vs. **Pongo abelii**
- Lowest similarity: **Homo sapiens** vs. **Cavia porcellus**

This makes sense evolutionarily since primates are closely related to humans.

## 📂 Files

- `bioinformatics_alignment.Rmd`: The main R Markdown file with code and visual output
- (Optional) `outputs/`: Folder to store plots, alignment results, or tables

## 👩‍💻 About Me

Hi! I'm **Melda**, a statistics graduate passionate about data science. You can view more of my work here on [GitHub](https://github.com/melldaa).

## 📬 Contact

Feel free to reach out if you'd like to collaborate or ask questions!

---
