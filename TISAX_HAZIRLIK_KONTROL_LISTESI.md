# TISAX® Hazırlık ve Öz Değerlendirme Kontrol Listesi

Bu kontrol listesi; otomotiv tedarikçilerinin TISAX değerlendirmesi öncesinde kendi organizasyonel ve teknik altyapılarını sistematik biçimde denetlemeleri amacıyla 11 kritik modül altında yapılandırılmıştır.

---

## 1. Değerlendirme Kapsamının Belirlenmesi (Scope Definition)
- [ ] Tesis adresi, üretim holleri, AR-GE ofisleri ve veri merkezleri açıkça sınırlandırıldı mı?
- [ ] ENX Portalı üzerinde oluşturulacak Kapsam (Scope ID) ile şirket tüzel kişiliği (Participant ID) eşleştirildi mi?
- [ ] Birden fazla lokasyon varsa "Standart Kapsam" mı yoksa "Genişletilmiş Kapsam" mı seçileceği netleştirildi mi?
- [ ] Kapsam dışı bırakılan fiziksel veya operasyonel alanların gerekçesi belgelendi mi?

---

## 2. Müşteri (OEM) Gereksinimlerinin Belirlenmesi
- [ ] Hangi ana otomotiv üreticisi (OEM - VW, BMW, Mercedes vb.) TISAX etiketi talep ediyor?
- [ ] Müşterinin tedarikçi şartnamesinde (CSR - Customer Specific Requirements) belirtilen asgari gereksinimler incelendi mi?
- [ ] Müşterinin talep ettiği etiket paylaşım seviyesi (Sharing Level: Anonim, Seçili Ortaklar, Kamuya Açık) belirlendi mi?
- [ ] Değerlendirmenin tamamlanması için müşteriye taahhüt edilen son tarih nedir?

---

## 3. Uygulanabilir Değerlendirme Hedeflerinin Seçimi (Assessment Objectives)
- [ ] **Bilgi Güvenliği (Information Security):**
  - [ ] *Info High (Yüksek Koruma İhtiyacı)* — Gizli teknik çizimler, fiyat teklifleri.
  - [ ] *Info Very High (Çok Yüksek Koruma İhtiyacı)* — Gizli AR-GE projeleri, henüz lansmanı yapılmamış stratejik veriler.
  - [ ] *Availability High / Very High* — Just-in-Time / Just-in-Sequence üretim yapan ve duruş maliyeti kritik tesisler.
- [ ] **Prototip Koruması (Prototype Protection):**
  - [ ] *Proto Parts (Prototip Parçalar)* — Fiziksel olarak gizlenen parça ve komponentler.
  - [ ] *Proto Vehicles (Prototip Araçlar)* — Test sürüşü ve kamuflajlı araç operasyonları.
  - [ ] *Test Vehicles (Test Araçları)* — Modifiye edilmiş seri üretim veya deneme araçları.
- [ ] **Veri Koruma (Data Protection):**
  - [ ] AB GDPR veya KVKK Madde 28 uyarınca özel nitelikli kişisel veri işleme durumu var mı?

---

## 4. Kritik Bilgi Varlıklarının Belirlenmesi
- [ ] CAD/CAM çizimleri, 3D modelleme verileri ve parça kalıp dosyaları envantere kaydedildi mi?
- [ ] Telematik yazılımları, ECU firmware kaynak kodları ve test logları sınıflandırıldı mı?
- [ ] Bilgi varlıklarının gizlilik, bütünlük ve erişilebilirlik (C-I-A) etki analizleri yapıldı mı?
- [ ] Varlık sahipleri (Asset Owners) departman bazında yazılı olarak atandı mı?

---

## 5. Tedarikçi ve Üçüncü Taraf Bağımlılıkları
- [ ] Kritik müşteri verilerini paylaşan alt yükleniciler ve kalıpçılar sözleşmesel olarak denetlendi mi?
- [ ] Alt tedarikçilerden TISAX etiketi veya ISO/IEC 27001 belgesi talep ediliyor mu?
- [ ] Bulut ve SaaS sağlayıcılarının (CAD yazılımı, ERP, yedekleme) güncel SOC 2 / ISO 27001 raporları alındı mı?
- [ ] Tedarikçi sözleşmelerinde gizlilik hükümleri (NDA) ve bilgi güvenliği ekleri güncel mi?

