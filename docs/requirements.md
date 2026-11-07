# Proje Analiz Belgesi — Etkileşimli Ders Deneyimi Panosu

## 1. Projenin Amacı

Etkileşimli Ders Deneyimi Panosu, öğrencilerin haftalık ders içeriklerini, öğrenme hedeflerini, görevlerini ve ilerlemelerini tek bir web uygulaması üzerinden takip etmelerini sağlamak amacıyla geliştirilecektir.

Uygulama, öğrencilerin öğrenme sürecini planlamasını, tamamladıkları görevleri takip etmesini ve kalan işlerini kolayca görmesini sağlayacaktır.

## 2. Hedef Kullanıcılar

### Birincil kullanıcılar
- Derslerini ve haftalık öğrenme hedeflerini takip etmek isteyen üniversite öğrencileri
- Görevlerini düzenlemek ve ilerlemelerini görmek isteyen öğrenciler

### İkincil kullanıcılar
- Öğrencilerin ders ve proje ilerlemesini incelemek isteyen öğretim elemanları

İlk sürümün temel kullanım senaryosu öğrenci odaklıdır.

## 3. Kullanıcı Hikâyeleri

### US-01: Haftalık dersleri görüntüleme
Bir öğrenci olarak, haftalık ders ve öğrenme kartlarını görüntülemek istiyorum; böylece o hafta hangi konulara odaklanmam gerektiğini bilebilirim.

**Kabul kriterleri:**
- Haftalar anlaşılır biçimde listelenmelidir.
- Her haftanın ders veya öğrenme içeriği görüntülenebilmelidir.

### US-02: Görevleri görüntüleme
Bir öğrenci olarak, görev ve mini etkinliklerimi listelemek istiyorum; böylece yapmam gerekenleri takip edebilirim.

**Kabul kriterleri:**
- Görevler başlık ve durum bilgisiyle gösterilmelidir.
- Görevlerin tamamlanma durumu değiştirilebilmelidir.

### US-03: Görevleri filtreleme ve arama
Bir öğrenci olarak, görevlerimi durumlarına göre filtrelemek ve arama yapmak istiyorum; böylece belirli bir göreve hızlıca ulaşabilirim.

**Kabul kriterleri:**
- Görevler durumlarına göre filtrelenebilmelidir.
- Arama alanı görev başlıklarında eşleşme bulabilmelidir.

### US-04: Genel ilerlemeyi görme
Bir öğrenci olarak, tamamladığım görevlerin genel ilerlemeye etkisini görmek istiyorum; böylece ne kadar ilerlediğimi anlayabilirim.

**Kabul kriterleri:**
- Tamamlanan görev sayısı gösterilmelidir.
- İlerleme göstergesi görev durumlarıyla tutarlı biçimde güncellenmelidir.

### US-05: Mobil cihazlarda kullanma
Bir öğrenci olarak, uygulamayı telefonumdan da kullanmak istiyorum; böylece ders planıma farklı cihazlardan erişebilirim.

**Kabul kriterleri:**
- İçerik dar ekranlarda taşma oluşturmamalıdır.
- Temel işlemler mobil ekranda kullanılabilir olmalıdır.

### US-06: Görünümü kişiselleştirme
Bir öğrenci olarak, aydınlık veya karanlık tema seçmek istiyorum; böylece arayüzü tercihlerime göre kullanabilirim.

**Kabul kriterleri:**
- Tema seçimi arayüzün renklerini değiştirmelidir.
- Seçilen tema mümkünse sonraki ziyaretlerde korunmalıdır.

### US-07: Verileri koruma
Bir öğrenci olarak, görev durumlarımın tarayıcıda saklanmasını istiyorum; böylece sayfayı yenilediğimde verilerimi kaybetmem.

**Kabul kriterleri:**
- Görev durumları localStorage üzerinden saklanmalıdır.
- Sayfa yeniden açıldığında kayıtlı veriler yüklenmelidir.

## 4. Fonksiyonel Gereksinimler

- FR-01: Sistem haftalık ders ve öğrenme kartlarını göstermelidir.
- FR-02: Sistem görevleri ve mini etkinlikleri listelemelidir.
- FR-03: Kullanıcı görev durumlarını değiştirebilmelidir.
- FR-04: Kullanıcı görevlerde arama yapabilmeli ve filtreleme uygulayabilmelidir.
- FR-05: Sistem genel ilerleme göstergesi sunmalıdır.
- FR-06: Arayüz mobil ve masaüstü ekranlarına uyum sağlamalıdır.
- FR-07: Kullanıcı aydınlık ve karanlık tema arasında geçiş yapabilmelidir.
- FR-08: Uygulama, gerekli kullanıcı verilerini localStorage üzerinden saklayabilmelidir.
- FR-09: Temel kontroller klavye ile kullanılabilir olmalıdır.
- FR-10: Form ve etkileşim kontrollerinde anlaşılır etiketler bulunmalıdır.

