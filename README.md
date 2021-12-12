# Yapay Zeka ve Öğrenen Algoritmalar Proje
Karma Döngü Enerji Santrali için elektrik enerjisi çıkışını tahmin etmek için Lineer Regresyon, Polinom
Regresyon ve Rprop MLP Learner(Yapay Sinir Ağları) modellerinin kullanılmıştır. Bu araştırmada
kullanılan makine öğrenme yöntemleri akıllı şehirlerde kullanılabilecek bir tesis olup, kullanılan
algoritmanın performansları değerlendirilmiştir.
<br/>

# Veri Kümesi Bilgileri
Veri seti, santral tam yükte çalışmaya ayarlandığında 6 yıl boyunca (2006-2011) bir Kombine Çevrim
Santralinden toplanan 9568 veri noktasını içerir. Özellikler, tesisin net saatlik elektrik enerjisi çıkışını (PE)
tahmin etmek için saatlik ortalama ortam değişkenlerinden Sıcaklık (AT), Ortam Basıncı (AP), Bağıl Nem
(RH) ve Egzoz Vakumundan (V) oluşur. Elektrik, tek çevrimde birleştirilen gaz ve buhar türbinleri tarafından
üretilir. Üç ortam değişkeni gaz türbininin performansını etkiler ve egzoz vakumu buhar türbininin
performansını etkiler. Veriler, her saniye ortam değişkenlerini kaydeden tesis çevresinde bulunan çeşitli
sensörlerden alınan saatlik ortalamalardan oluşur.

# Veri Bilgileri ( Değişkenler normalizasyon yapılmadan verilmiştir. )

- Avg Temperature (AT) in the range 1.81°C and 37.11°C,
- Ambient Pressure (AP) in the range 992.89–1033.30 millibar,
- Relative Humidity (RH) in the range 25.56% to 100.16%
- Exhaust Vacuum (V) in the range 25.36–81.56 cm Hg
- Net hourly electrical energy output (PE) 420.26–495.76 MW

# Knime ile analiz

```sh
$ Knime uygulamasını açın.
$ File/Import Knıme Workflow...
$ Dosya klasörünü seçerek ilerleyin.
```