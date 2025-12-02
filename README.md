# Scan-2-QC: Quality Control of Prefabricated Structural Systems using Point Cloud
# Introduction
This repository presents a generic solution to automatic detection of prefabricated elements with arbitrarily-shaped cross-sections from point clouds using a new robust artificial intelligence (AI) least-squares fitting, referred to as scan-2-QC for brevity. Four new algorithms were developed to: (i) represent the cross-sectional boundaries of elements with parametric trigonometric polynomials, (ii) perform orthogonal fitting of points to these polynomials, (iii) remove outlying observations through robust concentration steps (CS), and (iv) perform assembly verification of prefabricated elements in construction projects. The scan-2-QC framework can be integrated with common building information modeling (BIM) frameworks to report construction tolerances and generate the geometric digital twin of structural systems. The figure below shows the schmatics of such an integration.
![Figure 1-d](https://github.com/user-attachments/assets/dc5cc16b-d7b9-4fdc-8efb-d952e2d0c0a4)

# Algorithm Development and Methodology
The scan-2-QC framework involves the following general steps:

1- Registration of point cloud into the BIM project coordinate system
2- Detection of points of each BIM element through a new robust model fitting strategy, solved through AI-based optimization methods
3- Generation of relevant descriptive analytics to visualize the severity of tolerance violation of each construted and assembled prefabricated element

The following video provides a visual demonstration of the scan-to-QC process.



# Explanation of Repository Files
Four sets of standalone Matlab Applications are provided together with this repository to allow the users to apply random and large transormations on the point cloud of a sample W–Section. Two overall categories, based on the operating systems of Mac and Windows was provided. Each contained two types of Apps, namely, parallel, and no-parallel. The parallel app performs the optimization using the Parallel Processing Toolbox of MATLAB, where as the no-parallel app performs optimization evaluations through single core processing.

# Citation
The study is published in the IEEE Access journal, where the mathematical formulations are explained in more detail. You may cite the study using the following information:

Maalek, R., Maalek, S. 2025. Scan-2-QC: Quality Control of Prefabricated Structural Systems using Point Cloud, IEEE Access, doi:10.1109/ACCESS.2025.3639809.

# Acknowledgements

The author wishes to acknowledge the generous endowment provided by GOLDBECK GmbH to the Karlsruhe Institute of Technology (KIT) for the establishment of the Professorship in Digital Engineering and Construction at the Institute of Technology and Management in Construction (TMB).
