# Advance Machine Learning

A comprehensive collection of advanced machine learning projects demonstrating practical applications of predictive modeling, clustering, and classification techniques.

## 📋 Repository Overview

This repository contains **7 machine learning notebooks** implementing various real-world use cases using Python, scikit-learn, and data visualization libraries. Each notebook demonstrates end-to-end machine learning workflows including data preprocessing, exploratory data analysis, model building, and evaluation.

---

## 📁 Projects

### 1. **Salary Predictor** 📊
**File**: `salary_predictor.ipynb`

**Objective**: Predict employee salaries based on multiple features

**Dataset**: 390 salary records with 6 features
- **Features**: Age, Gender, Education Level, Job Title, Years of Experience
- **Target**: Salary

**Key Characteristics**:
- Data Cleaning: Handles inconsistent categorical values (e.g., "Male", "male", "MALE")
- Missing Values: Addresses null values across all columns
- Data Quality Issues: Identifies outliers (negative ages, ages > 1000) and salary anomalies
- Statistical Analysis: Salary ranges from -$20,000 to $1,500,000 with mean ~$105,899

**ML Techniques Used**:
- Label Encoding for categorical features (Gender, Education Level, Job Title)
- Regression modeling for salary prediction
- Data preprocessing and normalization

**Insights**:
- Dataset has data quality issues requiring preprocessing
- Education level, job title, and experience significantly influence salary
- Gender distribution is relatively balanced (195 Male vs 180 Female)

---

### 2. **Customer Segmentation** 🎯
**File**: `customer_segmentation.ipynb`

**Objective**: Segment mall customers into meaningful groups for targeted marketing

**Dataset**: 200 mall customers with 2 features
- **Features**: Annual Income (k$), Spending Score (1-100)

**Key Techniques**:
- **Elbow Method**: Determines optimal number of clusters (k=5 identified)
- **K-Means Clustering**: Unsupervised learning algorithm
- Visualization: 2D scatter plots with cluster centroids

**Customer Segments Identified**:
1. **Premium Customers**: High Income + High Spending
2. **Careful Buyers**: High Income + Low Spending
3. **Budget Buyers**: Low Income + Low Spending
4. **Young Buyers**: Low Income + High Spending
5. **Middle-Class**: Medium Income + Medium Spending

**Business Applications**:
- Targeted marketing strategies per segment
- Personalized product recommendations
- Inventory management optimization

---

### 3. **Loan Prediction Model** 💰
**File**: `Loan_prediction_model.ipynb`

**Objective**: Predict loan approval/rejection status

**Key Features**:
- Classification task (Binary: Approved/Rejected)
- Analyzes creditworthiness and financial metrics
- Supports risk assessment in lending decisions

---

### 4. **Gearbox Failure Prediction** ⚙️
**File**: `gearbox_failure.ipynb`

**Objective**: Predict gearbox failures for predictive maintenance

**Use Case**: Manufacturing and industrial maintenance
- Early failure detection
- Reduce downtime and maintenance costs
- Optimize maintenance scheduling

**Domain**: Predictive Maintenance / Industrial IoT

---

### 5. **Wine Type Classification** 🍇
**File**: `wine_type_classify.ipynb` (12.9 MB - Largest notebook)

**Objective**: Classify wines into different types/categories

**ML Task**: Multi-class classification
- Uses wine characteristics (color, pH, acidity, alcohol content, etc.)
- Determines wine quality or type

**Potential Applications**:
- Quality control in wineries
- Automated wine classification
- Wine pairing recommendations

---

### 6. **Expense Segmentation** 💳
**File**: `expense_segmention.ipynb`

**Objective**: Segment expenses into categories for financial analysis

**Use Case**: Personal/Corporate expense tracking
- Categorize transactions
- Budget analysis
- Spending pattern identification

---

## 🛠️ Technology Stack

| Technology | Purpose |
|-----------|---------|
| **Python 3.x** | Core programming language |
| **Pandas** | Data manipulation and analysis |
| **NumPy** | Numerical computations |
| **Scikit-learn** | Machine learning algorithms |
| **Matplotlib** | Static data visualizations |
| **Seaborn** | Statistical data visualization |
| **Streamlit** | Web app deployment |
| **Joblib** | Model serialization |
| **Google Colab** | Development environment |

---

## 📊 Common ML Workflows

All notebooks follow a standard machine learning pipeline:

```
1. Data Loading & Exploration
   ↓
2. Data Cleaning & Preprocessing
   ↓
3. Exploratory Data Analysis (EDA)
   ↓
4. Feature Engineering & Selection
   ↓
5. Model Building & Training
   ↓
6. Model Evaluation & Validation
   ↓
7. Results Visualization
```

---

## 🔑 Key Machine Learning Concepts Covered

- **Supervised Learning**: Regression, Classification
- **Unsupervised Learning**: Clustering (K-Means)
- **Data Preprocessing**: Handling missing values, encoding categorical variables, outlier detection
- **Exploratory Data Analysis**: Statistical summaries, visualizations, distributions
- **Model Evaluation**: Performance metrics, validation techniques
- **Deployment**: Web application development with Streamlit

---

## 📈 Data Quality Observations

From the Salary Predictor notebook analysis:
- **Missing Data**: Up to 6 values missing in salary column
- **Inconsistent Categories**: Multiple representations of same value (e.g., "Male", "male", "MALE")
- **Outliers**: Invalid age values (-5, 1000) indicating data entry errors
- **Data Validation**: Important for preprocessing before modeling

---

## 💡 Use Cases & Business Impact

| Project | Business Benefit |
|---------|------------------|
| Salary Predictor | HR analytics, compensation planning |
| Customer Segmentation | Marketing optimization, revenue increase |
| Loan Prediction | Risk management, credit decisions |
| Gearbox Failure | Reduce downtime, cost savings |
| Wine Classification | Quality assurance, consistency |
| Expense Segmentation | Financial insights, budget control |

---

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy scikit-learn matplotlib seaborn streamlit joblib openpyxl
```

### Running Notebooks
1. Open notebooks in Google Colab or Jupyter
2. Ensure dataset paths are accessible
3. Run cells sequentially from top to bottom
4. Review visualizations and model outputs

### Running Streamlit App
```bash
streamlit run streamlit_salary_prediction_deployment.ipynb
```

---

## 📚 Learning Outcomes

After exploring this repository, you'll understand:
- ✅ End-to-end machine learning project structure
- ✅ Data preprocessing and cleaning techniques
- ✅ Supervised learning (regression, classification)
- ✅ Unsupervised learning (clustering)
- ✅ Model evaluation and visualization
- ✅ Deploying ML models as web applications
- ✅ Handling real-world data quality issues

---

## 🔍 Repository Statistics

- **Total Notebooks**: 7
- **Language**: Jupyter Notebook (100%)
- **Largest Project**: Wine Classification (12.9 MB)
- **Total Repository Size**: ~31.7 KB
- **Development Environment**: Google Colab
- **Created**: 2026
- **Status**: Active

---

## 📝 Notes

- All notebooks are developed in **Google Colab** with paths to Google Drive datasets
- Datasets are hosted on Google Drive and referenced in notebook file paths
- Code uses industry-standard libraries for reproducibility
- Each notebook is independent and can be run separately

---

## 🤝 Contributing

This is a learning repository. Feel free to:
- Explore the notebooks
- Modify and experiment with models
- Add improvements to data preprocessing
- Enhance visualizations
- Share insights and findings

---

## 📞 Contact

**Repository Owner**: [aryancodes12](https://github.com/aryancodes12)

For questions or suggestions, please open an issue in the repository.

---

**Happy Learning! 🎓**
