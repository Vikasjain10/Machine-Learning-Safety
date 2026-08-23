# Machine Learning Safety – CARLA Perception System

This repository contains the code, Jupyter notebooks, trained models, and supporting
files used for the **Introduction to Machine Learning Safety** course and the
accompanying Safety Case Report.

## Project Overview

The project evaluates a CARLA-based autonomous driving perception system from a
machine learning safety perspective. The analysis focuses on detection performance,
adversarial robustness, uncertainty calibration, explainability, and
out-of-distribution detection.

## Perception Models

The system consists of three independent binary classification models:

- **Pedestrian detection**
- **Vehicle detection**
- **Traffic-light detection**

All three models use a pretrained **ResNet18** backbone.

## Repository Contents

The repository contains the exercise notebooks, trained model checkpoints,
Grad-CAM visualisations, and supporting files used in the safety evaluation.

## Safety Evaluation

The main verification activities include:

- **V-1:** In-distribution detection performance
- **V-2:** Robustness to adversarial perturbations
- **V-3:** Calibrated uncertainty
- **V-4:** Out-of-distribution detection
- **V-5:** Safe system fallback

## Results

The final safety evaluation identified weaknesses in pedestrian detection,
adversarial robustness, and confidence calibration, while the k-NN based
OOD detector showed strong performance.

## Author

**Vikas Jain**  
Matriculation Number: 261612  
Otto-von-Guericke University Magdeburg

## GitHub Repository

https://github.com/Vikasjain10/Machine-Learning-Safety/tree/main
