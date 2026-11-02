# Periodontal Chart-Voice

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23881985.svg)](https://doi.org/10.5281/zenodo.23881985)

Sesli komutlarla doldurulan periodontal chart. Hekim muayene ederken ölçümleri söyler, chart kendiliğinden dolar; muayene bitince chart yazdırılır veya bilgisayara kaydedilir. Ayrıca bir asistanın not almasına gerek kalmaz.

**Uygulamayı aç:** https://yakupkaankalayciperio.github.io/periodontal-chart-voice/

Created by **Yakup Kaan Kalaycı, DDS, PhD**

*English summary below.*

## Özellikler

- FDI numaralandırması, her diş için 6 bölge (bukkal ve palatinal/lingual)
- Sondlama cep derinliği, klinik ataçman kaybı, gingival marjin, plak indeksi ve gingival indeks
- Diş başına sondlamada kanama (pozitif / negatif) ve furkasyon (1–4)
- Gingival marjin ve cep tabanını gösteren diş grafiği
- Özet: ortalama cep derinliği, ortalama klinik ataçman kaybı, kanama yüzdesi, plak ve gingival indeks ortalamaları, 3 mm'den derin cep sayısı
- Tek sayfaya sığan A4 yatay çıktı; yazdırma penceresinden PDF olarak da kaydedilebilir
- Kaydedilen dosya açıldığında chart dolu haliyle gelir
- Kurulum gerektirmez: tek bir HTML dosyasıdır

## Gereksinimler

- **Google Chrome** veya **Microsoft Edge** (sesli giriş diğer tarayıcılarda çalışmaz)
- Mikrofon ve internet bağlantısı (konuşma tanıma tarayıcının çevrimiçi servisini kullanır)
- Sesli giriş olmadan klavyeyle de veri girilebilir

## Kullanım

1. **Mikrofonu aç** butonuna basın ve tarayıcının mikrofon iznini onaylayın.
2. **"Chart'ı başlat"** deyin.
3. Bir ölçüm komutu söyleyin, ardından değerleri sırayla söyleyin (ör. "üç iki üç üç dört üç").

| Sesli komut | Değerler |
|---|---|
| "Chart'ı başlat" | — |
| "Sondlamada kanamayı yaz" | pozitif / negatif (diş başına) |
| "Cep derinliğini yaz" | mm |
| "Klinik ataçman kaybı seviyesini yaz" | mm |
| "Gingival marjini yaz" | mm (resesyon için "eksi 2") |
| "Plak indexi yaz" | 0–3 |
| "Gingival indexi yaz" | 0–4 |
| "Furkasyon yaz" | 1–4 |
| "diş 36'ya geç" | Belirtilen dişe geçer |
| "36 nolu diş eksik" | Dişi eksik olarak işaretler, sırada atlanır |

Ek komutlar: "geri al", "atla", "dur", "devam". Bir ölçüm belirli bir dişten başlatılabilir: "14 numaralı dişin klinik ataçman kaybı".

### Yazma sırası

Dişler: 18→11, 21→28, 38→31, 41→48. Her dişte önce bukkal, sonra palatinal/lingual yüzeyler yazılır:

- 18–11 ve 38–31: disto → mid → mesio
- 21–28 ve 41–48: mesio → mid → disto

### Kaydetme ve yazdırma

- **Kaydet:** Chart, hasta adı ve tarihle adlandırılmış bir `.html` dosyası olarak İndirilenler klasörüne iner. Bu dosya açıldığında chart dolu haliyle gelir; **Aç** butonuyla da yüklenebilir.
- **Yazdır:** Chart tek bir A4 yatay sayfaya sığdırılır.

## Veri gizliliği

Chart verileri hiçbir sunucuya gönderilmez; yalnızca kullanılan tarayıcıda ve kaydedilen dosyalarda tutulur. **Sesli giriş açıkken konuşma, yazıya çevrilmesi için tarayıcının konuşma tanıma servisine (Chrome'da Google, Edge'de Microsoft) gönderilir.** Hasta adı gibi kimlik bilgilerini sesle söylemeyin; bunları klavyeyle girin.

## Sorumluluk reddi

Bu yazılım bir dokümantasyon aracıdır; teşhis koymaz, tedavi önermez ve tıbbi cihaz olarak onaylanmamıştır. Girilen değerlerin doğruluğundan kullanan hekim sorumludur. Yazılım "olduğu gibi" sunulur; hiçbir garanti verilmez.

## Atıf

Bu yazılımı kullanırsanız lütfen şu şekilde atıf yapın:

Kalaycı, Y. K. (2026). *Periodontal Chart-Voice* [Bilgisayar yazılımı]. Zenodo. https://doi.org/10.5281/zenodo.23881985

Bu DOI tüm sürümleri kapsar ve her zaman en son sürümü gösterir. Belirli bir sürüme atıf için o sürümün DOI'sini kullanın (v1.0.0: [10.5281/zenodo.23881986](https://doi.org/10.5281/zenodo.23881986)).

## Lisans

© 2026 Yakup Kaan Kalaycı · [Creative Commons Atıf-GayriTicari-AynıLisanslaPaylaş 4.0 Uluslararası (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.tr)

- **Atıf:** Kullanırken veya paylaşırken yazara atıf yapılmalı ve lisansa bağlantı verilmelidir.
- **GayriTicari:** Ticari amaçlarla kullanılamaz.
- **AynıLisanslaPaylaş:** Değiştirilmiş sürümler aynı lisansla paylaşılmalıdır.

**Ek izin — klinik kullanım:** Diş hekimleri, hekimler ve diğer sağlık profesyonelleri ile çalıştıkları klinik, hastane ve kurumlar (ücretli hizmet veren özel muayenehaneler dahil) bu yazılımı hasta bakımı, klinik kayıt, eğitim ve araştırma amacıyla ücretsiz kullanabilir. Yazılımın satılması veya ücretli bir ürün ya da hizmetin parçası olarak sunulması yazarın iznini gerektirir.

Ayrıntılar için [LICENSE](LICENSE) dosyasına bakın.

---

## English summary

**Periodontal Chart-Voice** ([open the app](https://yakupkaankalayciperio.github.io/periodontal-chart-voice/)) is a periodontal chart that is filled in by voice (Turkish speech recognition). The clinician dictates measurements while examining the patient; the chart can then be printed or saved.

- FDI numbering, 6 sites per tooth: probing depth, clinical attachment loss, gingival margin, plaque index, gingival index; bleeding on probing per tooth; furcation (1–4)
- Runs in Google Chrome or Microsoft Edge as a single HTML file; no installation
- Chart data never leaves the browser except as files you save. While voice input is on, speech is sent to the browser's speech-recognition service (Google in Chrome, Microsoft in Edge).
- This is a documentation tool. It does not diagnose and is not an approved medical device. The clinician is responsible for the accuracy of all entries.

Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) (Attribution-NonCommercial-ShareAlike 4.0 International), with an additional permission: dentists, physicians and other healthcare professionals, and their clinics, hospitals and institutions (including private, fee-charging practices), may use the software free of charge for patient care, clinical documentation, teaching and research. Selling it or offering it as part of a paid product or service requires the author's permission. See [LICENSE](LICENSE). Created by Yakup Kaan Kalaycı, DDS, PhD.

Cite as: Kalaycı, Y. K. (2026). *Periodontal Chart-Voice* [Computer software]. Zenodo. https://doi.org/10.5281/zenodo.23881985
