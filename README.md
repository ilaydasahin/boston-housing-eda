6- Sonuç ve Öneriler
Bu adımda, elde edilen analizler ışığında ev kiraları ve piyasadaki değişkenler arasındaki ilişkiler değerlendirilerek, modelin gelişimine yönelik önerilerde bulunulacaktır.

Öneriler:

Ev Fiyat Tahmin Modelleri: Bu projede, kiralık ev fiyatlarını tahmin etmek için regresyon modelleri kullanılabilir. Özellikle Linear Regression veya Random Forest Regressor gibi modeller ile tahmin yapılabilir.

Model Seçimi: Ev fiyatlarını tahmin etmek için, karmaşık ilişkiler ve etkileşimler nedeniyle Random Forest Regressor daha iyi sonuç verebilir. Bu model, doğrusal olmayan ilişkileri ve etkileşimleri modelleyebilir.

Bu proje, bir "House Rent Dataset" kullanarak ev kiralarını tahmin etmeye yönelik keşifsel veri analizi (EDA) yapmayı amaçlamaktadır. Proje, veri setinin analizini yaparak, ev kiralarıyla ilgili önemli öngörüler elde etmeyi, görselleştirme teknikleri kullanarak veriyi daha iyi anlamayı ve son olarak bir tahmin modeli geliştirmeyi hedeflemektedir.

Kullanılan Teknolojiler
Python
Pandas: Veri işleme ve analizi için.
Numpy: Sayısal hesaplamalar için.
Matplotlib ve Seaborn: Veri görselleştirme için.
Scikit-learn: Modelleme ve makine öğrenmesi için.
Proje Adımları
1. Veri Seti Yükleme ve Ön İnceleme
Projenin ilk adımında, veri seti yüklenmiş ve içeriği kontrol edilmiştir. Veri seti, evlerin kiralarını, özelliklerini ve bulunduğu şehirlere dair bilgileri içermektedir.

İlk olarak, veri seti Pandas kütüphanesi ile okunur.
Veri setinin ilk 5 satırı ve temel özellikleri görüntülenir.
Veri setinde bulunan eksik değerler ve duplikalar kontrol edilir.
2. Keşifsel Veri Analizi (EDA)
Keşifsel veri analizi adımında, ev kiraları, evin bulunduğu şehirler, mobilya durumu gibi özellikler görselleştirilmiştir.

Ev kiralarının dağılımı: Ev kiralarının dağılımı ve histogramları çizilmiştir.
Şehir bazında ev sayısı: Hangi şehirlerde daha fazla kiralık ev bulunduğu görselleştirilmiştir.
Furnishing durumu: Mobilyalı ve mobilyasız evlerin sayısı analiz edilmiştir.
3. Veri Temizleme ve Ön İşleme
Veri setindeki eksik değerler, duplikalar ve gereksiz sütunlar temizlenmiştir. Ayrıca kategorik veriler, sayısal verilere dönüştürülmüştür.

Eksik veriler: Veri setindeki eksik değerler kontrol edilmiştir ve gerekli işlemler yapılmıştır.
Kategori dönüşümü: Kategorik sütunlar, sayısal verilere dönüştürülmüştür.
4. Görselleştirme
Veri setindeki temel değişkenlerin dağılımını ve ilişkilerini görselleştirmek için Matplotlib ve Seaborn kullanılmıştır.

Ev Kiraları: Ev kiralarının genel dağılımı incelenmiştir.
Şehir Bazında Ev Sayısı: Kiralık evlerin hangi şehirlerde yoğunlaştığı görselleştirilmiştir.
Furnishing Durumu: Mobilyalı ve mobilyasız evlerin sayısı grafikle gösterilmiştir.
5. Sonuçlar ve Öneriler
Veri analizi sonrası elde edilen sonuçlarla, ev kiralarını etkileyen faktörler hakkında bilgi edinilmiştir. Bu bilgiler, model geliştirme aşamasında kullanılabilir.

Ev Kirası Tahmin Modelleri: Ev kiralarını tahmin etmek için regresyon modelleri kullanılabilir. Linear Regression ve Random Forest Regressor gibi modeller tavsiye edilmektedir.
Faktörlerin Etkisi: Şehir, evin büyüklüğü, kat sayısı ve mobilya durumu gibi faktörlerin kiralar üzerinde önemli etkileri bulunmaktadır.

https://www.kaggle.com/code/klaydaahin/house-dataset
