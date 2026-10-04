# IEAP – Python Series 03 | Group Assignment

**Université de Montpellier**  
**Master 1 – Ingénierie et Ergonomie de l'Activité Physique (IEAP)**  
**2026–2027**

## Overview

This repository contains the group assignment for **Python Series 03**, focusing on signal processing, remarkable-point detection, signal generation, noise analysis, and filtering using Python.

The project also introduces collaborative development using **Git and GitHub**, with individual branches, pull requests, code integration, and a shared final report created using **Quarto**.

## Project Content

The assignment is organized into five sections:

### 1. Group organization and GitHub workflow
- Organization of group contributions.
- Branch management and pull requests.
- Collaborative development and code integration.

### 2. Remarkable-point detection
- Detection of positive and negative zero crossings.
- Understanding and improving existing code.
- Detection of local maxima and minima.
- Creation of reusable detection and plotting functions.

### 3. Signal generation and analysis
- Generation of sinusoidal signals.
- Identification and visualization of remarkable points.
- Estimation of signal period and frequency.

### 4. Noise analysis and filtering
- Addition of normally distributed random noise.
- Analysis of noise effects on remarkable-point detection.
- Application of a Butterworth low-pass filter.
- Comparison of original, noisy, and filtered signals.
- Evaluation of frequency estimation after filtering.

### 5. Critical points and problem solving
- Management of generated HTML files.
- Reuse of functions and libraries across sections.
- Resolution of GitHub branch and pull request issues.

## Repository Structure

The project uses a main Quarto document that combines the individual sections into a single report.

```text
IEAP-Python-Series03-Group/
│
├── IEAP-Python-Series03-Group.qmd
├── sections/
│   ├── 01_groups.qmd
│   ├── 02_1_zero_crossings.qmd
│   ├── 02_2_explain_improve_code.qmd
│   ├── 02_3_local_maxima_minima.qmd
│   ├── 03_1_create_signal.qmd
│   ├── 03_2_remarkable_points.qmd
│   ├── 03_3_signal_frequency.qmd
│   ├── 04_1_noisy_signal.qmd
│   ├── 04_2_noisy_remarkable_points.qmd
│   ├── 04_3_low_pass_filter.qmd
│   └── 05_critical_point.qmd
│
├── .gitignore
└── README.md
```

## Tools and Libraries

- **Python** – Signal processing and numerical calculations.
- **NumPy** – Array operations and numerical analysis.
- **Matplotlib** – Signal visualization.
- **SciPy** – Butterworth filtering.
- **Quarto / Jupyter** – Report generation and Python execution.
- **Git and GitHub** – Version control and collaboration.

## Running the Report

### 1. Clone the repository

```bash
git clone https://github.com/jenniferhoumard/IEAP-Python-Series03-Group.git
cd IEAP-Python-Series03-Group
```

### 2. Set up the environment

Install Python, Quarto, and the required Python packages:

```bash
python -m pip install numpy matplotlib scipy jupyter ipykernel
```

Quarto must also be installed separately.

### 3. Render the report

From the repository's root directory, run:

```bash
quarto render IEAP-Python-Series03-Group.qmd
```

This generates the complete HTML report.

**Note:** The individual section files are included in the main Quarto document and share functions and variables. The report should therefore be rendered from the main `.qmd` file to ensure the correct execution order.

## Collaboration

The assignment was developed collaboratively using GitHub.

Each section was completed in a dedicated branch and integrated into `main` through pull requests. A final review was then performed to improve formatting, structure, explanations, and consistency across the complete report.

### Contributors

- [Jennifer Houmard](https://github.com/jenniferhoumard)
- [Ayesha Waheed](https://github.com/ayeshawaheed9)
- [Werner Binche](https://github.com/wernr-me)

## Project Outcome

The completed report demonstrates fundamental Python signal-processing techniques, including zero-crossing detection, local-extrema identification, frequency estimation, noise generation, and low-pass filtering.

It also documents the collaborative workflow and challenges encountered while developing a shared, reproducible Quarto report.
