Anomaly Detection & Cyber Attack Detection with Deep Learning 🛡️

Bu proje, ağ trafiği verilerini analiz ederek gerçek zamanlı anomali ve siber saldırı tespiti yapmak amacıyla geliştirilmiştir. Projede hem zamansal verileri işlemek için LSTM hem de öznitelik çıkarımı için Conv1D katmanları içeren karma bir derin öğrenme mimarisi kullanılmıştır.

🚀 Öne Çıkan Özellikler

Hibrit Mimari: CNN (Conv1D) ve RNN (LSTM) katmanlarının kombinasyonu.

Veri İşleme: Ağ trafiği verilerinin (Network Traffic) normalize edilmesi ve zaman serisi formatına dönüştürülmesi.

Geniş Kapsam: DoS, Brute Force ve Infiltration gibi farklı saldırı türlerinin tespiti.

🛠️ Kullanılan Teknolojiler

Python (Pandas, NumPy)

TensorFlow / Keras (Sequential API)

Scikit-learn (Preprocessing & Evaluation)

Visualization: Matplotlib, Seaborn

📁 Klasör Yapısı

notebooks/: Model geliştirme ve eğitim süreçleri.

data/: Örnek veri seti yapıları.

images/: Karmaşıklık matrisi (Confusion Matrix) ve eğitim grafikleri.

📊 Model Mimarisi

Model şu katmanları içermektedir:

Conv1D: Yerel özniteliklerin çıkarılması.

MaxPooling1D: Boyut azaltma.

LSTM: Verilerdeki zamansal bağımlılıkların öğrenilmesi.

Dense: Sınıflandırma katmanı.

Katılımcılar: Esma Betül KOCAAHMET & Esma GELEBEK & Funda BOZBURUN
