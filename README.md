# 🦠 CORD-19 Research Challenge - COVID-19 Open Research Dataset

Bu proje, Allen Institute for AI tarafından yayımlanan ve COVID-19 ile ilgili 500.000'den fazla akademik makaleyi içeren **CORD-19 (COVID-19 Open Research Dataset)** veri seti üzerinde gerçekleştirilen analizleri ve doğal dil işleme (NLP) uygulamalarını içermektedir.

## 📘 Proje Hakkında

CORD-19 veri seti, COVID-19, SARS-CoV-2 ve ilgili virüsler üzerine yapılan bilimsel araştırmalardan oluşur. Bu proje kapsamında yapılan çalışmalar:

- Veri keşfi ve istatistiksel özetleme (EDA)
- Anahtar kelime analizi
- Makale özetleme (text summarization)
- Temel NLP işlemleri (tokenization, stopword removal, stemming, vs.)
- Yayınların yıllara göre dağılımı
- En çok katkı sağlayan dergiler ve kurumlar
- TF-IDF ve benzeri tekniklerle metin temsili
- (Opsiyonel) Belge kümelenmesi ya da konu modelleme (LDA)

## 🧪 Kullanılan Teknikler

- **Pandas**, **NumPy** – Veri işleme
- **NLTK**, **spaCy**, **Scikit-learn** – NLP görevleri
- **matplotlib**, **seaborn**, **plotly** – Görselleştirme
- **gensim**, **BERTopic**, **LDA** – Konu modelleme (opsiyonel)
- **tqdm**, **json**, **os** – Yardımcı işlemler

## 📊 Veri Kümesi

- **Kaynak:** [CORD-19 Dataset on Kaggle](https://www.kaggle.com/datasets/allen-institute-for-ai/CORD-19-research-challenge)

  

## 💡 Potansiyel Kullanım Alanları

- Literatür taraması ve bilimsel analiz
- Otomatik özetleme modelleri
- Bilgi çıkarımı (entity extraction, relationship mining)
- Akademik arama motorları geliştirme
- COVID-19 ile ilgili konu modelleme

## 📈 Sonuçlar

CORD-19 veri seti üzerinde yapılan analizler, COVID-19 ve ilişkili virüsler hakkında yayımlanmış bilimsel araştırmaların zamana, konuma, yazar katkısına ve içerik temalarına göre kapsamlı bir biçimde dağıldığını göstermektedir.

- **Yıllara göre yayın dağılımı**, 2020 yılı itibariyle hızlı bir artış göstermekte ve pandeminin bilimsel etkisini açıkça yansıtmaktadır.
- **En aktif yayıncılar** arasında medikal dergiler ve açık erişimli kaynaklar öne çıkmaktadır.
- **Anahtar kelime ve konu modelleme analizleri**, özellikle aşı geliştirme, bulaşma yolları, varyantlar, semptomlar ve tedavi yaklaşımlarının literatürde sıkça işlendiğini ortaya koymuştur.
- **Özetleme ve metin temizleme süreçleri**, makale içeriklerinin NLP modellerine uygun hale getirilmesini sağlamıştır.
- Yapılan görselleştirmeler sayesinde literatürün hangi yönlerde yoğunlaştığı daha net bir biçimde gözlemlenebilmiştir.

Bu analiz, sadece veri keşfi değil, aynı zamanda COVID-19 özelinde **bilimsel bilgi madenciliği** açısından da güçlü bir temel sunmaktadır. CORD-19, NLP ve bilgi çıkarımı uygulamaları için zengin ve gerçek dünya temelli bir kaynak olmayı sürdürmektedir.
