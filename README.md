# Emre Boss Menu Updates

Emre Boss Menu update/release repository'si.

Bu herkese açık repository yalnızca uygulama güncelleme dosyaları, sürüm notları ve release manifestleri için kullanılır. Uygulamanın kaynak kodu burada tutulmaz.

## Başlangıç durumu

Henüz gerçek bir sürüm veya EXE yayımlanmamıştır. Kökteki `version.json`, `0.0.0` sürümüyle hazırlanmış, aktif olmayan bir örnektir; `downloadUrl` ve `sha256` alanları bilerek boştur.

Updater bu boş alanları güncelleme bulunmadığı şeklinde değerlendirmeli ve indirme başlatmamalıdır. Gerçek bir sürüm yayımlanırken sürüm numarası, gerçek release dosyasının indirme URL'si, SHA-256 değeri ve sürüm notları birlikte güncellenmelidir.

Repository herkese açık olduğundan updater manifesti ve yayımlanmış release dosyalarını kullanıcı tokenı olmadan okuyabilir.
