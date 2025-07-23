🧬 Breast Cancer Classification & EDA
Bu proje, meme kanseri teşhisine yardımcı olmak amacıyla gerçekleştirilen bir veri bilimi çalışmasıdır. Hem keşifsel veri analizi (EDA) hem de makine öğrenmesi algoritmalarıyla sınıflandırma süreçleri içermektedir.

📁 Veri Kümesi
Veri kümesi, meme kanseri hücre örnekleri üzerine toplanmış 9 adet nitelik ve 1 hedef sınıftan oluşmaktadır.

## 📊 Özellik Açıklamaları (Breast Cancer Dataset)

| Özellik Adı                    | Açıklama                                                                 |
|-------------------------------|--------------------------------------------------------------------------|
| `ClumpThickness`              | Hücre yığınlarının kalınlığı. Kalınlık arttıkça malignite riski artar. |
| `UniformityCellSize`          | Hücre boyutlarının tutarlılığı. Yüksek değerler düzensiz hücre boyutlarına işaret eder. |
| `UniformityCellShape`         | Hücre şekillerinin tutarlılığı. Yüksek skorlar, şekil bozukluklarını gösterir. |
| `MarginalAdhesion`            | Hücrelerin kenar yapışkanlığı. Düşük yapışkanlık, hücrelerin ayrıştığını gösterir. |
| `SingleEpithelialCellSize`    | Tekil epitelyal hücrelerin boyutu. Artan büyüklük, anormalliğe işaret edebilir. |
| `BareNuclei`                  | Çevresiz (çıplak) çekirdek sayısı. Yüksek değerler, malign hücre göstergesi olabilir. |
| `BlandChromatin`              | Kromatin yapısının düzenliliği. Düzensiz yapı, hücrelerin kanserli olabileceğini gösterir. |
| `NormalNucleoli`              | Nükleol (çekirdekçik) sayısı. Normalden fazla nükleol, hücre anormalliğini gösterir. |
| `Mitoses`                     | Hücre bölünme oranı. Yüksek mitoz, hızlı hücre çoğalmasına ve tümör riskine işaret eder. |
| `Malignite`                   | Hedef sınıf. `2 = Benign (iyi huylu)`, `4 = Malign (kötü huylu)` olarak etiketlenmiştir. |


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
