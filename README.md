# 🧠 Breast Cancer Classification (Machine Learning Project)

# 📌 Overview

این پروژه یک مدل یادگیری ماشین برای تشخیص سرطان سینه است که هدفش دسته‌بندی تومورها به دو حالت Benign (خوش‌خیم) و Malignant (بدخیم) است.

در این پروژه دو مدل مختلف آموزش داده شده و عملکرد آن‌ها با هم مقایسه شده است.

# 📊 Dataset
دیتاست شامل ویژگی‌های مربوط به سلول‌های سرطانی است.
# 🔧 Data Preprocessing:
حذف ستون‌های اضافی (id, Unnamed: 32)

تبدیل لیبل‌ها با LabelEncoder

پر کردن داده‌های گمشده با median

استانداردسازی داده‌ها (StandardScaler)

کاهش ابعاد با PCA (15 component)

# ⚙️ Workflow
تقسیم داده‌ها به train و test (80/20)

آموزش مدل‌ها

پیش‌بینی روی داده تست

ارزیابی عملکرد مدل‌ها

# 🤖 Models

Logistic Regression (baseline model)

Support Vector Classifier (SVC)

# 📈 Evaluation Metrics
برای بررسی عملکرد مدل‌ها از معیارهای زیر استفاده شده:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

ROC Curve (برای SVC)


# 📊 Visualizations

PCA scatter plot

Confusion matrix (برای هر دو مدل)

ROC curve برای SVC

t-SNE projection

# 💾 Model Saving
مدل‌های آموزش‌دیده با joblib ذخیره شده‌اند:

Logistic Regression model

SVC model
