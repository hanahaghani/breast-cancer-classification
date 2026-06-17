Breast Cancer Classification (ML Project)
Overview
این پروژه یک مدل یادگیری ماشین برای تشخیص سرطان سینه است. هدف این است که بر اساس ویژگی‌های مختلف، تومور به دو دسته خوش‌خیم (Benign) و بدخیم (Malignant) تقسیم شود.
در این پروژه دو مدل Logistic Regression و SVC استفاده شده و عملکرد آن‌ها با هم مقایسه شده است.
Dataset
دیتاست شامل اطلاعات مربوط به ویژگی‌های سلولی سرطان سینه است.
پیش‌پردازش داده:
حذف ستون‌های id و Unnamed: 32
تبدیل لیبل‌ها با LabelEncoder
پر کردن مقادیر گمشده با median
استانداردسازی داده‌ها با StandardScaler
کاهش ابعاد با PCA (15 ویژگی)
مراحل پروژه
تقسیم داده به train و test (80/20)
آموزش مدل Logistic Regression
آموزش مدل SVC
ارزیابی مدل‌ها با معیارهای مختلف
مدل‌ها
Logistic Regression
Support Vector Classifier (SVC)
ارزیابی
برای بررسی عملکرد مدل‌ها از این موارد استفاده شده:
Accuracy
Precision
Recall
F1-score
Confusion Matrix
ROC Curve (برای SVC)
Visualization
در این پروژه چند نمودار برای تحلیل داده و مدل‌ها رسم شده:
PCA scatter plot
Confusion matrix برای هر دو مدل
ROC curve برای SVC
t-SNE visualization
ذخیره مدل
مدل‌های آموزش‌دیده با استفاده از joblib ذخیره شده‌اند:
Logistic Regression model
SVC model
