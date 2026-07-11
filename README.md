# PyDefectData
Open-source Python defect prediction dataset with software metrics, defect labels, preprocessing scripts, and benchmark datasets for machine learning research.
# Features
- Open-source Python project dataset
- Static software metrics extracted from source code
- Defect labels for supervised learning
- Ready for machine learning experiments
- Suitable for software defect prediction research
- Easy-to-use CSV format

## Dataset Overview

The dataset contains software entities (e.g., classes or modules) represented by software metrics and corresponding defect labels.

Example features include:

| Feature | Description |
|---------|-------------|
| LOC | Lines of Code |
| CC | Cyclomatic Complexity |
| WMC | Weighted Methods per Class |
| CBO | Coupling Between Objects |
| RFC | Response for a Class |
| LCOM | Lack of Cohesion in Methods |
| DIT | Depth of Inheritance Tree |
| NOC | Number of Children |
| Defect | Binary defect label (0 = Non-defective, 1 = Defective) |

> Note: Available metrics may vary depending on the project.
> ## Getting Started

Clone the repository:

```bash
git clone https://github.com/<username>/PyDefectData.git
cd PyDefectData
```

Load a dataset:

```python
import pandas as pd

df = pd.read_csv("datasets/project1.csv")
print(df.head())
```

## Citation

If you use this dataset in your research, please cite:

```
Kapse, R., & Harsoor, B. (2026). PyDefectData: An open-source Python project defect prediction dataset [Data set]. 
GitHub. https://github.com/kapserahul74/PyDefectData
```
