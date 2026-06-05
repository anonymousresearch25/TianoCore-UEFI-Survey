# Survey on Security Practices in the TianoCore/UEFI Ecosystem — EDA Notebooks

This repository contains the Jupyter notebooks used for the exploratory
data analysis (EDA) of a survey study on security practices and preferences
within the TianoCore open-source community and the UEFI ecosystem.

The survey was conducted between **March 8–25, 2026** and yielded
**13 valid responses** after preprocessing.

---

## Repository Structure

| Notebook | Section | Topics Covered |
|---|---|---|
| `eda_01_demographics.ipynb` | Demographics | Sex/gender, age group, country, highest degree |
| `eda_02_project_info.ipynb` | Project Information | Ecosystem role, project focus, team size, experience, codebase size, project stage |
| `eda_03_bug_management.ipynb` | Bug Management | Issue tracking, bug prioritisation, triage, upstreaming conditions and methods, lifecycle maturity |
| `eda_04_patch_management.ipynb` | Patch Management | Patch propagation, semantic patching, upstream submission frequency |
| `eda_05_testing_analysis.ipynb` | Verification & Validation | Formal verification, static analysis, CodeQL, dynamic analysis, Intel HBFA |
| `eda_06_security.ipynb` | Firmware Security | Security bug priority rankings, bug bounty programmes, security effort, TianoCore posture |
| `eda_07_memory_safety.ipynb` | Memory Safety & Rust | Barriers to adoption, interest in Rust for EDK II, in-house Rust components |
| `eda_08_devops.ipynb` | DevOps / DevSecOps | CI/CD pipeline adoption, DevSecOps knowledge |
| `eda_09_supply_chain.ipynb` | Supply Chain | Verification methods, challenges in supply-chain visibility |
| `eda_10_impact.ipynb` | Organisational Impact & Barriers | Vulnerability impact types, adoption barriers, support needs, person-hours |

---

## How to Run

These notebooks are designed to run in **Google Colab**.

### Prerequisites

1. Mount your Google Drive and place the cleaned survey CSV at:
   ```
   /content/drive/MyDrive/TS-Survey/tianocore-survey_cleaned.csv
   ```

2. Figures will be saved to:
   ```
   /content/drive/MyDrive/TS-Survey/figures/
   ```

### Steps

1. Upload a notebook to [Google Colab](https://colab.research.google.com)
2. Run **Step 1** — Mount Google Drive
3. Run **Step 2** — Install dependencies (`matplotlib`, `pandas`)
4. Run **Step 3** — Load data and helpers
5. Run the remaining cells for each question

---

## Data

The survey data is available on Dataverse.

---

## Paper

These notebooks support a paper currently under review.
Details will be added upon publication.
