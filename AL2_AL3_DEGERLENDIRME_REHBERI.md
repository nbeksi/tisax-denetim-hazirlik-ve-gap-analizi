# TISAX® AL2 ve AL3 Değerlendirme Seviyeleri Rehberi

TISAX değerlendirmelerinde en sık karşılaşılan hatalardan biri, **Değerlendirme Hedefi (Assessment Objective)** ile **Değerlendirme Seviyesi (Assessment Level - AL)** kavramlarının birbirine karıştırılmasıdır.

Bu rehber; resmî **ENX TISAX Participant Handbook** kurallarına dayanarak AL2 ve AL3 arasındaki metodolojik farkları, 1 Ocak 2025 kural güncellemelerini ve ISA2027 geçişinin etkilerini açıklamaktadır.

---

## 1. Değerlendirme Seviyesi (AL) Nedir?

Değerlendirme Seviyesi (Assessment Level), denetimin **ne kadar derinlemesine ve hangi yöntemle** gerçekleştirileceğini belirler:

- **AL1 (Assessment Level 1):** Yalnızca kurum içi öz değerlendirmedir. Akredite denetim firması dahil edilmez ve sonuçlar ENX Portalı üzerinde TISAX Etiketi olarak paylaşılamaz.
- **AL2 (Assessment Level 2 - Plausibility Check):** Akredite denetim sağlayıcısı tarafından gerçekleştirilen **inandırıcılık kontrolüdür (plausibility check)**. Temel olarak uzaktan video konferans mülakatları ve kanıt incelemeleriyle yürütülür.
- **AL3 (Assessment Level 3 - Comprehensive Verification):** Akredite denetim sağlayıcısının tesisinize bizzat gelerek gerçekleştirdiği **kapsamlı yerinde doğrulamadır (on-site audit)**.

---

## 2. AL2 ve AL3 Yöntem Farklılıkları Karşılaştırması

| Özellik | AL2 (Assessment Level 2) | AL3 (Assessment Level 3) |
| :--- | :--- | :--- |
| **Denetim Lokasyonu** | Tamamen uzaktan (Webex, Teams vb.) | **Bizzat yerinde (On-site)** tesis ziyareti |
| **Kanıt Doğrulama Şekli** | Ekran paylaşımı ve sunulan belgelerin inandırıcılık analizi | Doğrudan sistem başında, sahada ve fiziksel ortamda doğrulama |
| **Mülakat Kapsamı** | Süreç ve sistem sorumluları ile çevrim içi görüşmeler | Operatörler, güvenlik personeli ve yönetimle yüz yüze mülakat |
| **Tesis Turu / Fiziksel Denetim** | Genellikle talep edilmez veya canlı kamera turuyla sınırlıdır | Sunucu odası, üretim hattı, çitler ve AR-GE odalarının fiziksel teftişi |
| **Maliyet ve Süre** | Daha düşük maliyet, daha hızlı planlama | Yerinde harcanan adam-gün ve lojistik masrafları nedeniyle daha yüksek bütçe |

---

## 3. Değerlendirme Hedefleri ile AL Eşleşmesi

Değerlendirme Seviyesini kurum kendi keyfine göre seçemez. Seçilecek AL düzeyi, müşterinin (OEM) talep ettiği **Değerlendirme Hedefine (Assessment Objective)** bağlıdır:

| Değerlendirme Hedefi (Assessment Objective) | Asgari Zorunlu AL | Denetim Yöntemi |
| :--- | :---: | :--- |
| **Info High** (Yüksek Koruma İhtiyacı) | **AL2** | Uzaktan inandırıcılık denetimi |
| **Info Very High** (Çok Yüksek Koruma İhtiyacı) | **AL3** | **Zorunlu yerinde (On-site)** denetim |
| **Availability High** | **AL2** | Uzaktan inandırıcılık denetimi |
| **Availability Very High** | **AL3** | **Zorunlu yerinde (On-site)** denetim |
| **Proto Parts** (Prototip Parçalar) | **AL3** | **Zorunlu yerinde (On-site)** denetim |
| **Data Protection** (GDPR / KVKK) | **AL2** | Uzaktan inandırıcılık denetimi |

