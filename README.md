# Student Learning Recommendation System

## Overview
This project builds a recommendation system for student learning based on their activity logs. The system utilizes clustering and sequential pattern mining techniques to identify learning patterns and suggest relevant educational resources.

## Features
- **Data Processing**: Converts student learning logs into structured sequences.
- **TF-IDF Encoding**: Transforms activity sequences into numerical representations.
- **Hierarchical Agglomerative Clustering (HAC)**: Groups students based on their learning behaviors.
- **Sequential Pattern Mining (PrefixSpan)**: Identifies frequent learning patterns.
- **Association Rule Mining (Apriori)**: Extracts relationships between learning activities.

## Dataset
The project uses a **synthetic dataset** containing simulated student activity logs. Each student follows a sequence of learning activities, which are analyzed to identify patterns and trends.

## Performance Analysis
The system's performance is limited due to the synthetic nature of the dataset:
- **Limited Variability**: The dataset lacks the natural diversity found in real student behaviors, leading to biased patterns.
- **Overfitting Risks**: The model may learn patterns that do not generalize to real-world data.
- **Cluster Ambiguity**: If synthetic interactions lack clear patterns, clustering effectiveness is reduced.

## Future Improvements
To improve the system, future iterations should consider:
- Using real-world student data for training.
- Incorporating reinforcement learning to adapt recommendations dynamically.
- Evaluating different clustering methods for more robust pattern discovery.

## How to Run
1. Install dependencies:
   ```bash
   pip install pandas numpy torch sklearn mlxtend prefixspan matplotlib
   ```
2. Run the notebook to preprocess data and train models.
3. Analyze the clustering results and recommendation outputs.




