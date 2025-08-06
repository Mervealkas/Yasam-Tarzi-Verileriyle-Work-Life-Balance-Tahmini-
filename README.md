# Yasam-Tarzi-Verileriyle-Work-Life-Balance-Tahmini-

-Proje Özeti-
Bu proje, bireylerin yaşam tarzı alışkanlıklarına göre iş-yaşam dengesi skorlarını tahmin etmeyi amaçlamaktadır. 15.000'den fazla kişinin stres seviyesi, uyku süresi, sosyal çevresi gibi veriler kullanılarak tahmin modelleri geliştirilmiştir.

-Amaç-
Yaşam tarzı verileriyle bireylerin iş-yaşam dengesi skorlarını tahmin etmek
Farklı regresyon algoritmalarını karşılaştırmak
Ensemble yaklaşımı ile daha dengeli tahminler elde etmek

-Kullanılan Teknikler-
Veri ön işleme (eksik değer tamamlama, one-hot encoding)
Model karşılaştırması (Linear Regression, Random Forest, XGBoost)
5 katlı çapraz doğrulama (cross-validation)
Ensemble model (ortalama tahmin)

Görselleştirme (matplotlib ile tahmin vs gerçek skorlar)

-Sonuçlar-
Model	Mean Squared Error (MSE)
Linear Regression	A değeri
Random Forest	B değeri
XGBoost	C değeri
Ensemble (Ortalama)	D değeri
XGBoost en düşük hata ile en başarılı model olurken, ensemble yaklaşımı daha dengeli sonuçlar sundu.
