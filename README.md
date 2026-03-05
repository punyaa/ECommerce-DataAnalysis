ECommerce Data Analysis

A comprehensive data analysis project on e-commerce orders, covering data preprocessing, exploratory data analysis, supervised learning, and unsupervised learning techniques.

---

## Project Overview

This project involves analyzing e-commerce order data through multiple analytical techniques to derive insights and build predictive models. The work is organized into three progressive tasks.

---

## Tasks Completed

### Task 1: Data Preprocessing and Exploratory Data Analysis

**File:** [Task_1.ipynb](Task_1.ipynb)

**Objectives:**
- Load and integrate four relational tables: `orders`, `order_items`, `order_shipping`, and `payments`
- Join multiple tables into a single, unified order-level dataset
- Perform data cleaning and transformation
- Conduct exploratory data analysis (EDA) and create visualizations

**Key Activities:**
- Data loading and integration from multiple sources
- Data quality assessment and cleaning
- Feature engineering and data transformation
- Statistical summaries and visualization
- Dataset preparation for downstream analysis

---

### Task 2: Supervised Learning Techniques

**File:** [Task_2_11.ipynb](Task_2_11.ipynb)

**Objectives:**
- Apply supervised learning techniques to build classification models
- Develop models to predict payment method (`payment_type`) used for each order
- Leverage order characteristics and attributes as predictive features
- Evaluate and compare multiple classification approaches

**Key Activities:**
- Feature selection and preprocessing for supervised learning
- Data splitting and model preparation
- Implementation and training of multiple classification algorithms
- Model evaluation using appropriate metrics
- Comparison and analysis of model performance

---

### Task 3: Unsupervised Learning and Market Basket Analysis

**File:** [Task_3_11.ipynb](Task_3_11.ipynb)

**Objectives:**
- Apply clustering techniques to identify similar order types
- Perform market basket analysis using association rule mining
- Explore patterns and relationships in e-commerce transactions
- Publish findings and insights

**Key Activities:**
- Clustering analysis to segment orders
- Market basket analysis and association rules discovery
- Pattern identification in customer purchasing behavior
- Findings documentation and interpretation
- GitHub Pages publication for results dissemination

---

## Dataset

**Primary Data:** [ecommerce_orders_cleaned_Grp11.csv](ecommerce_orders_cleaned_Grp11.csv)

The dataset contains cleaned and integrated e-commerce order information with comprehensive attributes for analysis.

---

## Outputs

- **Interactive Notebooks:** 
  - [Task 1 HTML Report](Task_1.html)
  - [Task 2 HTML Report](Task_2_11.html)
  - [Task 3 HTML Report](Task_3_11.html)

- **Project Website:** [GitHub Pages](index.html)

---

## Repository Structure

```
.
├── Task_1.ipynb                      # Task 1: Data Preprocessing & EDA
├── Task_1.html                       # Task 1 HTML output
├── Task_2_11.ipynb                  # Task 2: Supervised Learning
├── Task_2_11.html                   # Task 2 HTML output
├── Task_3_11.ipynb                  # Task 3: Unsupervised Learning
├── Task_3_11.html                   # Task 3 HTML output
├── ecommerce_orders_cleaned_Grp11.csv  # Dataset
├── index.html                        # Project website
├── README.md                         # This file
└── .git/                            # Version control
```

---

## Technologies Used

- **Python 3**
- **Data Analysis:** pandas, NumPy
- **Machine Learning:** scikit-learn
- **Visualization:** Matplotlib, Seaborn, Plotly
- **Notebooks:** Jupyter

---

## How to Use

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd ECommerece-DataAnalysis
   ```

2. **Install Dependencies**
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn plotly jupyter
   ```

3. **Run the Notebooks**
   - Open each `.ipynb` file in Jupyter Notebook or VS Code
   - Execute cells sequentially from top to bottom
   - Follow the instructions within each notebook

---

## Notes

- All notebooks follow a structured, top-to-bottom workflow
- Each task builds upon the insights and data from previous tasks
- Results are documented within the notebooks and published as HTML reports

---


