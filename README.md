# Analyzing-SARS-CoV-2-Genome-Mutations
Analyzing SARS-CoV-2 Genome Mutations

## 🚀 Project Overview

In this project, we perform a **comparative genomic analysis** of SARS-CoV-2 sequences from different countries.  
We’ll download viral genomes, align them, identify mutations, and visualize the results — gaining practical experience in genome analysis and viral evolution tracking.

---

## ⚙️ Steps to Follow

### 1️⃣ Download the Data
- Visit [**NCBI Virus**](https://www.ncbi.nlm.nih.gov/labs/virus/) or [**GISAID**](https://www.gisaid.org/) (requires signup).
- Search for **SARS-CoV-2 complete genomes**.
- Download 2–3 genome sequences from different countries in **FASTA format**.

Example:
```bash
India.fasta [**Acessions**](https://www.ncbi.nlm.nih.gov/labs/virus/vssi/#/virus?SeqType_s=Nucleotide&VirusLineage_ss=Severe%20acute%20respiratory%20syndrome%20coronavirus%202,%20taxid:2697049&Country_s=India)
>PV361318.1 
>PP434597.1 
>OQ852607.1
Kenya.fasta
>OR619800.1
>OR099071.1
>OR099085.1
Germany.fasta
>OZ302279.1
>OZ302280.1
>OZ302281.1
