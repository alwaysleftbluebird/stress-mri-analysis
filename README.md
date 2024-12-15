# **Exploring Stress-Related Brain Activity: A Neuroimaging Analysis**

## **Author**  
Sofie Veld  

## **Date**  
15 december 2024  

---

## **Project Description**

This project uses neuroimaging data to explore brain regions associated with stress. It visualizes functional MRI statistical maps overlaid on anatomical brain images and analyzes voxel intensity distributions to gain insights into stress-related neural activity. The analysis is conducted using Python and relevant neuroimaging libraries.

**Relevant Neurosynth Page**:  
[Stress - Neurosynth Concept Page](https://neurosynth.org/analyses/stress)  

---

## **Table of Contents**

| **Section**           | **Description**                                                                                  |
|------------------------|--------------------------------------------------------------------------------------------------|
| **Data**              | Neuroimaging data used for analysis: <br> - **`anatomical.nii.gz`**: Anatomical brain image. <br> - **`stress_uniformity-test_z_FDR_0.01.nii.gz`**: Functional MRI data showing brain regions associated with stress. <br> These files can be downloaded from [Neurosynth's Stress Analysis Page](https://neurosynth.org/analyses/stress).|
| **Notebook**          | Main notebook file: **`main.ipynb`**. Contains all the code and visualizations.     |
| **Readme**            | This file, which provides an overview of the project.                                           |

---

## **Python Packages Used**

The following Python packages were used in this project:  
- **os**: For file and directory operations.  
- **nilearn**: For visualizing and analyzing neuroimaging data.  
- **nibabel**: For loading and handling NIFTI neuroimaging files.  
- **matplotlib**: For plotting and visualizations.

---

## **.gitignore File**

A `.gitignore` file is included to ensure that unnecessary files (such as temporary files) are not tracked by Git. You can customize the `.gitignore` to fit your project needs.
