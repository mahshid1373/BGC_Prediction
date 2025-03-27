# Biosynthetic Gene Cluster (BGC) Tools Comparison

<div align="center">

![BGC Analysis](figures/coelicolor_venn.png)

A comprehensive analysis and comparison of BGC detection tools for Streptomyces species

</div>

## 📋 Table of Contents
- [Overview](#overview)
- [Key Features](#key-features)
- [Installation](#installation)
- [Tools Analyzed](#tools-analyzed)
- [Results](#results)
  - [Streptomyces coelicolor](#streptomyces-coelicolor)
  - [Streptomyces ameniacus](#streptomyces-ameniacus)
  - [Streptomyces avidinii](#streptomyces-avidinii)
- [Contributing](#contributing)

## 🔍 Overview

This project provides a detailed comparative analysis of different tools used for detecting and classifying Biosynthetic Gene Clusters (BGCs) in bacterial genomes. The analysis focuses on three important Streptomyces species and evaluates the performance of leading BGC detection tools: antiSMASH, GECCO, and DeepBGC.

## ✨ Key Features

- Comprehensive comparison of three major BGC detection tools
- Analysis of genomic data from three Streptomyces species
- Visual representation of tool overlaps using Venn diagrams
- Dynamic genomic coordinate plots
- Detailed statistical analysis of tool performance
- Jupyter notebook implementation for reproducible research

## 🚀 Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/BGC_Prediction.git
cd BGC_Prediction
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

3. Install the BGC detection tools:
```bash
# antiSMASH
conda create -n antismash python=3.8
conda activate antismash
pip install antismash

# GECCO
pip install gecco-tool

# DeepBGC
pip install deepbgc
```

4. Run the Jupyter notebook:
```bash
jupyter notebook main.ipynb
```

## 🛠️ Tools Analyzed

### antiSMASH
- Industry standard for BGC detection
- Provides detailed annotations and classifications
- Comprehensive analysis of secondary metabolite biosynthesis pathways

### GECCO
- Rule-based approach for gene cluster detection
- Focuses on genomic context and gene organization
- Efficient processing of large genomic datasets

### DeepBGC
- Machine learning-based BGC classification
- Utilizes deep learning models for prediction
- Capable of detecting novel BGC types

## 📊 Results

### Streptomyces coelicolor
![S. coelicolor Results](figures/coelicolor_venn.png)

Key findings:
- 21 BGCs detected by all three tools
- 115 unique regions identified by DeepBGC
- 9 unique regions detected by GECCO
- 2 unique regions found by antiSMASH

### Streptomyces ameniacus
![S. ameniacus Results](figures/ameniacus_venn.png)

Key findings:
- 20 BGCs detected by all three tools
- 81 unique regions identified by DeepBGC
- 5 unique regions detected by antiSMASH
- 2 unique regions found by GECCO

### Streptomyces avidinii
![S. avidinii Results](figures/avidinii_venn.png)

Key findings:
- 23 BGCs detected by all three tools
- 67 unique regions identified by DeepBGC
- 8 unique regions detected by GECCO
- 1 unique region found by antiSMASH

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">
Created with ❤️ for the bioinformatics community
</div>



