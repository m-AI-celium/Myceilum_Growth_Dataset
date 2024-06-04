# Mycelium Growth and Structural Compression Dataset

This repository contains a dataset for monitoring mycelium growth, including images, geometrical parametres and structural testing data. The dataset was created as part of a thesis project within the [Integrative Technologies and Architectural Design Research](https://www.itech.uni-stuttgart.de/) ITECH MSc. Program at the [University of Stuttgart](https://www.uni-stuttgart.de/) in 2023.

## Samples

![overview](https://github.com/HussamAG/Myceilum_Growth/blob/main/overview.jpg)

## Directory Structure

mycelium-growth/
|
|00_growth_dataset/
|   | 00_curve_segments_images/
|   |   |-- S0_F1_0_0.jpg
|   |   |-- S1_F1_1_2.jpg
|   |   |-- ...
|   |-- 01_skin_scans_outer_curves/
|   |   |-- S0_F1_0_Skin.jpg
|   |   |-- S1_F1_1_Skin.jpg
|   |   |-- ...
|   |-- 02_skin_scans_infill/
|       |-- S0_0_Infill.jpg
|       |-- S1_1_Infill.jpg
|       |-- ...
|
|-- 01_structural_dataset/
|   |-- 00_samples_parameters.csv
|   |-- 00_samples_compression_test/
|   |   |-- 0.csv
|   |   |-- 1.csv
|   |   |-- ...
|   |-- README.md
|
|-- 02_raw_skin_scans/
|   |-- raw_skin_scan1.jpg
|   |-- raw_skin_scan2.jpg
|   |-- ...
|
|-- 03_raw_growth_images/
|   |-- raw_growth_image1.jpg
|   |-- raw_growth_image2.jpg
|   |-- ...
|
|
|-- README.md
|-- LICENSE

## Naming Convention

### Example

   - Images in 00_curve_segments_images: (S0_F1_0_0.jpg) Sample 0, Face 1, Segment 0, Growth Hour 0
   - Images in 01_skin_scans_outer_curves: (S1_F1_0_Skin.jpg) Sample 1, Face 1, Segment 0
   - Images in 02_skin_scans_infill: (S3_0_Infill.jpg) Sample 3, Segment 0

## General Information

This dataset was created by Hussamaldeen Gomaa, Yara Karazi, and Wai Man Chau, supervised by Eliza Biala and Zuardin Akbar, under the [ITECH MSc. Program](https://www.itech.uni-stuttgart.de/) at the University of Stuttgart in 2023. The collaboration involved the Institute for Computational Design and Construction (ICD), the Institute of Building Structures and Structural Design (ITKE), and the Institute for Building Construction (IBK).

## Contributors and Acknowledgements

   - Main contributors: Hussamaldeen Gomaa, Yara Karazi, Wai Man Chau, Eliza Biala, Zuardin Akbar.
   - Supervisors: Eliza Biala, Zuardin Akbar, Thomas Wortmann, Martin Ostermann.
   - Additional contributors: Tzu-Ying Chen: structural testing assistance, Mai Thi Nguyen: lab experimentation support, Michael Schneider and Andreas Kulla: sample post-processing.
   - All laboratory experiments and sample production were conducted at the Future Matter Lab (FUMA), part of the IBK, University of Stuttgart.

### Funding
Partially funded by BMBF "Ideenwettbewerbs Biologisierung der Technik" (grant number 13XP5154) and the Deutsche Forschungsgemeinschaft (DFG, German Research Foundation) under Germany’s Excellence Strategy – EXC 2120/1 – 390831618.

## License

This dataset is licensed under Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.


