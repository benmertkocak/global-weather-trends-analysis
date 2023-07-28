# Global Weather Trends Analysis

Bu proje, Kaggle platformunda bulunan "Global Weather Trends" adlı veri kümesi üzerinde yapılan analizleri içerir. Bu veri kümesi, dünya genelinde farklı bölgelerin hava durumu verilerini içermektedir. Analizler, Python programlama dili ve Pandas, Matplotlib gibi kütüphaneler kullanılarak gerçekleştirilmiştir.

## Dosyalar ve Sütunlar

- `weather_dataset.csv`: Ana veri kümesi dosyası. İçerisinde aşağıdaki sütunlar bulunmaktadır:

    - `index`: Veri giriş indeksi
    - `current_time`: Şu anki saat
    - `crawled_at`: Verilerin çekildiği zaman
    - `pressure`: Basınç değeri
    - `country`: Ülke adı
    - `wind_direction`: Rüzgar yönü
    - `sky`: Gökyüzü durumu
    - `uniq_id`: Tekil kimlik numarası
    - `visibility`: Görüş mesafesi
    - `temparature`: Sıcaklık değeri
    - `dev_point`: Çiğ nokta sıcaklığı
    - `place`: Yer adı
    - `location`: Coğrafi konum
    - `data_category`: Veri kategorisi
    - `latest_report`: Son rapor zamanı
    - `wind`: Rüzgar hızı
    - `forecast`: Hava durumu tahmini
    - `feels_like`: Hissedilen sıcaklık
    - `index_date_format`: Tarih formatı

## Analizler

Proje içerisinde yapılan analizler aşağıda sıralanmıştır:

1. **Bölgesel Karşılaştırmalar:** Veri kümesinde yer alan bölgelerin sıcaklık değişimleri zaman içinde analiz edilmiştir.
2. **Ülke Ortalama Sıcaklıkları:** Türkiye, Amerika, Hindistan, Rusya, Çin ve Suudi Arabistan ülkelerinin yıllara göre ortalama sıcaklık değerleri görselleştirilmiştir.
3. **Ülkeler Arasındaki Sıcaklık Farkları:** Seçilen ülkeler arasındaki ortalama sıcaklık farkları hesaplanmıştır.
4. **Türkiye ile Karşılaştırma:** Diğer ülkelerin sıcaklık değerleri, Türkiye ile karşılaştırılarak farklar belirlenmiştir.

## Nasıl Kullanılır?

Bu proje, Python programlama dili kullanılarak gerçekleştirilmiştir. Analizleri çalıştırmak ve görselleştirmeleri görmek için aşağıdaki adımları takip edebilirsiniz:

1. Python yüklü olmalıdır. Eğer yüklü değilse, Python'ın en son sürümünü [buradan](https://www.python.org/downloads/) indirebilir ve yükleyebilirsiniz.

2. Gerekli kütüphaneleri yüklemek için aşağıdaki komutları terminalde veya komut satırında çalıştırın:
   
   ```bash
   pip install pandas matplotlib
