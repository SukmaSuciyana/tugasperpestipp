# Tugas Prescriptive Analytics - Optimasi dan Rekomendasi Keputusan

## 📋 Deskripsi Tugas

Tugas ini dirancang untuk mahasiswa memahami dan mengimplementasikan **Prescriptive Analytics** - tingkat tertinggi dalam analytics yang tidak hanya memprediksi apa yang akan terjadi, tetapi juga memberikan rekomendasi tindakan yang harus diambil untuk mencapai hasil optimal.

---

## 🎯 Tujuan Pembelajaran

1. Memahami perbedaan antara Descriptive, Predictive, dan Prescriptive Analytics
2. Mengimplementasikan teknik optimasi untuk pengambilan keputusan
3. Menggunakan algoritma seperti Linear Programming, Integer Programming, Genetic Algorithm, atau Reinforcement Learning
4. Memberikan rekomendasi actionable berdasarkan data

---



## 📝 Format Pengerjaan

### Struktur Project
```
project-folder/
│
├── data/
│   ├── raw/                 # Dataset original dari Kaggle
│   └── processed/           # Data setelah preprocessing
│
├── notebooks/
│   ├── 01_EDA.ipynb        # Exploratory Data Analysis
│   ├── 02_Predictive.ipynb # Model prediksi (jika diperlukan)
│   └── 03_Prescriptive.ipynb # Model optimasi dan rekomendasi
│
├── src/
│   ├── preprocessing.py     # Data cleaning & feature engineering
│   ├── optimization.py      # Optimization algorithms
│   └── visualization.py     # Plotting functions
│
├── results/
│   ├── recommendations.csv  # Output rekomendasi
│   └── optimization_report.pdf
│
├── README.md
└── requirements.txt
```

### Komponen Wajib dalam Notebook Prescriptive

#### 1. Problem Definition (10%)
- Jelaskan business problem secara detail
- Define decision variables (apa yang ingin dioptimasi?)
- Define objective function (minimize cost? maximize profit?)
- Define constraints (apa batasan yang harus dipatuhi?)

#### 2. Data Preparation (15%)
- Feature engineering untuk optimization
- Handle missing values dan outliers
- Create scenarios untuk sensitivity analysis

#### 3. Predictive Model (20%) - Jika diperlukan
- Build model untuk predict future behavior
- Model evaluation dan validation
- Feature importance analysis

#### 4. Optimization Model (35%)
- Formulate mathematical model
- Implement menggunakan library: PuLP, Pyomo, scipy.optimize, atau CVXPY
- Solve optimization problem
- Validate solution feasibility

#### 5. Prescriptive Recommendations (15%)
- Generate actionable recommendations
- Create what-if scenario analysis
- Sensitivity analysis (bagaimana jika parameter berubah?)
- Visualize trade-offs

#### 6. Business Impact (5%)
- Calculate expected ROI
- Compare vs current baseline
- Implementation roadmap

---

## 🛠️ Tools & Libraries

### Python Libraries Wajib:
```python
# Data Processing
pandas
numpy

# Visualization
matplotlib
seaborn
plotly

# Machine Learning (untuk predictive)
scikit-learn
xgboost / lightgbm

# Optimization
pulp              # Linear Programming
scipy.optimize    # Non-linear optimization
cvxpy             # Convex optimization
ortools           # Google OR-Tools untuk routing problems

# Optional (Advanced)
gurobipy          # Commercial solver (free academic license)
pyomo             # Advanced optimization modeling
```

### Install Dependencies:
```bash
pip install pandas numpy matplotlib seaborn plotly
pip install scikit-learn xgboost
pip install pulp scipy cvxpy
pip install ortools
```

---

## 📊 Kriteria Penilaian

