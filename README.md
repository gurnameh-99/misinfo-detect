# Multitask Learning for Authenticity and Authorship Detection

Welcome to the **misinfo-detect** repository, containing **code** and a **subset** of the dataset supporting our research on **joint detection of fake news (authenticity) and AI-generated text (authorship)**. Our work introduces novel architectures—such as the Shared-Private Synergy Model (SPSM)—that simultaneously improve classification accuracy and interpretability across both tasks.

---

## Project Overview

1. **Research Focus**  
   - **Authenticity Detection**: Distinguishing whether an article is *fake* or *real*.  
   - **Authorship Detection**: Identifying if the text was authored by a *human* or by *AI*.  
   - **Multitask Synergy**: Exploiting shared and private layers to robustly tackle both classification objectives within a single framework.

2. **Repository Contents**  
   - **`code/`**: Source files, Python scripts, and Jupyter notebooks demonstrating data preprocessing, model training (transformers, stylometric features, etc.), and evaluation.  
   - **`data_subset/`**: A partial release of our dual-labeled dataset, including labels for both authenticity (*fake* vs. *real*) and authorship (*AI* vs. *human*).  
   - **Documentation**: Guidance on usage, references, and supporting materials to help you reproduce our experiments on this subset.

3. **Publication Status**  
   - This work is currently under review in the journal *Electronics* for the Special Issue on *Big Data Analytics and Information Technology for Smart Cities and Citizen Wellbeing*.  
   - **Full Release Coming Soon**: Once peer review is complete, we will provide the **entire dataset** and **full codebase**, including training scripts, model checkpoints, and further analyses.

---

## Getting Started

1. **Clone or Download**
   ```bash
   git clone https://github.com/your-username/misinfo-detect.git
   cd misinfo-detect
   ```
2. **Install Dependencies**
   - Ensure you have Python (>= 3.7) installed.  
   - Install required packages:
     ```bash
     pip install -r requirements.txt
     ```
3. **Data Subset**
   - Located in `data_subset/`.  
   - Each sample contains:
     - Article text.  
     - Labels for authenticity (`fake` or `real`) and authorship (`human` or `AI`).  
   - The **complete dataset** will be released once the paper is accepted.

4. **Running the Code**
   - Check out the notebooks/scripts in `code/` for an end-to-end pipeline of data loading, preprocessing, and model training.  
   - Detailed usage instructions and example runs are provided within the respective files.

---

## How to Cite

If you find this repository helpful, please cite our forthcoming publication when it becomes available. We will update this section with a formal citation and DOI upon acceptance.

For now, you can reference:

> **Multitask Learning for Authenticity and Authorship Detection**  
> Gurunameh Singh Chhatwal, Jiashu Zhao, (Under Review in *Electronics*)

---

## Contact

- **Corresponding Author**: [Name]  
- **Email**: [Email Address]

Feel free to open an issue or reach out with any questions, suggestions, or collaboration ideas.

---

## License

This repository is provided for non-commercial, academic, and research purposes. Please see the `LICENSE` file for complete details.

---

**Note**:  
We appreciate your patience during the review process. The **complete dataset** and **full code** for all experiments will be made publicly available once the manuscript is published.
```