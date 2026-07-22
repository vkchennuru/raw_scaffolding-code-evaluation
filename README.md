# AI-Code-Judgment-CS1

## From Generation to Justification: Transforming Introductory Programming Education

This repository accompanies the research paper:

**From Generation to Justification: Transforming Introductory Programming Education**

## Overview

Large Language Models (LLMs) can generate syntactically correct programs, but correctness alone does not guarantee that the generated code is pedagogically suitable for novice programmers.

This project presents a reproducible experimental framework for evaluating AI-generated Python programs using:

- Functional correctness
- Halstead software metrics
- Abstract Syntax Tree (AST) analysis
- Cognitive Complexity
- Prompt scaffolding
- Statistical analysis
- Pedagogical suitability indicators

The repository contains datasets, prompts, generated programs, notebooks, evaluation scripts, figures, and an interactive analyzer supporting reproducible computing education research.

---

## Repository Structure

```
AI-Code-Judgment-CS1/

├── notebooks/
├── dataset/
├── prompts/
│   ├── raw/
│   └── scaffolded/
├── generated_code/
│   ├── raw/
│   └── scaffolded/
├── hidden_testcases/
├── results/
├── figures/
├── analyzer/
├── docs/
└── README.md
```

---

## Experimental Workflow

1. Create benchmark dataset
2. Generate Raw AI programs
3. Generate Scaffolded AI programs
4. Execute hidden test cases
5. Compute software metrics
6. Analyze AST structure
7. Measure Cognitive Complexity
8. Perform statistical analysis
9. Generate publication-quality figures
10. Evaluate pedagogical suitability

---

## Research Objectives

- Investigate whether AI-generated code requires human verification.
- Study the educational shift from code generation to code justification.
- Evaluate the impact of instructional prompt scaffolding.
- Provide a reproducible benchmark for computing education research.

---

## Technologies

- Python
- Google Colab
- Jupyter Notebook
- Pandas
- Matplotlib
- Radon
- AST
- GitHub Pages

---

## Reproducibility

All datasets, prompts, generated artifacts, analysis scripts, and figures are generated through reproducible Jupyter notebooks.

---

## Citation

If you use this repository, please cite the associated ACM COMPUTE publication (citation will be added after publication).

---

## License

This project is released under the MIT License.

---

## Authors

**Dr. C. V. Krishnaveni**

Department of Computer Science

SKR & SKR Government College for Women (Autonomous)

Kadapa, Andhra Pradesh, India
