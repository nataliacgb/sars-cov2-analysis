# 🧬 Genomic and Structural Analysis of SARS-CoV-2

## 📌 Overview

This project explores publicly available data from NCBI and the Protein Data Bank (PDB)
to investigate two fundamental aspects of the virus responsible for COVID-19: its genome
organization and the three-dimensional structure of the Spike protein.

The analysis is interpretative, based on public data and peer-reviewed literature.

---

## 🎯 Objectives

- Analyze the complete viral genome (NC_045512.2)
- Identify and interpret key genes (ORF1ab, Spike)
- Explore the 3D structure of the Spike protein (PDB: 6XRA)
- Understand the relationship between protein structure and host cell infection

---

## 🗄️ Databases

| Database | Description | Accession |
|----------|-------------|-----------|
| NCBI | Global repository of biological sequences, genomes, and scientific literature | NC_045512.2 |
| Protein Data Bank (PDB) | Repository of 3D structures of biological macromolecules | 6XRA |

---

## 🧪 Methods

**Genomic analysis** was based on accession NC_045512.2 — the reference genome of the
Wuhan-Hu-1 isolate, sequenced by NGS (Illumina platform) and assembled using the Megahit
algorithm (v1.1.3). The genome consists of ~29,900 base pairs of positive-sense
single-stranded RNA.

Key genes identified and interpreted:
- **ORF1ab** — encodes non-structural proteins essential for viral replication
- **Spike gene** — encodes the protein responsible for host cell entry

**Structural analysis** was conducted using the 6XRA structure (PDB), focusing on:
- Trimeric organization of the protein
- Receptor Binding Domain (RBD) and its interaction with ACE2
- Glycan distribution on the protein surface (glycan shield)
- Conformational changes associated with membrane fusion

---

## 🔬 Key Findings

- The Spike protein exhibits a **trimeric structure** essential for viral function
- A **glycan shield** on the surface contributes to immune evasion
- The **RBD** directly binds to ACE2 receptors on human cells, initiating infection
- Structural conformation directly influences viral entry into host cells

---

## 💉 Why Is the Spike Protein an Ideal Vaccine Target?

The Spike protein is the structure the virus uses to recognize and bind to the ACE2
receptor on human cells — without this step, infection cannot occur. This makes it a
strategic target: by inducing the immune system to produce antibodies against Spike,
it is possible to block infection before the virus enters the cell.

Additionally, Spike is a surface-exposed protein, meaning it is accessible to the
immune system — unlike internal viral proteins, which would only be recognized after
infection is already established. Its relatively conserved structure across variants
also makes it relevant for broad-spectrum vaccine development.

---

## 🧬 Biological Insights

- The ORF1ab gene is associated with viral replication mechanisms
- The Spike protein is a major therapeutic and vaccine target
- Structural features of Spike explain its high infectivity and immune interaction

---

## 💡 Scientific Relevance

- Vaccine and antibody development targeting the Spike protein
- Identification of antiviral targets
- Support for structure-based drug design
- Understanding viral mechanisms in the context of public health emergencies

---

## 🧠 Skills Demonstrated

- Genomic data interpretation (NCBI)
- Structural biology analysis (PDB)
- Scientific writing and biological data interpretation
- Use of public biological databases

## 📂 Project Structure
```
sars-cov2-analysis/
│
├── README.md
├── report.pdf
├── report.docx
└── figures/
    └── figure1.png
```

## 🖼️ Visualization
![Spike Protein Structure](figures/figure1.png)

## 📚 References

- WALLS, A. C. et al. Structure, function, and antigenicity of the SARS-CoV-2 spike
  glycoprotein. *Cell*, v. 181, n. 2, p. 281–292, 2020.
- WU, F. et al. A new coronavirus associated with human respiratory disease in China.
  *Nature*, v. 579, p. 265–269, 2020.
- HOFFMANN, M. et al. SARS-CoV-2 cell entry depends on ACE2 and TMPRSS2.
  *Cell*, v. 181, p. 271–280, 2020.
- NCBI. SARS-CoV-2 isolate Wuhan-Hu-1, complete genome. NC_045512.2.
  https://www.ncbi.nlm.nih.gov/nuccore/NC_045512.2
- PDB. Structure of SARS-CoV-2 spike glycoprotein (6XRA).
  https://www.rcsb.org/structure/6XRA

---

## 👩‍🔬 Author

**Natália Canholato Gomes**
Postgraduate in Bioinformatics — Unyleya
