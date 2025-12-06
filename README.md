# Finansal-Hisse-Analizi-AAPL-MSFT-Kıyaslama

# API Tabanlı Finansal Veri Analizi: AAPL vs MSFT Kıyaslaması

##  Proje Amacı
Bu proje, finansal piyasalardaki gerçek zamanlı verilerin **API** (Yahoo Finance) üzerinden çekilmesi, Pandas ile temizlenmesi ve analiz edilmesi sürecini göstermektedir. Temel hedef, son 5 yıllık dönemde Apple (AAPL) ve Microsoft (MSFT) hisselerinin yatırım performansını, risk ve getiri metrikleri üzerinden kıyaslayarak bir yatırım stratejisi önerisi sunmaktır.

##  Kullanılan Teknolojiler
* Python (Colab ortamında)
* Pandas (Veri Manipülasyonu ve Hesaplama)
* Matplotlib (Görselleştirme)
* **yfinance Kütüphanesi (Yahoo Finance API Entegrasyonu)**

---

## Analiz Metrikleri ve Bulgular

Verilerin analiz edilmesiyle elde edilen temel risk ve getiri metrikleri şunlardır:

| Metrik | AAPL (Apple) | MSFT (Microsoft) | Yorum (YBS) |
| :--- | :--- | :--- | :--- |
| **Ortalama Günlük Getiri** | **0.082423 %** | **0.081199 %** | Yüksek getirili hisse, teorik olarak daha iyi kazandırır. |
| **Oynaklık (Risk)** | **1.75 %** (Lütfen Kendi Çıktınızla Değiştirin) | **1.55 %** (Lütfen Kendi Çıktınızla Değiştirin) | Yüksek oynaklık, hissenin daha sık ve sert fiyat dalgalanması yaşadığı anlamına gelir. |

**Gözlem:** Ortalama günlük getiri açısından AAPL (%0.0824) bir miktar öndeyken, MSFT (%0.0811) daha az oynak (daha az riskli) bir profil çizmektedir. Bu, AAPL'nin biraz daha yüksek kazanç potansiyeli sunarken, MSFT'nin daha istikrarlı bir yatırım olduğunu gösterir.

---

## Performans Kıyaslaması (Zaman Serisi Analizi)

### ![AAPL vs MSFT Kıyaslama Grafiği](https://i.ibb.co/F4Ds7mvP/graf-k-nd-r.png)
*Bu grafik, kod çıktısı olarak üretilmiştir.*


**Açıklama:** Grafik, her iki hisseye de 5 yıl önce 100 birim yatırım yapılmış olsaydı, bu yatırımın bugün ulaştığı değeri göstermektedir.

**Gözlem (Grafik):**
Grafik incelendiğinde, **MSFT (Microsoft)** hissesinin özellikle son 2 yılda **AAPL'ye göre daha istikrarlı ve hızlı bir büyüme trendi** yakalayarak toplam getiri açısından daha yüksek bir noktaya ulaştığı görülmektedir. Bu, MSFT'nin pazar payını ve yatırımcı güvenini artırdığını gösterir.

---

##  Stratejik Karar Önerisi

Bu analizden elde edilen bulgular, bir portföy yöneticisi için aşağıdaki stratejik kararları desteklemektedir:

1.  **Risk İştahına Göre Tercih:**
    * **Yüksek Getiri ve İstikrar Arayanlar:** MSFT, hem oynaklıkta rekabetçi olması hem de son 5 yıldaki toplam getiride liderlik etmesi nedeniyle ana hedef olmalıdır.
    * **Alternatif Getiri Arayanlar:** AAPL, portföyü çeşitlendirmek ve Microsoft'a özgü riskleri dengelemek için portföye eklenmelidir.
2.  **Portföy Çeşitlendirmesi:** Finansal analizin temel kuralı, riski dağıtmaktır. Bu nedenle, iki güçlü teknoloji hissesini de içeren **çeşitlendirilmiş bir portföy**, en uygun ve güvenli yatırım stratejisidir.
3.  **API Kullanımının Değeri:** Bu proje, **API entegrasyonunun**, yöneticilere hızlı, güncel ve karar destek sistemlerine doğrudan entegre edilebilir analitik içgörüler sunma gücünü kanıtlamaktadır.

