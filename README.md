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

## 📊 Dataset Kaggle dan Tugas Prescriptive

Pilih **SATU** dari 6 dataset berikut dan kerjakan komponen Prescriptive Analytics-nya:

### 1. **Store Sales - Time Series Forecasting**
**Link:** https://www.kaggle.com/competitions/store-sales-time-series-forecasting

**Deskripsi Dataset:**
- Data penjualan dari ribuan produk di berbagai toko
- Informasi promosi, hari libur, harga minyak
- Data historis penjualan per kategori produk

**Tugas Prescriptive:**
1. **Optimasi Inventory Management:**
   - Tentukan jumlah stok optimal untuk setiap produk di setiap toko
   - Minimasi biaya penyimpanan dan stockout
   - Pertimbangkan lead time dan demand uncertainty

2. **Optimasi Promosi Budget:**
   - Alokasikan budget promosi ke produk dan toko yang tepat
   - Maksimalkan ROI dari aktivitas promosi
   - Tentukan timing optimal untuk promosi

3. **Workforce Scheduling:**
   - Tentukan jumlah karyawan optimal per shift berdasarkan prediksi penjualan
   - Minimasi overtime cost sambil memenuhi service level

**Deliverables:**
- Model optimasi (Linear Programming/Mixed Integer Programming)
- Rekomendasi stok per produk per toko untuk 2 minggu ke depan
- Dashboard visualisasi dengan skenario what-if analysis

---

### 2. **Retail Rocket Recommender System**
**Link:** https://www.kaggle.com/datasets/retailrocket/ecommerce-dataset

**Deskripsi Dataset:**
- Data behavior customer (view, add to cart, transaction)
- Data properti produk
- Timestamp interaksi user-item

**Tugas Prescriptive:**
1. **Dynamic Pricing Optimization:**
   - Tentukan harga optimal untuk setiap produk berdasarkan demand elasticity
   - Maksimalkan revenue atau profit margin
   - Pertimbangkan competitor pricing dan customer segments

2. **Product Bundle Optimization:**
   - Tentukan kombinasi produk optimal untuk bundling
   - Maksimalkan cross-selling dan basket size
   - Optimalkan discount level untuk bundle

3. **Personalized Marketing Campaign:**
   - Tentukan produk mana yang harus dipromosikan ke customer tertentu
   - Alokasikan marketing budget optimal per customer segment
   - Tentukan channel komunikasi terbaik (email, push notif, SMS)

**Deliverables:**
- Optimization model untuk pricing strategy
- Rekomendasi bundle produk dengan expected revenue lift
- Action plan untuk personalized campaign dengan budget allocation

---

### 3. **Customer Churn Prediction (Telco/Bank)**
**Link:** https://www.kaggle.com/datasets/blastchar/telco-customer-churn

**Deskripsi Dataset:**
- Data demografi customer
- Data layanan yang digunakan
- Data pembayaran dan kontrak
- Status churn (Yes/No)

**Tugas Prescriptive:**
1. **Retention Budget Optimization:**
   - Tentukan customer mana yang harus diberi retention offer
   - Alokasikan budget retention secara optimal
   - Tentukan jenis incentive optimal per customer segment

2. **Proactive Intervention Strategy:**
   - Tentukan timing optimal untuk melakukan intervention
   - Pilih action terbaik (discount, upgrade, personal call, gift)
   - Maksimalkan Customer Lifetime Value (CLV)

3. **Resource Allocation:**
   - Alokasikan customer service agent ke high-risk churn customers
   - Optimasi call center capacity planning
   - Prioritize customer contacts berdasarkan churn risk dan value

**Deliverables:**
- Optimization model untuk retention investment
- Prioritized list customer dengan recommended action
- Expected ROI dari retention strategy

---

### 4. **Supply Chain Shipment Pricing**
**Link:** https://www.kaggle.com/datasets/divyeshardeshana/supply-chain-shipment-pricing-data

**Deskripsi Dataset:**
- Data shipment (origin, destination, weight, volume)
- Freight cost per carrier
- Delivery time dan service level
- Product categories

**Tugas Prescriptive:**
1. **Carrier Selection Optimization:**
   - Tentukan carrier optimal untuk setiap shipment
   - Minimasi total logistics cost
   - Pertimbangkan constraints: delivery time, capacity, service level

2. **Route Optimization:**
   - Tentukan routing optimal untuk multiple deliveries
   - Minimasi transportation cost dan CO2 emission
   - Consolidate shipments untuk efisiensi

3. **Warehouse Location Optimization:**
   - Tentukan lokasi warehouse optimal untuk mengurangi shipping cost
   - Balance antara warehouse cost dan transportation cost
   - Pertimbangkan demand distribution

**Deliverables:**
- Multi-objective optimization model
- Recommended carrier per shipment type
- Cost savings simulation dan trade-off analysis

---

### 5. **Marketing Campaign Performance**
**Link:** https://www.kaggle.com/datasets/rodsaldanha/arketing-campaign

**Deskripsi Dataset:**
- Data customer demographics
- Purchase history
- Campaign response history
- Channel preferences

**Tugas Prescriptive:**
1. **Campaign Budget Allocation:**
   - Alokasikan marketing budget optimal across channels
   - Maksimalkan conversion atau revenue
   - Tentukan budget per customer segment

2. **Next Best Offer (NBO):**
   - Tentukan produk mana yang harus di-offer ke customer tertentu
   - Tentukan timing optimal untuk offer
   - Personalize discount level per customer

3. **Customer Contact Optimization:**
   - Tentukan frequency optimal untuk contact customer
   - Pilih channel terbaik per customer (email, phone, social media)
   - Avoid over-communication yang bisa jadi spam

**Deliverables:**
- Budget allocation model dengan expected return
- Personalized offer recommendation per customer
- Contact strategy calendar untuk 3 bulan ke depan

---

### 6. **Hospital Emergency Room (ER) Management**
**Link:** https://www.kaggle.com/datasets/maalona/hospital-er-emergency-room

**Deskripsi Dataset:**
- Patient arrival data dengan timestamp
- Triage level (emergency level)
- Wait time dan service time
- Department assignment

**Tugas Prescriptive:**
1. **Staffing Optimization:**
   - Tentukan jumlah dokter dan nurse optimal per shift
   - Minimasi wait time sambil minimasi labor cost
   - Pertimbangkan skill mix requirements

2. **Patient Flow Optimization:**
   - Tentukan assignment optimal patient ke treatment room
   - Prioritize patient berdasarkan severity dan wait time
   - Minimasi overall patient length of stay

3. **Resource Allocation:**
   - Alokasikan medical equipment ke departemen yang tepat
   - Tentukan capacity planning untuk bed dan equipment
   - Balance utilization dan service level

**Deliverables:**
- Optimization model untuk staff scheduling
- Patient prioritization algorithm dengan fairness constraints
- Simulation untuk scenario planning (normal vs peak hours)

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
