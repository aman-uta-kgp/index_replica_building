# Index Replica Building: Comparative Study between single shot Mixed Integer Programming and a Two-Step Optimization Paradigm

Welcome to our project on constructing index replicas using advanced optimization techniques! This repository explores the effectiveness of two distinct optimization models: Mixed-Integer Programming (MIP) and a Two-Part Integer Programming approach, applied to replicate financial indices with precision.

## 📊 Project Overview

Index replication is a challenging task that involves selecting a subset of assets to match the performance of a target index. Our study presents a comparative analysis of MIP and Two-Part Integer Programming, evaluating their performance on out-of-sample data. We aimed to assess which model better captures index dynamics while balancing computational efficiency and replication accuracy.

## 🛠️ Key Methodologies

1. **Mixed-Integer Programming (MIP)**: We used this approach to optimize asset selection and allocation simultaneously, focusing on minimizing tracking error against the benchmark index.
2. **Two-Part Integer Programming**: In this approach, we split the problem into two sub-problems: asset selection and allocation, to improve computational feasibility and performance.

## 📈 Performance Evaluation

Our models were rigorously tested on out-of-sample data to understand real-world applicability. The comparative study reveals strengths and limitations of each model, providing valuable insights into the trade-offs between complexity and performance in financial index replication.

## 🔍 Insights & Takeaways

- **MIP**: Offers higher accuracy but can be computationally intensive for large datasets.
- **Two-Part Integer Programming**: Provides a more scalable solution with slightly reduced accuracy, suitable for scenarios with limited computational resources.
- **Real-World Implications**: Understanding these trade-offs is crucial for asset managers and financial engineers looking to optimize their strategies.

## 📚 Course Details

This project was completed as part of **RM 294: Optimization 1**, instructed by Professor Dan Mitchell. The study was a collaborative effort with my talented teammates:
- **Destin Blanchard**
- **Luke Leon**
- **Sarah Stephens**

## 🚀 Repository Structure

- **Data**: Contains the datasets used for model training and testing.
- **Scripts**: Includes Python scripts for data preprocessing, model implementation, and performance evaluation.
- **Results and Documentation**: Out-of-sample performance metrics and visualizations comparing the two models.

---

Feel free to dive into our findings, experiment with the models, and contribute to enhancing this study. We hope this project serves as a stepping stone for further advancements in the field of financial optimization and index replication!
