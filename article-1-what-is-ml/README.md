
# What is Machine Learning?

This folder contains all resources for the first article in the **Machine Learning Fundamentals** series: "What is Machine Learning?". The article introduces key concepts and includes a simple experiment with the Iris dataset.

## Article Overview
In this article, we explore the fundamental concepts of machine learning (ML), including:
- What is ML and how it differs from traditional programming?
- Types of machine learning: Supervised, Unsupervised, and Reinforcement Learning.
- A basic example of supervised learning using the **Iris dataset**.

## Folder Structure
The folder is organized as follows:

- `data/`: Datasets used in the article and experiments.
    - `raw/`: Original data (not modified).
    - `processed/`: Processed or cleaned data, ready for analysis.
- `notebooks/`: Jupyter notebooks containing the practical implementation of the article's concepts.
    - `what_is_ml.ipynb`: The Jupyter notebook with the experiment, data analysis, and model building.
- `scripts/`: Python scripts used for data preprocessing, utility functions, and other supportive tasks.
    - `helpers.py`: Example of helper functions for preprocessing.
- `article.md`: Full text of the article, ready to be published on Medium or any platform.
- `README.md`: Documentation for this article and its resources.

## Running the Experiment

This article is accompanied by a practical implementation of the concepts introduced. The experiment uses the **Iris dataset** and involves:

- **Loading and preprocessing** the dataset.
- **Building a simple classification model** (e.g., Logistic Regression).
- **Evaluating the model** using basic metrics and visualizations.

### Steps to Run the Experiment

1. **Start Jupyter Notebook** in the `article-1-what-is-ml/` folder:
   ```bash
   jupyter notebook

2. Open the **`what_is_ml.ipynb`** notebook in the Jupyter interface and run the cells to:
   - Explore the Iris dataset.
   - Implement a supervised learning model.
   - Analyze the results with visualizations.
   - Refer to the comments and explanations in the notebook to understand the step-by-step process.

### Additional Resources

- **Notebook**: [notebooks/what_is_ml.ipynb](notebooks/what_is_ml.ipynb)  
  Contains detailed steps for implementing the model and analyzing the data.
- **Scripts**: [scripts/helpers.py](scripts/helpers.py)  
  Includes reusable functions for data preprocessing and visualization.

## License
The resources in this article are provided under the MIT License. See the [LICENSE](../../LICENSE) file for more information.

## Contact
For any questions or suggestions related to this article, feel free to reach out via the GitHub issues or directly by email.