## 5. Fonksiyonel Olmayan Gereksinimler

- Kullanıcı arayüzü anlaşılır ve tutarlı olmalıdır.
- Kod okunabilir, modüler ve bakımı kolay olacak şekilde düzenlenmelidir.
- Arayüz farklı ekran boyutlarında kullanılabilir olmalıdır.
- Metinler ile arka plan arasında yeterli renk kontrastı bulunmalıdır.
- Tarayıcı konsolunda temel kullanım sırasında beklenmeyen hatalar oluşmamalıdır.
- Gizli bilgiler, parolalar veya API anahtarları repository içerisine eklenmemelidir.

## 6. Teknoloji ve Mimari

İlk sürüm aşağıdaki teknolojilerle geliştirilecektir:

- HTML: Sayfa yapısı
- CSS: Görsel tasarım ve responsive düzen
- JavaScript: Etkileşimler ve uygulama mantığı
- localStorage: Tarayıcıda veri saklama
- JSON: Gerektiğinde örnek veya yapılandırılmış veriler

İlk sürüm için veritabanı ve backend zorunlu değildir. Kod, sorumlulukları anlaşılır dosyalara ayrılarak geliştirilecektir.

## 7. Proje Kapsamı

### Kapsam dahilinde
- Haftalık ders ve öğrenme kartları
- Görev listesi ve durum yönetimi
- Arama ve filtreleme
- Genel ilerleme göstergesi
- Responsive tasarım
- Aydınlık ve karanlık tema
- Tarayıcıda veri saklama
- Temel erişilebilirlik kontrolleri
- Test, README ve kullanıcı dokümantasyonu

### Kapsam dışında
- Kullanıcı hesabı ve sunucu taraflı kimlik doğrulama
- Bulut tabanlı veri senkronizasyonu
- Zorunlu ilişkisel veritabanı
- Karmaşık backend servisleri
- Gerçek zamanlı çok kullanıcılı çalışma

Bu özellikler ilk sürümün zorunlu gereksinimleri değildir.

## 8. Test ve Kabul Planı

- Haftalık ders kartlarının doğru görüntülendiği kontrol edilir.
- Görev ekleme veya mevcut görev durumunu değiştirme akışı test edilir.
- Arama ve filtreleme sonuçları doğrulanır.
- Görev tamamlandığında ilerleme göstergesinin güncellendiği kontrol edilir.
- Sayfa yenilendiğinde kayıtlı verilerin korunduğu test edilir.
- Tema değişikliğinin arayüze uygulandığı doğrulanır.
- Mobil ve masaüstü görünümleri kontrol edilir.
- Klavye ile temel kontrollerin kullanılabildiği test edilir.
- README yönergeleri izlenerek proje temiz bir ortamda çalıştırılır.

## 9. Dört Haftalık Geliştirme Planı

### 1. hafta — İhtiyaç analizi
- Gereksinimleri netleştirme
- Kullanıcı hikâyelerini ve kabul kriterlerini belirleme
- Repository ve görev panosunu oluşturma
- Ekip sorumluluklarını paylaşma

### 2. hafta — Tasarım ve iskelet
- Sayfa yapısını ve görsel tasarımı oluşturma
- Temel HTML, CSS ve JavaScript yapısını kurma
- İlk çalışan arayüzü hazırlama

### 3. hafta — Geliştirme ve test
- Görev yönetimi, arama ve filtreleme özelliklerini geliştirme
- localStorage entegrasyonunu tamamlama
- Responsive tasarım ve tema özelliklerini test etme

### 4. hafta — Teslim hazırlığı
- Son testleri ve hata düzeltmelerini yapma
- README ve kullanıcı dokümantasyonunu tamamlama
- Proje raporu ve sunumu hazırlama
- Çalışan demoyu teslim etme

## 10. Teslim Kriterleri

Proje teslim edilebilir sayılmak için:
- Temel işlevleri çalışan bir web uygulaması sunmalıdır.
- Kaynak kod GitHub repository'sinde bulunmalıdır.
- Commit geçmişi bireysel katkıları göstermelidir.
- README kurulum ve kullanım bilgilerini içermelidir.
- Gereksinim ve test sonuçları dokümante edilmelidir.
- Sunum ve demo için çalışır bir sürüm hazır olmalıdır.
