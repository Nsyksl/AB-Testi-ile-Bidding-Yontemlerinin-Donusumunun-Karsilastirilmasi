# Bombabomba.com A/B Testi Analizi
Bu proje, bombabomba.com adlı bir müşteri için gerçekleştirilen A/B testinin sonuçlarını analiz etmeyi amaçlamaktadır. 
Test, mevcut "maximum bidding" teklif verme türüne alternatif olarak yeni bir teklif türü olan "average bidding"i değerlendirmek için yapılmıştır. 
Test, Purchase metriğini nihai başarı ölçütü olarak kullanmaktadır.

# İş Problemi
Bombabomba.com, Facebook'un average bidding özelliğini test etmek amacıyla bir A/B testi yürütmüştür.
Bu testin sonuçlarına dayanarak, average bidding'in maximum bidding'den daha fazla dönüşüm getirip getirmediğini belirlemek istemektedir.

Veri Seti
Bu analiz için kullanılan veri seti, bombabomba.com'un web sitesiyle ilgili bilgileri içermektedir. Veri seti, kontrol grubu ve test grubu olmak üzere iki ayrı veri setinden oluşmaktadır. 
Kontrol grubuna Maximum Bidding, test grubuna Average Bidding uygulanmıştır. Veri seti, "ab_testing.xlsx" adlı Excel dosyasının ayrı sayfalarında bulunmaktadır.



# Veri Hazırlama:

* Kontrol ve test gruplarını birleştirin.

# İstatistiksel Analiz:
* İki grup arasında istatistiksel olarak anlamlı bir fark olup olmadığını belirlemek için uygun hipotez testini seçin ve uygulayın.

# Sonuçlar ve Yorumlar:

* Hipotez testinin sonuçlarını yorumlayın.
* Average bidding'in maximum bidding'den daha fazla dönüşüm getirip getirmediğini belirleyin.
* Test sonuçlarına dayanarak müşteriye öneriler sunun.

# Kurulum
* Gerekli Kütüphaneleri Yükleme:

  Analizi gerçekleştirmek için gerekli olan Python kütüphaneleri, modülleri ve fonksiyonlarını (örneğin Pandas, Scipy, nttest_1samp, shapiro, levene, ttest_ind, mannwhitneyu) yükleyin.
