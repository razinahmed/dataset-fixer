# Dataset Fixer

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![ML](https://img.shields.io/badge/ML-Data_Pipeline-orange)
![License](https://img.shields.io/badge/License-MIT-green)

A machine learning dataset cleaning and preprocessing tool that detects and fixes common data quality issues. Automates the tedious process of handling missing values, duplicates, outliers, and format inconsistencies in training datasets.

---

## Features

- **Missing Value Detection** -- Identifies and imputes missing data using statistical methods
- **Duplicate Removal** -- Finds and eliminates duplicate or near-duplicate records
- **Outlier Detection** -- Flags statistical outliers using IQR, Z-score, and isolation forest methods
- **Format Standardization** -- Normalizes date formats, encodings, and data types
- **Label Validation** -- Checks classification labels for consistency and typos
- **Data Profiling** -- Generates comprehensive quality reports for your datasets

---

## Tech Stack

| Technology | Purpose |
|---|---|
| Python 3.9+ | Core runtime |
| Pandas / NumPy | Data manipulation |
| scikit-learn | Statistical analysis |
| CSS3 | Report theming |
| Makefile | Build and test automation |

---

## Quick Start

```bash
# Clone the repository
git clone https://github.com/razinahmed/dataset-fixer.git
cd dataset-fixer

# Install dependencies
pip install -r requirements.txt

# Clean a dataset
python main.py --input dirty_data.csv --output clean_data.csv
```

---

## Project Structure

```
dataset-fixer/
├── styles/
│   └── theme.css           # Report theme configuration
├── Makefile                # Build and test commands
├── LICENSE                 # MIT License
├── SECURITY.md             # Security policy
└── README.md
```

---

## Usage

```bash
# Build the project
make build

# Run tests
make test
```

---

## Contributing

1. Fork the repository
2. Create a feature branch -- `git checkout -b feature/your-feature`
3. Commit your changes -- `git commit -m "feat: add new feature"`
4. Push and open a Pull Request

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

**Built by [Razin Ahmed](https://github.com/razinahmed)**
