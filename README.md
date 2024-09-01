# Application of Gaussian Mixture Model Clustering Technique Based on Characteristics of Access to Clean Water and Proper Sanitation in Indonesia 🔎💧

## Overview
This project involves the application of Gaussian Mixture Models (GMM) to cluster the 34 provinces of Indonesia based on their characteristics related to access to clean water and proper sanitation. The choice of the GMM is motivated by its ability to model data distributions that follow a Gaussian pattern (also known as a Normal distribution) with more than one peak, providing flexibility in identifying clusters with different characteristics.

## Objectives
- **Cluster the 34 provinces** of Indonesia into several groups based on characteristics related to access to clean water and proper sanitation.
- **Understand the characteristics** of each cluster to provide insights into the water and sanitation conditions across Indonesia.

## Background
Indonesia faces challenges related to declining access to clean water and proper sanitation, which have been predicted to deteriorate further each year. This issue poses significant health risks and affects the quality of life for many Indonesian households. To address these challenges, clustering analysis can provide a better understanding of the regional disparities in access to these essential services, thereby aiding policymakers and stakeholders in implementing targeted interventions.
## Dataset
The data used for this analysis comes from the Badan Pusat Statistik (BPS) (Statistics Indonesia), accessible via [this link.](https://www.bps.go.id/id/statistics-table?subject=525). The dataset contains:
- Provinsi: Menunjukkan 34 provinsi di Indonesia.
- Persentase Rumah Tangga dengan Sumber Air Minum Layak
- Persentase Rumah Tangga dengan Akses terhadap Sanitasi Layak
- Persentase Rumah Tangga yang Memiliki Fasilitas Cuci Tangan dengan Sabun dan Air


## Methodology
- **Variable Selection**: Select relevant variables for clustering that represent the access to clean water and proper sanitation.
- **Data Characterization**: Understand the characteristics of the selected data to determine the appropriate clustering method.
- **Gaussian Mixture Model (GMM)**: The GMM was chosen as it successfully clusters the 34 provinces into three categories: Good, Needs Attention, and Needs Significant Attention. This method allows for a flexible clustering approach that accommodates the natural variability in the data.

## Results and Findings
The clustering analysis resulted in three distinct clusters with the following characteristics:

* **Cluster 1**: High overall average — 92% access to safe drinking water, 83.5% access to proper sanitation, and 83.7% access to handwashing facilities (Regions classified as "Good").
* **Cluster 2**: Low overall average — 65.4% access to safe drinking water, 40.34% access to proper sanitation, and 40.91% access to handwashing facilities (Regions classified as "Needs Significant Attention").
* **Cluster 3**: Intermediate overall average — 83.63% access to safe drinking water, 80.82% access to proper sanitation, and 76% access to handwashing facilities (Regions classified as "Needs Attention").
These clusters help identify regions with different needs and allow targeted policy formulation to improve water and sanitation conditions.
## 📝 Additional Resources
For a more comprehensive discussion of this analysis, you can read my detailed article on Medium:
[Penerapan Teknik Clustering Gaussian Mixture Model berdasarkan Karakteristik Akses Air Bersih serta Sanitasi Layak di Indonesia | Analisis Juara 2 SIC SATRIA DATA 2024]([https://medium.com/@mahardinalendra](https://medium.com/@mahardinalendra/penerapan-teknik-clustering-gaussian-mixture-model-berdasarkan-karakteristik-akses-air-bersih-serta-914d36a663b5))


## 🥈 Awards 
This analysis, presented in infographic form, won 2nd place in the Statistika Ria and Data Science Festival (SATRIA DATA) 2024 organized by Balai Pengembangan Talenta Indonesia (BPTI), Pusat Prestasi Nasional (PUSPRESNAS), Kementerian Pendidikan, Kebudayaan, Riset, dan Teknologi (KEMENDIKBUDRISTEK)

## 📰 Media Coverage:
- *Tim Mahasiswa UGM Raih Juara di Kompetisi Statistika Ria dan Festival Sains Data* - [Pemberitaan UGM](https://ugm.ac.id/id/berita/tim-mahasiswa-ugm-raih-juara-di-kompetisi-statistika-ria-dan-festival-sains-data/)
- *Mahasiswa FMIPA UGM Raih Juara di Ajang Satria Data 2024* - [Pemberitaan FMIPA UGM](https://mipa.ugm.ac.id/2024/08/07/mahasiswa-fmipa-ugm-raih-juara-di-ajang-satria-data-2024/)
- *Kontingen Universitas Gadjah Mada Kembali Torehkan Prestasi dalam Satria Data 2024* - [Pemberitaan Kreativitas UGM](https://math.fmipa.ugm.ac.id/id/mahasiswa-departemen-matematika-ugm-raih-prestasi-di-kompetisi-python-based-data-analysis-2024/](https://mipa.ugm.ac.id/2024/08/07/mahasiswa-fmipa-ugm-raih-juara-di-ajang-satria-data-2024/)](https://kreativitas.ugm.ac.id/?p=11973))