---

## 6. Prototip Koruması (Uygulanabilir ise)
- [ ] Prototip depolama alanları fiziksel olarak izole edildi mi (tavan yüksekliğinde duvarlar, opak camlar)?
- [ ] Prototip alanına girişlerde fotoğraf çekme ve kayıt cihazı yasağı uygulanıyor mu?
- [ ] Prototip parçaların sevkiyatında mühürlü taşıma kutuları ve GPS takibi kullanılıyor mu?
- [ ] Prototip imhasında yetkili personel gözetimi ve imha tutanağı prosedürü işletiliyor mu?

---

## 7. Fiziksel Güvenlik ve Çevre Kontrolleri
- [ ] Tesis sınırları çit, bariyer ve 7/24 CCTV ile izleniyor mu?
- [ ] Sistem odaları ve AR-GE birimleri için iki faktörlü fiziksel geçiş (Kart + Biyometrik veya Kart + PIN) devrede mi?
- [ ] Ziyaretçiler için kimlik kontrolü, refakat kuralı ve ziyaretçi kayıt defteri/yazılımı işletiliyor mu?
- [ ] CCTV kayıtları mevzuata ve müşteri sözleşmelerine uygun sürede (asgari 30–90 gün) saklanıyor mu?

---

## 8. Bilişim ve Erişim Güvenliği (IT & IAM)
- [ ] CAD/CAM ve tasarım ağları kurumsal ofis ağından ve misafir ağından VLAN / Güvenlik Duvarı ile ayrıldı mı?
- [ ] Uzaktan erişimlerde (VPN) zorunlu Çok Faktörlü Kimlik Doğrulama (MFA) açık mı?
- [ ] Ayrıcalıklı hesaplar (Domain Admin, Root) için PAM / Jumpbox çözümü kullanılıyor mu?
- [ ] İşten ayrılan veya pozisyonu değişen personelin hesapları 24 saat içinde kapatılıyor mu?

---

## 9. Risk ve Olay Yönetimi
- [ ] VDA ISA kriterlerine uygun bir Bilgi Güvenliği Risk Değerlendirmesi yapıldı mı?
- [ ] Güvenlik ihlal olayları için 7/24 acil müdahale (CSIRT / SOME) ekibi ve eskalasyon şeması tanımlandı mı?
- [ ] Müşteri verisini etkileyen siber olayların OEM'e bildirilmesi için iletişim kanalları belirlendi mi?
- [ ] Yılda en az bir kez fidye yazılımı (ransomware) ve felaket kurtarma senaryo tatbikatı yapıldı mı?

---

## 10. Kanıt Dosyası Hazırlığı (Audit Evidence Repository)
- [ ] Tüm politika, prosedür ve yönergelerin onaylı, versiyonlu PDF nüshaları arşivlendi mi?
- [ ] Son 6 aylık zafiyet tarama, sızma testi ve kapatılan açıkların bilet kayıtları toplandı mı?
- [ ] Sistem odası giriş logları, temiz masa / temiz ekran denetim tutanakları dosyalandı mı?
- [ ] Çalışanların yıllık bilgi güvenliği farkındalık eğitimi katılım listeleri hazırlandı mı?

---

## 11. Düzeltici Faaliyetler ve Takip (CAP - Corrective Action Plan)
- [ ] Denetim öncesi iç değerlendirmede tespit edilen tüm uygunsuzluklar için aksiyon planı açıldı mı?
- [ ] Olası bir minör bulgu durumunda akredite denetim firmasına sunulacak CAP süreci (maksimum 9 ay) anlaşıldı mı?
- [ ] Düzeltici faaliyetlerin kök neden analizi (5 Neden / Balık Kılçığı) metodolojisiyle dokümante edildi mi?
