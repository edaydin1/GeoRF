📞 My Call Center - Veri Analizi Projesi
Bu proje, çağrı merkezi (call center) verileri üzerinde analiz ve görselleştirme çalışmaları yapmayı amaçlamaktadır. Veri setinde eksik olan konumsal bilgiler (şehir, enlem, boylam) Türkiye şehirlerinin nüfus verileri ile simüle edilerek eklenmiştir. Proje, özellikle veri ön işleme, simülasyon, görselleştirme ve analiz adımlarına odaklanmaktadır.

🔍 Proje İçeriği
Türkiye şehirlerinin nüfus, enlem ve boylam bilgileriyle yeni veri üretimi

Nüfus yoğunluğuna göre şehir dağılımı simülasyonu

Çağrı merkezi verisinin görselleştirilmesi

Pandas, NumPy, Matplotlib, Seaborn ile analizler

📂 Kullanılan Veri Setleri
Call Center Dataset
Kaynak: Kaggle
Özellikler:

Çağrı tarihi ve süresi

Müşteri tipi

Lokasyon bilgisi (başlangıçta eksik)

Türkiye Şehir Verisi
Manuel olarak oluşturulan veri seti:

81 şehir

Enlem, boylam, nüfus bilgileri

🛠️ Kullanılan Kütüphaneler

![image](https://github.com/user-attachments/assets/cacf3a98-3e04-40e3-8d34-8feb391a1a15)


⚙️ Veri Ön İşleme
Call-Center-Dataset.xlsx dosyası Pandas ile yüklendi.

Türkiye şehirlerine ait veri çerçevesi oluşturuldu.

Her şehir için ağırlıklar (nüfusa göre) hesaplandı.

df veri setine şehir, enlem ve boylam sütunları eklendi.


![image](https://github.com/user-attachments/assets/2b3be7e0-f474-4323-b331-a5e8987664e5)



![image](https://github.com/user-attachments/assets/569167cb-1bc0-457e-943e-9d7322b84f17)






🚀 Nasıl Kullanılır?
Gerekli kütüphaneleri kurun:

bash

pip install pandas numpy matplotlib seaborn
Notebook dosyasını çalıştırın:

my_call_center.ipynb

Call-Center-Dataset.xlsx dosyasını uygun konuma yerleştirin veya yolunu değiştirin.

📌 Notlar
Şehir bilgileri gerçek veri setinde yer almıyordu, bu nedenle simüle edilmiştir.

Harita görselleştirmeleri için folium veya plotly gibi ek kütüphanelerle genişletilebilir.

👩‍💻 Yazar
Eda Aydın
Staj çalışması kapsamında geliştirilmiştir.
