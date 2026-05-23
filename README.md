# NumPy 🔢

> Four focused Jupyter notebooks covering NumPy from fundamentals to advanced array operations — creation, indexing, broadcasting, math, views vs copies, and practice exercises.

---

## Notebooks

| Notebook | Topic | What's Covered |
|---|---|---|
| `basic.ipynb` | Fundamentals | `np.array()`, `dtype`, `shape`, `ndim`, `size`, `zeros`, `ones`, `arange` |
| `Array-operations.ipynb` | Operations | Element-wise math, broadcasting rules, universal functions (ufuncs), manipulation |
| `practise.ipynb` | Practice | Real-world problems applying everything from basics and operations |
| `last_part.ipynb` | Advanced | Advanced indexing (boolean, fancy), views vs copies, memory management, stats |

Sample `.npy` arrays are included (`array1.npy`, `array2.npy`, `array3.npy`) — loaded directly in the notebooks so you can run exercises without sourcing external data.

---

## Quick Start

```bash
git clone https://github.com/Wcoder547/Numpy.git
cd Numpy
pip install numpy jupyter matplotlib
jupyter notebook
```

Work through the notebooks in order: `basic` → `Array-operations` → `practise` → `last_part`.

---

## Skills Covered

- Array creation — `np.zeros`, `np.ones`, `np.arange`, `np.linspace`, `np.random`
- Array attributes — `shape`, `dtype`, `ndim`, `size`
- Indexing & slicing — basic, boolean, fancy indexing
- Broadcasting — rules and real examples
- Math & stats — element-wise ops, `mean`, `std`, `min`, `max`, matrix operations
- Manipulation — `reshape`, `transpose`, `concatenate`, `stack`
- Views vs copies — understanding when NumPy shares memory vs copies it
- Performance — why NumPy is fast and how to write vectorized code

---

## Tech Stack

- Python 3.11+
- NumPy 2.0+
- Jupyter Notebooks
- Matplotlib (optional, used in some visualizations)

---

## About

NumPy is the foundation everything else in the Python data stack is built on — pandas, scikit-learn, and PyTorch all use NumPy arrays under the hood. Understanding broadcasting, views vs copies, and vectorized operations makes you a faster and more efficient data engineer.

**Built by [Waseem Akram](https://www.linkedin.com/in/wasim-akram-dev/)** — Full-Stack Developer and DevOps Engineer based in Pakistan, working across the MERN stack, Generative AI integrations, and cloud automation.

---

*If this helped you, consider giving it a ⭐*
