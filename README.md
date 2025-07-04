# K-Nearest Neighbors (KNN) Classification Project

This project demonstrates the use of K-Nearest Neighbors (KNN) algorithm on a sample dataset to perform classification tasks. It includes data preprocessing, model training, evaluation, and visualization, implemented within a Jupyter Notebook.

---

## 📁 Repository Contents

- `Iris_KNN_Classification.ipynb`: Main notebook containing the classification workflow.
- `.github/workflows/run_notebook.yml`: GitHub Actions workflow that automates the notebook execution.
- `requirements.txt`: List of Python dependencies.

---

## ⚙️ Automation with GitHub Actions

This project includes a CI/CD pipeline powered by GitHub Actions:

- ✅ Automatically executes the notebook on every push to the `main` branch
- ✅ Uses `papermill` to run the notebook and generate `output.ipynb`
- ✅ Ensures environment compatibility with pinned dependencies

### Workflow Trigger
```yaml
on:
  push:
    branches: [main]
