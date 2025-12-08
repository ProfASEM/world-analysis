

🌍 World Data Analysis Project

This project demonstrates a complete end-to-end data analysis workflow, starting from collecting raw data, cleaning it using Python, preparing it with SQL, and finally building an interactive Power BI dashboard for insights and storytelling.
It simulates a real-world BI project by integrating data from multiple sources and overcoming common data challenges.

> Note: Although the dataset is clean and well-structured, it is not fully up-to-date, and this project should be considered a training simulation designed to practice real analytical workflows.




---

🎯 Project Objectives

Collect, explore, and clean data from multiple sources.

Handle missing values, inconsistent formatting, and type issues.

Perform descriptive and exploratory data analysis.

Use Python, Pandas, SQL for data preparation.

Build relationships and a data model in Power BI.

Design interactive dashboards for insights and storytelling.



---

🛠 Tools & Technologies

Python (Pandas, NumPy)

Jupyter Notebook

SQL

Power BI

Web Scraping (when needed)



---

📂 Project Structure

|-- notebook/
|     └── world_analysis.ipynb
|-- data/
|     ├── world.sql
|-- dashboard/
|     └── world dashboard.pbix
|-- README.md


---

🧹 Data Cleaning Steps

Identifying missing values and deciding how to handle them.

Fixing inconsistent formatting (text, numbers, dates).

Converting units (e.g., GDP values).

Removing duplicates.

Standardizing key fields for merging (country names/codes).

Merging datasets from different sources.

Exporting final cleaned dataset.



---

🔍 Exploratory Data Analysis

Performed using Python:

Summary statistics

Distribution analysis

Correlation analysis

Outlier detection

Feature comparisons


> Most visualizations were later implemented in Power BI for better presentation.




---

📊 Power BI Dashboard

Includes:

Global KPIs (Population, GDP, Growth Rate, etc.)

Top and bottom countries by key metrics

GDP and Life Expectancy trends

Language distributions

HDI world map

Correlation matrix

Country-level detailed report page

A mobile-friendly layout for phone viewing

<img src="images\Main Page.png">
<img src="images\HDI.png">
<img src="images\Filter Page.png">


> Dashboard file available in: dashboard/world_data_report.pbix
<a href="dashboard\world dashboard.pbix">




---

⚙️ Challenges & Solutions

1️⃣ Integrating Data from Multiple Sources

Challenge: Data came from different formats, structures, and naming conventions.
Solution:

Built a Power BI data model using cleaned keys.

Standardized country names/codes using Python.

Validated joins using SQL before import.



---

2️⃣ Importing SQL Data into Power BI

Challenge: Importing SQL tables caused encoding and datatype issues.
Solution:

Cleaned SQL output in Python first.

Reassigned column types in Power BI (Power Query → Transform Data).

Split large SQL tables into smaller structured ones.



---

3️⃣ GDP Column Contained Textual Values

Examples:
$3.5 trillion, $850B, 1.2 billion

Solution:

Built a custom Python function to convert all textual GDP units into numeric values.

Applied final validation in Power BI with Transform Data.


This allowed correct calculations, correlations, and rankings.


---

4️⃣ Visual Design and Layout Challenges

Challenge: Achieving a clean, modern layout with balanced visuals.
Solution:

Improved visual formatting, colors, spacing, and alignment.

Rebuilt charts from scratch when needed.

Designed a phone layout version separately.



---

5️⃣ Dataset Was Not Fully Up-to-Date

This project aims to simulate a realistic BI workflow rather than provide current global statistics.


---

💡 Key Insights

(Replace these with your actual insights if needed)

Countries with high GDP often show higher life expectancy.

Population distribution is highly uneven globally.

Some regions show consistent negative growth rates.

HDI strongly correlates with economic and educational indicators.



---

🚀 How to Run This Project

1. Clone or download this repository.


2. Open the Jupyter Notebook in the notebooks/ folder.


3. Run all cells to reproduce data cleaning and analysis.


4. Open the Power BI file to interact with the dashboard.




---

📬 Contact

If you'd like to connect:
LinkedIn: (www.linkedin.com/in/asem-haij-9797562a8)


---

🎉 Thank you for exploring this project!
Feel free to reach out for discussion or collaboration.




🌍 مشروع تحليل بيانات العالم

هذا المشروع يقدّم سير عمل كامل لتحليل البيانات من البداية حتى النهاية، بدءًا من جمع البيانات الخام، مرورًا بتنظيفها باستخدام Python، ومعالجتها باستخدام SQL، وانتهاءً ببناء لوحة تحكم تفاعلية في Power BI لعرض النتائج وصناعة القصة البصرية.

يحاكي المشروع تجربة BI حقيقية عبر دمج بيانات من مصادر متعددة والتعامل مع تحديات البيانات الشائعة.

ملاحظة: رغم أن البيانات منظمة إلى حد ما، إلا أنها ليست محدثة بالكامل، لذا يُعد المشروع محاكاة تدريبية لتطبيق خطوات التحليل العملية.

