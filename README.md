# SKILLSync: Resume and Job Matching System

## Overview

**SKILLSync** is an intelligent system designed to bridge talent and job opportunities through robust text processing, NLP, and machine learning. This project, developed under the guidance of Prof. Lu Xiao, focuses on creating a powerful job matching tool by extracting, transforming, and analyzing information from resumes and job descriptions.

## Key Features

- **Python Libraries:** Utilizes crucial Python libraries for data analysis, text processing, NLP, and machine learning to establish a robust foundation.

- **Text Preprocessing:** Implements text preprocessing functions for cleaning and preparing data, with a primary focus on skills extraction. Techniques like label encoding and TF-IDF vectorization are employed for effective data transformation.

- **K-Nearest Neighbors (KNN):** Utilizes the KNN algorithm for classification, enabling a detailed evaluation of accuracy and a comprehensive classification report.

- **PDF Parsing:** Uses PyPDF2 for parsing PDF files, extracting text from each page.

- **Vectorization Techniques:** Employs TF-IDF and Count Vectorization to enhance the representation of document content.

- **Sentiment Analysis:** Utilizes the KNN algorithm for intelligent skill matching, gauging the closeness of skills through numerical representation and cosine similarity.

## Operational Insights

### Data Visualization

**Top 20 Skills Distribution:**
- Generates a bar chart using seaborn to visualize the distribution of the top 20 skills based on their occurrence counts.

**Resume Categories Distribution:**
- Utilizes a countplot to visualize the distribution of resumes across different categories, aiding users in understanding the landscape of job opportunities.

### Performance Evaluation

**KNN Performance Evaluation:**
- Provides a vivid histogram showcasing the top 10 missing skills between a resume and a job description. Calculates dissimilarity percentages to identify crucial skills lacking in the resume based on job requirements.

**Text Similarity Measurement (Cosine Similarity):**
- Creates a heatmap visually representing the presence or absence of each skill in a resume compared to a job description. The custom colors enhance the interpretability of the heatmap, offering a quick and clear snapshot of skill alignment.

## References

1. Sajid et al., "Resume Parsing Framework for E-recruitment," 2022. [IEEE Xplore]
2. Ali et al., "Resume classification system using NLP and ML techniques," 2022. [Informit](https://search.informit.org/doi/10.3316/informit.263278216314684)
3. Bharadwaj et al., "Resume Analysis Using NLP," 2023. [Springer](https://doi.org/10.1007/978-981-99-1624-5_40)
4. Tejaswini K et al. (2022) achieved 85% parsing and 92% ranking accuracy using cosine similarity and KNN. [Global Transitions Proceedings](https://doi.org/10.1016/j.gltp.2021.10.002)
5. G. Rafiei et al. (2021) presented "Automating HR Recruiting" at the 5th NCAEA in Mashhad, Iran, achieving 43-47. [IEEE Xplore](https://doi.org/10.1109/NCAEA54556.2021.9690504)
6. P. Singh et al., "Automatic Candidature Selection by Artificial NLP," Springer, 2023. [DOI]

## Operational Considerations

In managing SKILLSync's operations, the focus is on scalability, real-time capabilities, and data privacy. Regular model updates, user feedback, and continuous monitoring ensure system relevance, user satisfaction, and optimal NLP performance.
