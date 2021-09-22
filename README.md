# Prediction of Traffic Density

**Kodluyoruz - Data Science for Public Good (28.03.2020-20.06.2020)**

İBB iş birliğiyle yürütülen programda İBB'den aldığımız **trafik duyuruları** ve **trafik yoğunluğu** veri setinden faydalanarak trafik yoğunluğunu tahmin eden model geliştirdik. 


![Resim1](https://user-images.githubusercontent.com/17860575/134295688-6a00b374-aa87-4fb7-9dde-bdb1d580609a.png)

Esenler, Beşiktaş, Kağıthane bölgeleri için Ocak-Haziran 2020 tarihlerini kapsayan trafik yoğunluğu ve trafik duyuruları veri setleri kullanıldı. Hedef değişkeni belirlemek için; trafik duyurusuna ait hızın medyanı eşik değer olarak alındı. Buna göre hız saatte 28 km den azsa; trafik yoğunluğu var, fazlaysa; yoğunluk yok, şeklinde sınıflandırıldı. 
İki veri setinde  konum ve zaman bilgisi eşleşen satırlarla oluşturulmuş makine öğrenimi modelinde, gelecekte oluşacak trafik yoğunluğu bilgisi Random Forest, XGBoost ve Logistic Regression algoritmaları ile testi sonucu % 75 doğru tahmin yaptığı sonucuna ulaşıldı. 

<img width="943" alt="trafik duyuruları" src="https://user-images.githubusercontent.com/17860575/134297725-0248f825-44d5-4120-8fb5-1362d392da55.png">





# TEAM
- Elif Kurt
- Gizem Göker
- Fazile Akça
- Betül Çelebi
- Berk Sudan
