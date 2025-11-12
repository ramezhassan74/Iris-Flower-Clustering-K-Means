## 🇪🇬 Scroll for Arabic ⬇️

# 🌸 Iris Flower Clustering using K-Means

## 📘 Project Overview
This project applies **K-Means Clustering**, an unsupervised machine learning algorithm, to the famous **Iris dataset**.  
The goal is to group iris flowers into clusters based on their **sepal** and **petal** measurements — without using the actual species labels.

After clustering, the results are compared with the real species (`Setosa`, `Versicolor`, `Virginica`) to evaluate how well K-Means identifies natural groupings in the data.

---

## 🧩 Dataset
**Columns:**
- `sepal_length`
- `sepal_width`
- `petal_length`
- `petal_width`
- `species` (for evaluation only)

---

## ⚙️ Steps
1. Load and explore the dataset  
2. Scale the features using `StandardScaler`  
3. Apply **K-Means** with `n_clusters=3`  
4. Compare predicted clusters with actual species  
5. Visualize clusters using `Seaborn`  

---

## 📊 Results
**Clustering Accuracy:** `83.33%`

**Confusion Matrix:**
[[50 0 0]
[ 0 39 11]
[ 0 14 36]]

**Cluster Centers:**
[[-0.0502 -0.8803 0.3475 0.2820]
[-1.0146 0.8423 -1.3049 -1.2551]
[ 1.1360 0.0966 0.9963 1.0172]]

---

## 📈 Visualization
- Scatter plot of clusters (petal length vs petal width)  
- Comparison between actual species and predicted clusters  

---

## 💡 Insights
- **Setosa** forms a perfectly distinct cluster 🌸  
- **Versicolor** and **Virginica** overlap slightly — a known challenge in this dataset  
- K-Means successfully identified the natural structure with ~83% accuracy  
- Demonstrates the power of **unsupervised learning**

---

## 🚀 Possible Improvements
- Use **Elbow Method** or **Silhouette Score** to confirm optimal k  
- Try **PCA** to visualize clusters in 2D  
- Compare with **Hierarchical Clustering** or **DBSCAN**

---

## 🧠 Tech Stack
- Python 🐍  
- Pandas, NumPy  
- Scikit-learn  
- Seaborn, Matplotlib  

---

## 📁 Files
| File | Description |
|------|--------------|
| `iris.csv` | Dataset |
| `kmeans_iris.py` | Full clustering code |
| `README.md` | Project documentation |

---

---

# 🌸 مشروع تجميع زهور Iris باستخدام K-Means

## 📘 نظرة عامة
في هذا المشروع تم استخدام خوارزمية **K-Means Clustering** (خوارزمية تعلم غير خاضع للإشراف) على **بيانات زهور Iris** الشهيرة.  
الهدف هو **تجميع الزهور في مجموعات** بناءً على قياسات **السبلات والبتلات**، دون استخدام الأنواع الحقيقية أثناء التدريب.

بعد تنفيذ التجميع، تمت مقارنة النتائج بالأنواع الحقيقية لمعرفة مدى قدرة الخوارزمية على اكتشاف الأنماط الطبيعية في البيانات.

---

## 🧩 البيانات
الأعمدة:
- `sepal_length` – طول السبلات  
- `sepal_width` – عرض السبلات  
- `petal_length` – طول البتلات  
- `petal_width` – عرض البتلات  
- `species` – النوع الحقيقي (للمقارنة فقط)

---

## ⚙️ الخطوات
1. تحميل واستكشاف البيانات  
2. توحيد القيم باستخدام `StandardScaler`  
3. تطبيق خوارزمية **K-Means** بعدد 3 مجموعات  
4. مقارنة النتائج بالأنواع الحقيقية  
5. رسم بياني لتوضيح التجمعات

---

## 📊 النتائج
**دقة التجميع:** `83.33%`

**مصفوفة الالتباس:**

[[50 0 0]
[ 0 39 11]
[ 0 14 36]]

**مراكز المجموعات:**
[[-0.0502 -0.8803 0.3475 0.2820]
[-1.0146 0.8423 -1.3049 -1.2551]
[ 1.1360 0.0966 0.9963 1.0172]]


---

## 📈 التصور البياني
- رسم Scatter يوضح توزيع التجمعات حسب طول وعرض البتلات  
- رسم آخر للمقارنة بين الأنواع الحقيقية والتجمعات المكتشفة  

---

## 💡 الاستنتاجات
- نوع **Setosa** ظهر في مجموعة منفصلة وواضحة تمامًا 🌸  
- يوجد تداخل بسيط بين **Versicolor** و **Virginica** — وهذا طبيعي في البيانات الأصلية  
- K-Means نجح في اكتشاف الأنماط بنسبة دقة عالية (83%)  
- يوضح المشروع قوة خوارزميات **التعلم غير الخاضع للإشراف**

---

## 🚀 تحسينات مستقبلية
- تطبيق **Elbow Method** أو **Silhouette Score** لتأكيد عدد المجموعات الأمثل  
- تجربة **PCA** لتقليل الأبعاد وعرض النتائج بصريًا  
- مقارنة النتائج مع **Hierarchical Clustering** أو **DBSCAN**

---

## 🧠 الأدوات المستخدمة
- Python 🐍  
- Pandas, NumPy  
- Scikit-learn  
- Seaborn, Matplotlib  

---
