!\[sklearn](https://img.shields.io/badge/sklearn-red)

<p align="center">
    <b> Sklearn </b><br>
</p>

<details>
<summary> ❀ What is sklearn</summary>
 
- Open source Machine Learning Library <br>
- Build on top of Numpy, Scipy and Matplotlib <br>
- provides API for all ML algorithms <br> 

</details>



<details>
<summary> ⚝ Core Features</summary>

- Data preprocessing
- Supervised learning algorithms
- Unsupervised learning algorithms
- Model evaluation \& validation
- Feature selection \& dimensionality reduction
- Pipelines for end-to-end ML workflows
</details>

<details>
<summary> ⁑  Datasets </summary> <br>

## 🧠 Basics
<details>
<summary> Basic </summary>
for 
- experimenting, 
- learning,
- testing, and 
- benchmarking 
machine learning algorithms.

save time for  
- data collection and cleaning, 

focus on modeling and evaluation.
</details>
---

## 🧠 Purpose of sklearn.datasets
<details>
<summary> Purpose of dataset in sklearn</summary><br>
- Provide **clean, ready-to-use datasets**
- Maintain **consistency** across ML experiments
- Enable **fair comparison** of algorithms
- Serve as **educational & interview datasets**
- Help validate ML pipelines quickly

</details>
---

## 🗂 Dataset Categories
<details>
<summary> 1️⃣ Toy (Small Built-in) Datasets
</summary>
These are small datasets packaged directly with sklearn.

| Function | Samples | Features | Task |
|-------|--------|----------|------|
| `load_iris()` | 150 | 4 | Classification |
| `load_wine()` | 178 | 13 | Classification |
| `load_breast_cancer()` | 569 | 30 | Classification |
| `load_digits()` | 1797 | 64 | Classification |
| `load_diabetes()` | 442 | 10 | Regression |

📌 Used in:
- Tutorials
- Interview coding questions
- Algorithm demos
</details>
---
<details>
<summary>2️⃣ Real-World Datasets (Downloaded)
</summary>
These datasets are **not packaged** with sklearn and are downloaded on demand.

| Function | Description |
|------|------------|
| `fetch_california_housing()` | Housing price prediction |
| `fetch_20newsgroups()` | Text classification |
| `fetch_openml()` | Access thousands of datasets |

📌 Stored locally after first download.
</details>
---
<details>
<summary>3️⃣ Synthetic (Generated) Datasets
</summary>
Used to **simulate controlled ML scenarios**.

| Function | Use Case |
|------|--------|
| `make_classification()` | Custom classification data |
| `make_regression()` | Linear & noisy regression |
| `make_blobs()` | Clustering |
| `make_moons()` | Non-linear decision boundaries |
| `make_circles()` | Circular data patterns |

📌 Very useful for:
- Algorithm testing
- Visualizations
- Edge-case simulations
</details>
---

## 📦 Dataset Object Structure (Bunch)

Most sklearn datasets return a **Bunch object**, similar to a dictionary.

```python
from sklearn.datasets import load_iris
data = load_iris()
```

</details>




