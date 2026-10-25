# TISAX® Değerlendirme Hazırlık ve GAP Analizi Çalışma Kiti

Bu açık kaynaklı çalışma seti; Avrupa ve küresel otomotiv ana üreticilerinin (OEM - Volkswagen Grubu, BMW, Mercedes-Benz, Porsche, Audi vb.) tedarik zincirinde yer alan otomotiv yan sanayi üreticileri, yazılım geliştiriciler ve mühendislik ortakları için **TISAX® (Trusted Information Security Assessment Exchange)** değerlendirme hazırlıklarını yapılandırmak amacıyla hazırlanmıştır.

Araç seti; ENX Association ve VDA (Alman Otomotiv Sanayi Derneği) tarafından yayımlanan resmî rehberler, güncel **VDA ISA 6.0.3** (ve 6.0.x serisi) kataloğu ile **ISA2027** geçiş prensipleri dikkate alınarak özgün bir hazırlık metodolojisi sunar.

---

## 🎯 Araç Setinin Amacı ve Hedef Kitle

### Kimler Kullanabilir?
- **Otomotiv Tedarikçileri (Tier-1 / Tier-2 / Tier-3):** OEM müşterilerinden TISAX etiket talebi alan parça üreticileri ve kalıp/tasarım firmaları.
- **Otomotiv Yazılım ve Mühendislik Hizmeti Verenler:** Gömülü yazılım, telematik, ECU geliştirme ve otonom sürüş test sağlayıcıları.
- **Bilgi Güvenliği ve Uyum Sorumluları:** Tesislerinde Aşama 2 (AL2) veya Aşama 3 (AL3) değerlendirmelerine hazırlanan CISO, BT yöneticileri ve kalite yöneticileri.

### Araç Seti Neyi Amaçlar?
1. Müşteri (OEM) tarafından talep edilen **Değerlendirme Hedeflerini (Assessment Objectives)** doğru tespit etmek.
2. **Değerlendirme Seviyesi (AL2 vs AL3)** ayrımını ve denetim metodolojisini netleştirmek.
3. Denetim öncesinde bağımsız bir **Boşluk (GAP) Analizi** yürüterek majör uygunsuzluk risklerini önceden belirlemek ve azaltmak.
4. Denetçiye sunulacak **Nesnel Kanıtları (Objective Evidence)** eksiksiz dosyalamak.

---

## ⚠️ Güncel Standart Sürümleri ve Geçiş Rehberi

- **Yürürlükteki Standart:** Değerlendirmelerde aktif olarak kullanılan resmî ana sürüm **VDA ISA 6.0.3** (ve ilgili 6.0.x revizyonları)'dır.
- **Sipariş Tarihi ve Geçiş Kuralları:** TISAX denetimlerinde hangi ISA kataloğunun uygulanacağı; akredite denetim sağlayıcısı ile yapılan **değerlendirme sipariş sözleşmesi tarihine (assessment ordering date)**, denetimin ilk değerlendirme veya yeniden belgelendirme durumuna ve ENX tarafından ilan edilen geçiş takvimine bağlıdır.
- **ISA2027 Hazırlığı:** ENX ve VDA tarafından yayımlanan **ISA2027** mimarisi, otomotiv tedarik zincirine erken hazırlık ve uyum imkanı tanımakta olup, ENX geçiş kuralları uyarınca 2027 yılından itibaren başlayacak yeni değerlendirme siparişleri için kademeli olarak bağlayıcı hale gelecektir.
- **1 Ocak 2025 Kural Güncellemesi:** ENX Handbook güncellemeleri uyarınca, *Test vehicles (Test araçları)* ve *Proto events (Prototip etkinlikleri)* değerlendirme hedefleri için 1 Ocak 2025 itibarıyla AL2 değerlendirme seçeneği yürürlüğe girmiştir.

---

## 📁 Depo İçeriği ve Doküman Haritası

1. 📋 **[TISAX Hazırlık Kontrol Listesi](TISAX_HAZIRLIK_KONTROL_LISTESI.md):** 11 ana başlık altında kapsam belirleme, bilgi varlıkları, üçüncü taraf bağımlılıkları, prototip güvenliği ve düzeltici faaliyetler kontrol yönergesi.
2. 📊 **[AL2 ve AL3 Değerlendirme Rehberi](AL2_AL3_DEGERLENDIRME_REHBERI.md):** Değerlendirme hedefleri ile değerlendirme seviyeleri arasındaki farklar, kanıt inceleme yöntemleri, 2025 kuralları ve ISA2027 geçiş analizi.
3. 📑 **[Nesnel Kanıt Matrisi](NESNEL_KANIT_MATRISI.md):** Değerlendirme konuları, örnek kanıt türleri, kanıt sahipleri, geçerlilik kriterleri ve aksiyon takip şablonu.
4. 🏢 **[Örnek TISAX Hazırlık Senaryosu](ORNEK_TISAX_HAZIRLIK_SENARYOSU.md):** Kurgusal bir Tier-1 otomotiv parça üreticisi senaryosu üzerinden 60–90 günlük hazırlık ve GAP kapatma planı.
5. ⚖️ **[Lisans ve Yasal Beyan](LICENSE):** MIT Açık Kaynak Lisansı ve ENX/VDA telif hakları bildirimi.

---

## 🔗 Profesyonel Danışmanlık ve Değerlendirme Hazırlığı

Tesisinizin ENX Portal kayıt sürecinden kapsam (Scope ID) tanımına, VDA ISA boşluk analizinden denetim eşliğine kadar uçtan uca çıkar çatışmasından uzak, tarafsız danışmanlık desteği almak isterseniz:

👉 **[Burak Ekşi — TISAX Danışmanlığı ve Değerlendirme Hazırlığı](https://www.burakeksi.com/hizmetler/tisax/?utm_source=github&utm_medium=readme&utm_campaign=tisax_preparation)** sayfamızı ziyaret edebilirsiniz.

---

## ⚖️ Yasal Bildirim ve Telif Hakları

- **TISAX®**, **ENX Association**'ın tescilli ticari markasıdır.
- Bu depo bağımsız bir açık kaynaklı hazırlık kılavuzudur; **ENX Association veya VDA ile hiçbir resmî ortaklığı, sponsorluğu veya akreditasyonu bulunmamaktadır.**
- TISAX sürecinde duvara asılacak klasik bir "ISO belgesi" verilmez; denetim sonucunda ENX Portalı üzerinde 3 yıl geçerli **TISAX Etiketleri (TISAX Labels)** tescil edilir.
- VDA ISA soru kataloğunun telif hakları VDA (Verband der Automobilindustrie e.V.) mülkiyetindedir. Resmî dokümanlara ve soru kataloğuna [ENX Portal](https://portal.enx.com/) üzerinden ulaşılabilir.
