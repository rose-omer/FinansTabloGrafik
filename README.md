# Hisse Senedi Veri Görselleştirme ve Analiz Aracı

Bu proje, Streamlit kullanarak geliştirilen bir hisse senedi veri görselleştirme aracıdır. Kullanıcılar, belirli bir tarih aralığı için seçilen hisse senedinin kapanış fiyatlarını grafik üzerinde görüntüleyebilir ve verileri Excel formatında indirebilirler.

## Özellikler

- **Hisse Senedi Seçimi**: Kullanıcılar Tesla, Apple, Nvidia, Microsoft gibi popüler hisse senetlerinden birini seçebilirler.
- **Tarih Aralığı Seçimi**: Başlangıç ve bitiş tarihleri girilerek, belirli bir dönemin hisse senedi verilerine ulaşılabilir.
- **Veri Görselleştirme**: Kapanış fiyatları bir çizgi grafik ile gösterilir.
- **Excel Olarak İndirme**: Kullanıcılar, çekilen hisse senedi verilerini Excel formatında indirebilirler.

## Gereksinimler

Bu projeyi çalıştırabilmek için aşağıdaki kütüphanelere ihtiyacınız olacak:

- `streamlit`: Web uygulamasını çalıştırmak için.
- `yfinance`: Hisse senedi verilerini çekmek için.
- `pandas`: Veri analizi ve işleme için.
- `xlsxwriter`: Excel dosyası oluşturmak için.

### !!!!!! ÖNEMLİ !!!!!!!
Streamlit Uygulamasını Başlatma:

Streamlit uygulamasını başlatmak için aşağıdaki komutu terminale yaz ve enter

- streamlit run app.py
