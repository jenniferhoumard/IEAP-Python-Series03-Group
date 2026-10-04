# IEAP – Python Series 03 | Group Assignment

**Université de Montpellier**  
**Master 1 – Ingénierie et Ergonomie de l'Activité Physique (IEAP)**  
**2026–2027**

## Overview

This repository contains the group assignment for **Python Series 03**, focusing on signal processing, remarkable-point detection, signal generation, noise analysis, and filtering using Python.

The project also introduces collaborative development using **Git and GitHub**, with individual branches, pull requests, code integration, and a shared final report created using **Quarto**.

## Project Content

The assignment is organized into five main sections, each divided into subsections corresponding to individual Quarto (`.qmd`) files.

### 1. Group Organization and GitHub Workflow
- #### **1.1. Group Organization**
  Description of the task distribution, individual responsibilities, GitHub branch structure, and collaborative workflow used throughout the assignment.

### 2. Remarkable-Point Detection
- #### **2.1. Functions to Find and Plot Zero Crossings**
  Implementation of functions to detect positive and negative zero crossings, handle exact zero values, test the functions, and visualize the results.
- #### **2.2. Explain and Improve Existing Code**
  Analysis and explanation of the provided Python code, including improvements to its implementation.
- #### **2.3. Functions to Find Local Maxima and Minima**
  Implementation and testing of reusable functions to identify and visualize local maxima and minima in a signal.

### 3. Signal Generation and Analysis
- #### **3.1. Create a Signal**
  Generation and visualization of sinusoidal signals using Python.
- #### **3.2. Remarkable Points**
  Application of the previously developed functions to identify and visualize zero crossings, local maxima, and local minima in the generated signal.
- #### **3.3. Signal Frequency**
  Estimation of signal period and frequency using the detected zero crossings.

### 4. Noise Analysis and Filtering
- #### **4.1. Noisy Signal**
  Addition of normally distributed random noise to the generated signal and visualization of its effects.
- #### **4.2. Remarkable Points in the Noisy Signal**
  Analysis of how noise affects the detection of zero crossings, local maxima, and local minima.
- #### **4.3. Low-Pass Filtering**
  Application of a Butterworth low-pass filter to reduce noise, compare original and filtered signals, and evaluate improvements in remarkable-point detection and frequency estimation.

### 5. Critical Points and Problem Solving
- #### **5.1. Critical Points**
  Documentation of challenges encountered during the assignment, including generated HTML files, reuse of functions across sections, and GitHub branch and pull request     issues, along with their solutions.

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
