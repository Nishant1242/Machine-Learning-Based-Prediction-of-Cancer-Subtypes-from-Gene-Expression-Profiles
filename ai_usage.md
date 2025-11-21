# AI Usage Documentation

This document describes how AI tools were used during the development of the project  
**“Machine Learning–Based Prediction of Cancer Subtypes from Gene Expression Profiles.”**

---

## 1. AI Tools Used

- **Tool:** ChatGPT (large language model)
- **Context of Use:**  
  - Idea refinement and project scoping  
  - Drafting proposal and report text  
  - Suggesting code structure and function outlines  
  - Clarifying bioinformatics concepts (e.g., PCA on gene expression data)

No external proprietary AI APIs were called directly from the project code.  
All AI interaction occurred outside the runtime environment (e.g., in a chat interface).

---

## 2. Tasks Where AI Assisted

AI assistance was used in the following areas:

1. **Project Planning & Wording**
   - Drafted and refined the project proposal text.
   - Helped structure the draft report sections to match course guidelines.
   - Suggested possible phrasing for research questions, objectives, and methods.

2. **Code Scaffolding**
   - Suggested a high-level Python project structure (folders such as `data/`, `src/`, `notebooks/`).
   - Provided example code snippets for:
     - Loading and merging Kaggle CSV files
     - Transposing expression matrices to “samples × genes”
     - Performing PCA and plotting results
     - Training a baseline Logistic Regression model
   - These snippets were **reviewed, edited, and integrated manually** by the team.

3. **Documentation Support**
   - Generated initial outlines for `README.md` and this `ai_usage.md` file.
   - Suggested commit message styles and reproducibility practices.

---

## 3. Verification and Human Oversight

All AI-generated suggestions were treated as drafts, not final outputs.  
Specifically:

- Code snippets were:
  - Manually inspected for correctness and readability.
  - Tested in the project environment.
  - Modified to match the actual dataset structure and file paths.

- Text (proposal, report drafts, README) was:
  - Edited to ensure accuracy with respect to the dataset and methods actually used.
  - Adjusted for clarity, concision, and alignment with course requirements.

The final decisions about model choice, preprocessing steps, and interpretation of results were made by the project team.

---

## 4. What AI Was *Not* Used For

AI tools were **not** used for:

- Fabricating or simulating data.
- Running any experiments or training models directly.
- Automatic grading, evaluation, or result generation.
- Accessing any private or sensitive information.

All computations and evaluations were performed locally by team members using Python and scikit-learn.

---

## 5. Ethical and Academic Integrity Considerations

- AI tools were used as **assistive tools**, similar to online documentation or coding examples.
- The team ensured that:
  - All analysis is replicable via the provided code and data.
  - AI-generated text does not misrepresent the work performed.
  - Citations to original datasets and publications (e.g., Golub et al. 1999) are included.

If required by the course, this document may be submitted alongside the report to provide transparency about AI involvement.