| Aspek | Bobot | Deskripsi |
|-------|-------|-----------|
| **Problem Formulation** | 20% | Seberapa baik mendefinisikan masalah optimasi (decision variables, objective, constraints) |
| **Model Implementation** | 30% | Implementasi teknis optimization model, code quality |
| **Solution Quality** | 20% | Feasibility dan optimality dari solution |
| **Business Insights** | 20% | Actionable recommendations, what-if analysis, impact analysis |
| **Presentation** | 10% | Visualisasi, dokumentasi, storytelling |

---

## 🎯 Contoh Output yang Diharapkan

### Example: Store Sales Optimization

**Input:**
- Prediksi sales 2 minggu ke depan per produk per toko
- Current inventory level
- Storage capacity
- Ordering cost, holding cost, shortage cost

**Output:**
```
OPTIMIZED INVENTORY RECOMMENDATIONS

Store: New York Manhattan
Date Range: 2024-01-01 to 2024-01-14

Product: Laptop_Model_A
  Current Stock: 50 units
  Recommended Order: 75 units
  Expected Sales: 68 units
  Target Stock Level: 57 units
  Expected Cost Savings: $1,250
  Service Level: 98%

Product: Smartphone_Model_B
  Current Stock: 120 units
  Recommended Order: 0 units (Sufficient stock)
  Expected Sales: 95 units
  Target Stock Level: 85 units
  Expected Cost Savings: $800
  Service Level: 99%

Total Expected Savings: $2,050 per store
Total for All 50 Stores: $102,500
```

---

## 📚 Resources & References

### Tutorials:
1. Linear Programming with PuLP: https://coin-or.github.io/pulp/
2. Optimization in Python: https://realpython.com/linear-programming-python/
3. Google OR-Tools: https://developers.google.com/optimization

### Papers:
- "Prescriptive Analytics: The Final Frontier for Data Science" - Analytics Magazine
- "From Predictive to Prescriptive Analytics" - INFORMS

### Books:
- "Practical Optimization: A Gentle Introduction" - John W. Chinneck
- "Model Building in Mathematical Programming" - H.P. Williams

---

## ⏰ Timeline Pengerjaan

- **Week 1:** Pemilihan dataset & EDA
- **Week 2:** Problem formulation & predictive modeling
- **Week 3:** Optimization model development
- **Week 4:** Testing, validation, & presentation preparation

---

## 📮 Submission Guidelines

1. **Format:** Upload ke GitHub repository (public/private)
2. **Deadline:** [ISI TANGGAL DEADLINE]
3. **Include:**
   - Semua notebook dengan output cells
   - README.md dengan penjelasan project
   - requirements.txt
   - Dataset (atau link ke Kaggle)
   - Presentation slides (PDF)

4. **Presentation:** 15 menit per kelompok
   - Problem overview (2 min)
   - Technical approach (5 min)
   - Results & recommendations (5 min)
   - Q&A (3 min)

---

## ❓ FAQ

**Q: Apakah boleh menggunakan dataset selain yang disebutkan?**
A: Boleh, tapi harus konsultasi dulu untuk memastikan dataset cocok untuk prescriptive analytics.

**Q: Apakah harus menggunakan semua optimization techniques?**
A: Tidak, pilih yang paling sesuai dengan problem. Yang penting bisa justify kenapa pilih method tersebut.

**Q: Boleh dikerjakan individual atau harus kelompok?**
A: [SESUAIKAN DENGAN KEBIJAKAN ANDA]

**Q: Bagaimana jika optimization model tidak converge?**
A: Dokumentasikan issue-nya, coba simplify model, atau relax beberapa constraints. Yang penting ada attempt dan analysis.

---

**Good luck! Remember: The goal is not just to optimize, but to provide actionable insights that can drive better business decisions! 🚀**

---

## 🔗 Quick Links

- [Kaggle Datasets Collection](https://www.kaggle.com/datasets)
- [PuLP Documentation](https://coin-or.github.io/pulp/)
- [OR-Tools Guide](https://developers.google.com/optimization/introduction)
- [Optimization Cheat Sheet](https://wiki.openopt.org/index.php/Optimization_Cheat_Sheet)