---

## 4. Kritik Güncelleme: 1 Ocak 2025 Kural Değişikliği

ENX TISAX Participant Handbook'ta yapılan ve **1 Ocak 2025 itibarıyla yürürlüğe giren** düzenleme kapsamında:

> **Test Vehicles ve Proto Events Hedeflerinde AL2 Esnekliği:**  
> Daha önce belirli prototip ve araç senaryolarında mutlaka AL3 (yerinde denetim) zorunluluğu aranırken, 1 Ocak 2025'ten itibaren **"Test vehicles" (Test araçları)** ve **"Proto events" (Prototip etkinlikleri)** hedefleri için şartları sağlayan tedarikçilere **AL2 (uzaktan inandırıcılık kontrolü)** ile değerlendirilme imkanı tanınmıştır.  
> *Not:* Fiziksel prototip parçalar (Proto parts) üreten tesisler için AL3 yerinde denetim zorunluluğu devam etmektedir.

---

## 5. Sık Yapılan Yanlış Seçimler ve Riskler

1. **Gereğinden Yüksek Hedef Seçmek (Over-scoping):**  
   Müşterisi yalnızca "Info High" talep ettiği halde prestij amacıyla "Info Very High" seçen tedarikçiler, gereksiz yere AL3 yerinde denetim maliyetine ve aşırı katı fiziksel bariyer şartlarına katlanmak zorunda kalır.
2. **AL2'yi Basit Bir "Form Doldurma" Sanmak:**  
   AL2 uzaktan yapılsa dahi denetçi rastgele örnekleme yapar; ekran paylaşımıyla canlı sistem konfigürasyonlarını ve Active Directory loglarını inceler. İnandırıcı bulunmayan kanıtlar majör uygunsuzluğa dönüşür.
3. **Kapsam Dışı Tesisleri Kapsama Almak:**  
   OEM projesinde yer almayan depolar veya ikinci fabrikalar kapsama dahil edildiğinde denetim süresi ve risk katlanarak artar.

---

## 6. VDA ISA Sürümleri ve ISA2027 Geçişinin Değerlendirme Hazırlığına Etkisi

- **Güncel Katalog:** Değerlendirmelerde aktif olarak kullanılan en güncel standart ana sürümü **VDA ISA 6.0.3** (ve ilgili 6.0.x revizyonları)'dır.
- **Sipariş Tarihi ve Uygulanabilirlik Kuralı:** Bir denetimde hangi katalog sürümünün geçerli olacağı; akredite denetim sağlayıcısı ile akdedilen **değerlendirme sipariş sözleşmesi tarihine (assessment ordering date)**, değerlendirmenin ilk denetim veya yeniden belgelendirme durumuna ve ENX geçiş yönergelerine göre belirlenir. Yürürlükteki bir sipariş kapsamında başlayan denetimler, sözleşme tarihindeki geçerli sürüm şartlarına göre sonuçlandırılır.
- **ISA2027 Geçişi:** ENX ve VDA tarafından duyurulan **ISA2027** mimarisi, otomotiv tedarikçilerine yeni nesil güvenlik kontrollerine uyum sağlamaları için bir geçiş penceresi tanımaktadır. ENX takvimine göre 2027 yılından itibaren başlayacak yeni değerlendirme siparişlerinde ISA2027 kademeli olarak zorunlu standart haline gelecektir.
- **Hazırlık Stratejisi:** Tedarikçiler mevcut değerlendirme süreçlerini VDA ISA 6.0.3 şartlarına göre planlarken, 3 yıllık TISAX etiket döngüsünün devamlılığı için ISA2027 ile gelen güncel bulut ve tedarik zinciri kontrollerini şimdiden yönetim sistemlerine dahil etmelidir.
