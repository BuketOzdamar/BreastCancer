🧬 Breast Cancer Classification & EDA
Bu proje, meme kanseri teşhisine yardımcı olmak amacıyla gerçekleştirilen bir veri bilimi çalışmasıdır. Hem keşifsel veri analizi (EDA) hem de makine öğrenmesi algoritmalarıyla sınıflandırma süreçleri içermektedir.

📁 Veri Kümesi
Veri kümesi, meme kanseri hücre örnekleri üzerine toplanmış 9 adet nitelik ve 1 hedef sınıftan oluşmaktadır.

Özellik	Açıklama
ClumpThickness	Hücre yığınlarının kalınlığı
UniformityCellSize	Hücre boyutlarının benzerliği
UniformityCellShape	Hücre şekillerinin benzerliği
MarginalAdhesion	Hücrelerin birbirine yapışma düzeyi
SingleEpithelialCellSize	Tekil epitelyal hücre büyüklüğü
BareNuclei	Hücre çekirdeği içeriği
BlandChromatin	Kromatin yapısının düzlüğü
NormalNucleoli	Normal nükleol sayısı
Mitoses	Hücre bölünme sayısı
Malignite	Hedef değişken – 2: Benign, 4: Malign (0 ve 1’e çevrilmiştir)

🔍 Yapılan Analizler
🧪 EDA (Keşifsel Veri Analizi)
📈 Korelasyon matrisi (heatmap)

📦 Boxplot ve violinplot ile sınıfa göre dağılım

🔁 Pairplot ile değişkenler arası ilişki

📉 Histogramlar

🧬 PCA ile boyut indirgeme (isteğe bağlı)

🤖 Makine Öğrenmesi Modelleri
Veri seti eğitim ve test olarak ayrılmış, aşağıdaki algoritmalar uygulanmıştır:

✅ K-Nearest Neighbors (KNN)

✅ Naive Bayes

✅ Random Forest

✅ Support Vector Machine (SVM)

📊 Model Performans Kriterleri
Her model için:

Doğruluk (accuracy)

F1

Precision

🛠️ Kullanılan Kütüphaneler
pandas
numpy
matplotlib
seaborn
scikit-learn