🎯 أهداف المشروع

جمع واستكشاف وتنظيف البيانات من مصادر متعددة

معالجة القيم المفقودة وعدم الاتساق في الصيغ والأنواع

إجراء تحليل وصفي واستكشافي

استخدام Python وPandas وSQL لإعداد البيانات

بناء نموذج بيانات في Power BI وربط الجداول

تصميم لوحات تحكم تفاعلية لعرض البيانات وصياغة قصة بصرية قوية

🛠 الأدوات والتقنيات المستخدمة

Python (Pandas, NumPy)

Jupyter Notebook

SQL

Power BI

Web Scraping (عند الحاجة)

📂 هيكل المشروع
|-- notebook/
|     └── world_analysis.ipynb
|-- data/
|     ├── world.sql
|-- dashboard/
|     └── world dashboard.pbix
|-- README.md

🧹 خطوات تنظيف البيانات

تحديد القيم المفقودة واتخاذ القرار المناسب لمعالجتها

إصلاح مشاكل التنسيق (النصوص، الأرقام، التواريخ)

تحويل الوحدات (مثل قيم الناتج المحلي GDP)

إزالة البيانات المكررة

توحيد أسماء/رموز الدول قبل الدمج

دمج البيانات القادمة من مصادر مختلفة

تصدير النسخة النهائية النظيفة من البيانات

🔍 التحليل الاستكشافي

تم باستخدام Python وشمل:

الإحصاءات الوصفية

تحليل التوزيعات

تحليل الارتباطات

كشف القيم الشاذة

مقارنة الميزات

تم تنفيذ معظم الرسوم البيانية لاحقًا في Power BI بشكل أكثر احترافية.

📊 لوحة تحكم Power BI

تتضمن:

مؤشرات عالمية (السكان، الناتج المحلي، معدل النمو … إلخ)

أعلى وأدنى الدول حسب المؤشرات

اتجاهات الناتج المحلي ومتوسط العمر

توزيع اللغات حول العالم

خريطة مؤشر HDI

مصفوفة الارتباط

صفحة تقارير تفصيلية لكل دولة

نسخة متوافقة مع الهاتف المحمول

<img src="images/Main Page.png"> <img src="images/HDI.png"> <img src="images/Filter Page.png">

ملف لوحة التحكم متوفر في:

<a href="dashboard/world dashboard.pbix">
⚙️ التحديات والحلول
1️⃣ دمج البيانات من مصادر متعددة

التحدي: اختلاف التنسيقات والأسماء والهياكل
الحل:

بناء نموذج بيانات في Power BI باستخدام مفاتيح موحدة

توحيد أسماء الدول باستخدام Python

التحقق من عمليات الدمج باستخدام SQL قبل الاستيراد

2️⃣ استيراد البيانات من SQL إلى Power BI

التحدي: مشاكل الترميز وأنواع البيانات
الحل:

تنظيف البيانات أولًا في Python

ضبط أنواع الأعمدة في Power Query

تقسيم الجداول الكبيرة عند الحاجة

3️⃣ عمود الناتج المحلي GDP يحتوي على قيم نصية

أمثلة:

3.5 trillion$

850B$

1.2 billion

الحل:

إنشاء دالة Python مخصصة لتحويل جميع القيم النصية إلى أرقام

التحقق النهائي في Power BI عبر Transform Data

4️⃣ تحديات التصميم البصري

التحدي: بناء تصميم حديث ومنسق ومناسب للمستخدم
الحل:

تحسين الألوان والمسافات والهوامش

إعادة بناء بعض الرسوم للحصول على أفضل عرض

تصميم نسخة خاصة بالهاتف المحمول

5️⃣ البيانات غير محدثة بالكامل

هذا المشروع يهدف إلى محاكاة سير عمل تحليلي واقعي أكثر من إعطاء إحصائيات عالمية حديثة.

💡 أهم النتائج

(يمكنك تعديلها حسب نتائجك الفعلية)

الدول ذات الناتج المحلي الأعلى غالبًا ما تمتلك متوسط عمر متوقع أعلى

التوزيع السكاني حول العالم غير متوازن بشكل كبير

بعض المناطق تشهد معدلات نمو سلبية

مؤشر HDI يرتبط بقوة بالمؤشرات الاقتصادية والتعليمية

🚀 طريقة تشغيل المشروع

تحميل المشروع أو استنساخه من GitHub

فتح الـ Notebook داخل مجلد notebook/

تشغيل الخلايا لإعادة خطوات التنظيف والتحليل

فتح ملف Power BI لاستكشاف لوحة التحكم التفاعلية

📬 للتواصل

LinkedIn:
(www.linkedin.com/in/asem-haij-9797562a8)

🎉 شكرًا لاستكشاف هذا المشروع!
لا تتردد بالتواصل للمناقشة أو التعاون.
