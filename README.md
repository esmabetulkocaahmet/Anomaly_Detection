Anomaly Detection & Cyber Attack Detection with Deep Learning 🛡️

Bu proje, ağ trafiği verilerini analiz ederek gerçek zamanlı anomali ve siber saldırı tespiti yapmak amacıyla geliştirilmiştir. Projede hem zamansal verileri işlemek için LSTM hem de öznitelik çıkarımı için Conv1D katmanları içeren karma bir derin öğrenme mimarisi kullanılmıştır.

🚀 Öne Çıkan Özellikler

Hibrit Mimari: CNN (Conv1D) ve RNN (LSTM) katmanlarının kombinasyonu.

Uçtan Uca Süreç: Veri toplama aşamasından model dağıtımına kadar tüm süreç simüle edilmiştir.

Geniş Kapsam: DoS, Brute Force ve Infiltration gibi farklı saldırı türlerinin tespiti.

🛠️ Veri Toplama ve Laboratuvar Ortamı (Data Collection)

Bu projenin en özgün yanı, verilerin kontrollü bir laboratuvar ortamında bizzat toplanmış olmasıdır:

Sanal Laboratuvar: VirtualBox üzerinde izole bir ağ (Host-only Adapter) kurulmuştur.

Saldırı Simülasyonu: Kali Linux (Saldırgan) ve Metasploitable/Windows (Kurban) makineleri kullanılarak gerçek saldırı senaryoları uygulanmıştır.

Trafik Yakalama: Wireshark ve TShark kullanılarak ağ paketleri .pcap formatında yakalanmış, ardından modelin işleyebileceği .csv formatına dönüştürülmüştür.

🛠️ Kullanılan Teknolojiler

Python (Pandas, NumPy)

TensorFlow / Keras (Sequential API)

Siber Güvenlik: VirtualBox, Kali Linux, Wireshark

Visualization: Matplotlib, Seaborn

📁 Klasör Yapısı

notebooks/: Model geliştirme ve eğitim süreçleri.

data/: Örnek veri seti yapıları ve yakalanan trafik örnekleri.

images/: Datast satırlarını gösteren bir görsel ve eğitim ile ilgili görseller.

📊 Model Mimarisi

Model şu katmanları içermektedir:

Conv1D: Yerel özniteliklerin çıkarılması.

MaxPooling1D: Boyut azaltma.

LSTM: Verilerdeki zamansal bağımlılıkların öğrenilmesi.

Dense: Sınıflandırma katmanı.

Katılımcılar: Esma Betül KOCAAHMET & Esma GELEBEK & Funda BOZBURUN
