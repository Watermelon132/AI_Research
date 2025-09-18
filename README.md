# AI_Research

#  Repository Overview  

This repository is organised to support the full workflow of a research project, from proposal to final submission.  

- **`Data_analysis/`** – Contains raw and additional datasets (`.csv`), survey materials, Python analysis scripts, and output visualisations.  
- **`Figures/`** – Stores figures and images used in presentations or papers.  
- **`Interview_documents/`** – Holds interview transcripts and related documentation.  
- **`Proposal/`** – Includes the project proposal draft and final version.  
- **`Research_papers/`** – Reference materials, background readings, and related academic papers.  
- **`Submitted_paper/`** – The final paper and submitted versions.  
- **`README.md`** – Entry point describing the project, its goals, and instructions.  

This structure keeps **data, analysis, supporting documents, and outputs clearly separated** for easier navigation and version tracking.  

---

# Collaboration Guidelines  

To ensure smooth collaboration, contributors should follow these practices:  

## 1. File Naming & Version Control  
- Use **clear, consistent names** with dates (`YYYYMMDD`), project name, and version numbers (e.g., `ProjectA_data_v1.csv`).  
- Avoid spaces in filenames; use underscores (`_`) instead.  
- Increment versions logically (`v1`, `v2`, …) instead of overwriting files.  

## 2. Branching & Git Workflow  
- Create a **feature branch** for changes (e.g., `feature/data-cleaning` or `fix/typo-proposal`).  
- Submit changes via **Pull Requests (PRs)** for review before merging into `main`.  
- Use **descriptive commit messages** (e.g., `Add graph of survey results` instead of `update`).  

## 3. Data Handling  
- Keep sensitive or identifiable data (e.g., interviews) secure and only share with authorized collaborators.  
- Place all analysis code in `Data_analysis/` and ensure scripts are **well-documented** with comments.  

## 4. Documentation  
- Update the `README.md` when major changes occur.  
- Add notes in `Proposal/` or `Submitted_paper/` folders when a draft has been superseded.  
- Use `Figures/` for finalized graphics, not raw plots or duplicates.  

## 5. Collaboration Etiquette  
- Discuss large structural changes before making them.  
- Review and comment on Pull Requests promptly.  
- Respect version history and avoid force-pushing unless absolutely necessary.  

---

Folder structure:
├── Data_analysis
│   ├── 20160104_ProjectA_additional_data_v1.csv
│   ├── 20160104_ProjectA_addtional_data2_v1.csv
│   ├── 20160104_ProjectA_data_v1.csv
│   ├── 20160104_ProjectA_survey_questions.docx
│   ├── Data_analysis_v1.py
│   └── Graphed_data.png
├── Figures
│   ├── An overview of the topics covered in our usability study of Al programming assistants.png
│   └── Main Fields in GAI Guidelines.png
├── Interview_documents
│   ├── 20160104_ProjectA_Interview_Eric_v1.docx
│   ├── 20160104_ProjectA_Interview_final_3.docx
│   └── 20160104_ProjectA_Interview_Jason_v1.docx.docx
├── Proposal
│   ├── Final_proposal.docx
│   └── Proposal_draft_v1.docx
├── README.md
├── Research_papers
│   ├── Academic_NonFiction.pdf
│   ├── An_inquiry_into_GenAI.pdf
│   └── Generative_AI tools.pdf
└── Submitted_paper
    ├── Final_paper_v1.docx
    └── Final_paper_v2_submitted_version.pd
