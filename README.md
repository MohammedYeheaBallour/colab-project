# ☁️ خدمة معالجة البيانات السحابية الموزعة (Cloud-Based Data Processing Service)

---

## 📌 نظرة عامة
هذا المشروع تم تطويره كجزء من مساق **Cloud and Distributed Systems (SICT 4313)** في الجامعة الإسلامية – غزة.  
الهدف هو تصميم وتنفيذ خدمة لمعالجة البيانات على السحابة باستخدام **Apache Spark (PySpark)** مع واجهة تفاعلية مبنية على **Gradio** داخل بيئة **Google Colab**.

---

## 🧪 المزايا
- 📂 رفع مجموعات البيانات (Datasets) إلى التخزين السحابي **Google Drive**.  
- 📊 حساب 4 إحصاءات وصفية (Descriptive Statistics):  
  - حجم البيانات (عدد الصفوف والأعمدة).  
  - أنواع البيانات (Numeric, String).  
  - القيم المفقودة (Missing Values).  
  - إحصاءات أساسية (Min, Max, Mean, Std).  
- 🤖 تنفيذ 4 مهام تعلم آلي (Machine Learning Jobs):  
  - Linear Regression.  
  - Decision Tree Regression.  
  - Random Forest Regression.  
  - K-Means Clustering.  
- ⚡ قياس الأداء (Performance Measurement) على 1، 2، 4، و8 عقد (Nodes) مع حساب السرعة (Speedup) والكفاءة (Efficiency).  
- 💾 تنزيل النتائج (Results) من التخزين السحابي.  

---

## 🛠️ التقنيات المستخدمة
- لغة البرمجة: **Python**  
- مكتبات: **PySpark**, **Gradio**, **Pandas**, **Findspark**  
- بيئة التطوير: **Google Colab**  
- التخزين: **Google Drive**  

---

## 📂 هيكل المشروع
       → الكود المصدري (Claude_Project.ipynb)

requirements.txt  → المكتبات المطلوبة
README.md      → وصف المشروع

كتابة تعليمات برمجية

---

## 📥 التثبيت
لتثبيت المكتبات المطلوبة:
```bash
pip install pyspark findspark gradio pandas
🚀 كيفية التشغيل
افتح ملف الـ Notebook على Google Colab.

اربط Google Drive مع Colab.

نفّذ جميع الخلايا البرمجية (Run all cells).

استخدم واجهة Gradio للتفاعل مع الخدمة.

🔗 روابط
📁 مستودع GitHub: https://github.com/MohammedYeheaBallour/colab-project

🚀 ملف Colab: https://colab.research.google.com/drive/18IatzjxpwikAO8j9GccYYMmy6ob0C0uj?usp=sharing