# Black-Friday-Data-Analyst
### README: **Black Friday Data Analysis**

#### **Proje Adı**
Black Friday Data Analysis

---

#### **Proje Açıklaması**
Bu proje, **Black Friday** satış etkinliği sırasında toplanan müşteri ve ürün verilerini analiz etmek için oluşturulmuştur. Amaç, müşteri davranışlarını anlamak, alışveriş trendlerini belirlemek ve bu verilerden içgörüler elde etmektir. 

Proje, Kaggle'da bulunan [Black Friday Dataset](https://www.kaggle.com/code/zlemtay/black-friday-data-analysis/edit/run/208264624) kullanılarak gerçekleştirilmiştir. Çalışma, veri temizleme, görselleştirme ve temel analiz tekniklerini içermektedir.

---

#### **Kullanılan Veri Seti**
- **Veri Kaynağı:** Kaggle 
- **Veri Seti Açıklaması:**
  - **Purchase (Satın Alma):** Müşterinin yaptığı harcama miktarı.
  - **Gender (Cinsiyet):** Müşterinin cinsiyeti.
  - **Age (Yaş):** Müşteri yaş grubu.
  - **City_Category (Şehir Kategorisi):** Müşterinin yaşadığı şehir kategorisi.
  - **Stay_In_Current_City_Years (Mevcut Şehirde Kalma Süresi):** Müşterinin mevcut şehirdeki ikamet süresi.
  - **Product_ID:** Satın alınan ürün kimliği.
  - **Occupation (Meslek):** Müşterinin meslek kategorisi.
  - Diğer demografik ve satın alma bilgileri.

---

#### **Analiz Aşamaları**
1. **Veri Yükleme ve Keşifsel Veri Analizi (EDA):**
   - Eksik verilerin belirlenmesi ve temizlenmesi.
   - Veri setindeki temel istatistiksel özetler.
   - Satın alma davranışlarına genel bir bakış.

2. **Veri Görselleştirme:**
   - **Matplotlib** ve **Seaborn** kullanarak:
     - Satın alma dağılımı.
     - Cinsiyet ve yaş gruplarına göre alışveriş trendleri.
     - Şehir kategorilerine göre harcama analizi.

3. **Müşteri Segmentasyonu ve İçgörüler:**
   - Hangi yaş gruplarının daha fazla harcama yaptığı.
   - Erkek ve kadın müşterilerin alışveriş alışkanlıklarının karşılaştırılması.
   - Şehir kategorilerinin ve mesleklerin harcama üzerindeki etkisi.

---

#### **Kullanılan Araçlar ve Kütüphaneler**
- **Python**
  - **Pandas**: Veri manipülasyonu ve temizleme.
  - **NumPy**: Sayısal hesaplamalar.
  - **Matplotlib**: Veri görselleştirme.
  - **Seaborn**: Gelişmiş görselleştirme.

---

#### **Proje Yapısı**
- **black_friday_data_analysis.ipynb**: Ana çalışma dosyası, tüm kodları ve analiz süreçlerini içerir.
- **data/**: Veri setinin saklandığı dizin.
- **output/**: Görselleştirmeler ve analiz sonuçları.

---

#### **Nasıl Çalıştırılır?**
1. **Gerekli kütüphaneleri yükleyin:**
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
2. Projeyi indirin ve çalıştırın:
   ```bash
   git clone https://www.kaggle.com/code/zlemtay/black-friday-data-analysis
   cd black-friday-data-analysis
   ```
3. **Jupyter Notebook** veya **Google Colab** kullanarak `black_friday_data_analysis.ipynb` dosyasını açın ve çalıştırın.

---

#### **Sonuçlar ve İçgörüler**
- Genç yaş grupları, özellikle **26-35 yaş arası müşteriler**, en yüksek harcamayı gerçekleştiren gruptur.
- Erkek müşteriler, kadınlara kıyasla daha fazla harcama yapma eğilimindedir.
- **B Şehri kategorisi**, en fazla harcama yapılan şehir kategorisi olarak dikkat çekmektedir.

---

#### **Kaynaklar**
- Veri seti: [Black Friday Dataset on Kaggle](https://www.kaggle.com/datasets/sdolezel/black-friday)
- Python dokümantasyonu: [Python](https://www.python.org/)

---

#### **Lisans**
Bu proje, Kaggle'ın veri seti kullanım şartlarına uygun şekilde hazırlanmıştır ve yalnızca eğitim ve analiz amaçlı kullanılabilir.
