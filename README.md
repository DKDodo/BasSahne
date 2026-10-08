# BasSahne

Bas, elektro, akustik ve klasik gitar için geliştirilen telefon ve bilgisayar uygulaması.

Bu depo kullanım bilgileri ve **herkese açık sürümler** içindir. Projenin kaynak kodu özel depoda tutulur.

## Windows

[Son Windows sürümü](https://github.com/DKDodo/BasSahne/releases/latest)

ZIP paketini bir klasöre çıkarıp `BasSahnePC.exe` ile çalıştır. Java ayrıca kurulmaz. **Güncellemeler** düğmesi yeni Windows sürümünü kontrol eder, paketi indirir ve doğruladıktan sonra geçişi başlatır. Otomatik denetim kapatılabilir; paket indirme ve kurulum kullanıcı seçimiyle yapılır.

Pedalboard dosyaları güncelleme paketinden ayrıdır. Önceki uygulama sürümü korunur. Geçişten önce kaydedilmemiş değişiklikler için kayıt seçimi sunulur.

## Mevcut özellikler

- Dört enstrüman profili ve altı yuvalı yerel pedalboard düzenleme.
- Kısa synth ses örnekleri.
- Manuel başlatılan kromatik akort: nota, Hz, sent ve pes/tiz göstergesi.
- Windows için GitHub sürüm denetimi ve indirme.

Bu bir geliştirme önizlemesidir. Gerçek bas/ses kartı ölçüm doğruluğu ve sahne kabulü henüz tamamlanmadı. Canlı pedal zinciri, amfi/kabin, gerçekçi enstrüman dönüşümü, üyelik ve telefonla eşitleme sonraki geliştirme adımlarıdır.

## Güncelleme ve gizlilik

Sürüm denetimi GitHub API'ye bağlanır. İndirme GitHub sürüm dosyalarından yapılır. Pedalboard içeriği ve ses gönderilmez; uygulamada GitHub giriş bilgisi gerekmez. Normal internet bağlantısı bilgileri GitHub hizmetlerine ulaşır. İndirilen Windows ZIP'inin SHA-256 ve boyutu sürüm manifestiyle karşılaştırılır; bu karşılaştırma bağımsız Windows kod imzası değildir.

Android güncellemeleri bu Windows kanalı üzerinden kurulmaz. Google Play yayını henüz yapılmadı.
