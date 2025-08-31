# Mean-Variance-Standard Deviation Calculator

This project implements a function `calculate()` that takes a list of **9 numbers**, reshapes them into a **3x3 NumPy array**, and returns a dictionary with several statistical calculations:

- Mean
- Variance
- Standard Deviation
- Maximum
- Minimum
- Sum  

The calculations are returned for:
1. Each column
2. Each row
3. The flattened matrix

---

## 🛠️ Tech Stack
- Python 3.8+
- NumPy
- Matplotlib (for visualization)

Install dependencies:
```bash
pip install -r requirements.txt

import matplotlib.pyplot as plt
import seaborn as sns

array = np.array([0,1,2,3,4,5,6,7,8]).reshape(3,3)
plt.figure(figsize=(4,4))
sns.heatmap(array, annot=True, cmap="Blues", cbar=False, square=True)
plt.title("3x3 Input Array")
plt.savefig("array_heatmap.png")







